# جدول الدوام — تطبيق مجاني بالكامل

هذا التطبيق ثابت (Static PWA)، ولا يحتاج قاعدة بيانات أو اشتراك أو خادم.

## النشر المجاني على GitHub Pages
1. أنشئ مستودع GitHub جديدًا، مثل: `jadwal-dawam`.
2. ارفع **محتويات هذا المجلد** إلى جذر المستودع (index.html, app.js, styles.css, manifest.webmanifest, service-worker.js, icons).
3. من GitHub: Settings → Pages.
4. اختر Deploy from a branch، ثم Branch = main و Folder = /(root)، ثم Save.
5. بعد ظهور الرابط افتحه على iPhone من Safari.
6. مشاركة → إضافة إلى الشاشة الرئيسية.

## البيانات
- تُحفظ داخل الجهاز في LocalStorage.
- استخدم "تصدير نسخة احتياطية JSON" بشكل دوري.
- عند تغيير الجهاز، استورد ملف النسخة الاحتياطية.

## ملاحظة
مسح بيانات Safari/المتصفح قد يمسح بيانات التطبيق المحلية، لذلك النسخة الاحتياطية مهمة.
