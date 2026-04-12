# ActNoTalk

موقع لعبة "ولا كلمة" جاهز للنشر كموقع ثابت على GitHub Pages.

## النشر عبر GitHub Pages

1. أنشئ مستودعًا جديدًا على GitHub وارفع ملفات المشروع إليه.
2. إذا كان اسم الفرع الرئيسي مختلفًا عن `main` أو `master`، حدّث الملف `.github/workflows/deploy-pages.yml` باسم الفرع الصحيح.
3. في GitHub افتح `Settings` ثم `Pages`.
4. من `Build and deployment` اختر `Source: GitHub Actions`.
5. ادفع أي تعديل جديد إلى الفرع الرئيسي، وسيبدأ النشر تلقائيًا.

## ماذا ينشر؟

يتم نشر ملفات الموقع العامة تلقائيًا، مع استبعاد الملفات المحلية وملفات المعاينة التالية:

- `category-theme-preview.html`
- `icon-preview.html`
- `mix-gallery.html`
- `words-grid.html`
- `.vscode/`
- `deploy.zip`

## ملاحظات

- رابط الموقع غالبًا سيكون بصيغة `https://USERNAME.github.io/REPOSITORY-NAME/`.
- إذا أردت لاحقًا نطاقًا مخصصًا، يمكن إضافته من إعدادات GitHub Pages.
