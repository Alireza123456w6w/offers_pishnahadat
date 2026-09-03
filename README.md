# Offers Pishnahadat — نسخهٔ استاتیک

این پوشه یک سایت کاملاً استاتیک است (HTML + JS + CSS) و به سرور Node نیاز ندارد.

## آپلود در GitHub Pages
1. همهٔ فایل‌های داخل این پوشه (شامل `index.html`, `assets/`, `.nojekyll`) را در ریشهٔ ریپازیتوری آپلود کنید.
2. در Settings → Pages، گزینهٔ Source را روی `Deploy from a branch` و شاخهٔ `main` / پوشهٔ `/ (root)` بگذارید.
3. چند دقیقه بعد سایت روی آدرس GitHub Pages بالا می‌آید.

## صفحه‌ها
- `#/` خانه
- `#/track` رهگیری پیام
- `#/admin` ورود مدیر
- `#/admin/messages` مدیریت پیام‌ها
- `#/admin/admins` مدیریت مدیران

مسیرها با hash کار می‌کنند تا در هر ساب‌فولدری از GitHub Pages بدون خطای 404 اجرا شوند.
دیتابیس Firebase بدون تغییر متصل است.
