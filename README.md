<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>منصة تدبير الشؤون القانونية - المديرية الإقليمية</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Tajawal', sans-serif; background-color: #f8fafc; }
    </style>
</head>
<body>

    <div class="flex h-screen overflow-hidden">
        
        <aside class="w-64 bg-slate-900 text-white flex flex-col">
            <div class="p-6 text-center border-b border-slate-700">
                <h2 class="text-xl font-bold uppercase tracking-wide">المديرية الإقليمية</h2>
                <p class="text-xs text-slate-400 mt-2">مصلحة الشؤون القانونية والتواصل</p>
            </div>
            <nav class="flex-1 p-4 space-y-2">
                <a href="#" class="block p-3 bg-blue-600 rounded-lg shadow-md transition">الرئيسية</a>
                <a href="#" class="block p-3 hover:bg-slate-800 rounded-lg transition">المنازعات القانونية</a>
                <a href="#" class="block p-3 hover:bg-slate-800 rounded-lg transition">اتفاقيات الشراكة</a>
                <a href="#" class="block p-3 hover:bg-slate-800 rounded-lg transition">التواصل والإعلام</a>
                <a href="#" class="block p-3 hover:bg-slate-800 rounded-lg transition">الأرشيف الرقمي</a>
            </nav>
            <div class="p-4 border-t border-slate-700">
                <button class="w-full bg-red-500 hover:bg-red-600 p-2 rounded-lg text-sm transition">تسجيل الخروج</button>
            </div>
        </aside>

        <main class="flex-1 flex flex-col overflow-y-auto">
            
            <header class="bg-white shadow-sm p-4 flex justify-between items-center">
                <div class="relative w-1/3">
                    <input type="text" placeholder="بحث عن ملف، شريك، أو رقم قضية..." class="w-full pr-10 pl-4 py-2 border rounded-full text-sm focus:outline-none focus:ring-2 focus:ring-blue-500">
                </div>
                <div class="flex items-center space-x-4 space-x-reverse">
                    <span class="text-sm font-medium">مرحباً، المسؤول الإقليمي</span>
                    <div class="w-10 h-10 bg-slate-200 rounded-full flex items-center justify-center">👤</div>
                </div>
            </header>

            <div class="p-8">
                
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-8">
                    <div class="bg-white p-6 rounded-xl shadow-sm border-r-4 border-blue-500">
                        <p class="text-sm text-gray-500">قضايا رائجة</p>
                        <h3 class="text-3xl font-bold text-slate-800">12</h3>
                    </div>
                    <div class="bg-white p-6 rounded-xl shadow-sm border-r-4 border-green-500">
                        <p class="text-sm text-gray-500">اتفاقيات نشطة</p>
                        <h3 class="text-3xl font-bold text-slate-800">45</h3>
                    </div>
                    <div class="bg-white p-6 rounded-xl shadow-sm border-r-4 border-orange-500">
                        <p class="text-sm text-gray-500">جلسات هذا الأسبوع</p>
                        <h3 class="text-3xl font-bold text-slate-800">3</h3>
                    </div>
                </div>

                <div class="bg-white rounded-xl shadow-sm overflow-hidden">
                    <div class="p-6 border-b flex justify-between items-center">
                        <h3 class="text-lg font-bold">آخر ملفات المنازعات</h3>
                        <button class="bg-blue-600 text-white px-4 py-2 rounded-lg text-sm hover:bg-blue-700">+ إضافة ملف جديد</button>
                    </div>
                    <table class="w-full text-right border-collapse">
                        <thead class="bg-slate-50 text-slate-600 text-sm">
                            <tr>
                                <th class="p-4 border-b">رقم الملف</th>
                                <th class="p-4 border-b">المحكمة</th>
                                <th class="p-4 border-b">الأطراف</th>
                                <th class="p-4 border-b">تاريخ الجلسة</th>
                                <th class="p-4 border-b">الحالة</th>
                                <th class="p-4 border-b">إجراءات</th>
                            </tr>
                        </thead>
                        <tbody class="text-sm text-slate-700">
                            <tr class="hover:bg-slate-50 transition">
                                <td class="p-4 border-b font-medium">2026/1205/45</td>
                                <td class="p-4 border-b">إدارية الرباط</td>
                                <td class="p-4 border-b">المديرية ضد (ع.أ)</td>
                                <td class="p-4 border-b">15 مايو 2026</td>
                                <td class="p-4 border-b"><span class="bg-orange-100 text-orange-600 px-2 py-1 rounded text-xs">قيد المداولة</span></td>
                                <td class="p-4 border-b">
                                    <button class="text-blue-600 hover:underline">تعديل</button>
                                </td>
                            </tr>
                            <tr class="hover:bg-slate-50 transition">
                                <td class="p-4 border-b font-medium">2026/1402/12</td>
                                <td class="p-4 border-b">ابتدائية الرشيدية</td>
                                <td class="p-4 border-b">شركة (X) ضد المديرية</td>
                                <td class="p-4 border-b">22 مايو 2026</td>
                                <td class="p-4 border-b"><span class="bg-blue-100 text-blue-600 px-2 py-1 rounded text-xs">جلسة مقبلة</span></td>
                                <td class="p-4 border-b">
                                    <button class="text-blue-600 hover:underline">تعديل</button>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                </div>

            </div>
        </main>
    </div>

</body>
</html>
