# ساخت APK فقط با گوشی

1. یک حساب GitHub بساز یا وارد حساب خودت شو.
2. یک Repository جدید بساز، مثلاً `FGC-App`.
3. فایل ZIP پروژه را روی گوشی دانلود و Extract کن.
4. محتویات پوشه پروژه را داخل Repository آپلود کن؛ فایل `.github/workflows/build-apk.yml` هم باید آپلود شود.
5. وارد تب **Actions** شو.
6. Workflow با نام **Build FGC APK** را باز کن.
7. اگر دستی اجرا می‌کنی، **Run workflow** را بزن.
8. بعد از سبز شدن اجرای Build، وارد همان Run شو.
9. پایین صفحه در بخش **Artifacts** روی **FGC-v3-APK** بزن و ZIP خروجی را دانلود کن.
10. ZIP خروجی را باز کن؛ داخلش `app-debug.apk` است. آن را روی گوشی نصب کن.

اگر GitHub هنگام آپلود فایل‌های مخفی مثل `.github` را نشان نداد، از نسخه وب GitHub و گزینه Add file > Upload files استفاده کن و مطمئن شو مسیر `.github/workflows/build-apk.yml` حفظ شده است.
