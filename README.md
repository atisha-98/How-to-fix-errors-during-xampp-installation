# How-to-fix-errors-during-xampp-installation

Persian language

در این جا به بررسی مشکلاتی که در هنگام استفاده از زمپ سرور عموما بین کاربران رخ میدهد میپردازیم تا با استفاده از راهکارهای موجود بدون هیچ خطایی اقدام به رفع مشکلات موجود در برنامه زمپ کنید

رفع خطای api-ms-win-crt-runtime-l1-1-0.dll
برای رفع این خطا ابتدا ویندوز خودتونو به آخرین نسخه موجود آپدیت کنید و سپس یک بار ویندوزتون رو ری‌استارت کنید و مجددا زمپ رو اجرا کنید، اگر باز هم مشکل پا برجا بود مجددا با مراجعه به مرکز به‌روزرسانی در ویندوز یک بار دیگه چک کنید تا ببینید ویندوز به صورت کامل آپدیت شده یا نه، اگر آپدیت جدیدی وجود داشت باز هم آپدیت کنید و پس از ری‌استارت مجدد سیستم زمپ را اجرا کنید، در صورتی که کاربر خوش‌شانسی باشید مشکل شما رفع خواهد شد اما در غیر این صورت لازمه تا اقدام به نصب یکی از فایل‌های ویندوز کنید بنابراین با مراجعه به آدرس
Update for Universal C Runtime in Windows 
بر اساس نسخه ویندوز ی که استفاده میکنید فایل مرتبط با نسخه سیستم عامل ویندوز را دانلود کرده و نصب کنید سپس مجددا با ری استارت کردن ویندوز برنامه زمپ را اجرا کنید تا مشکل شما برطرف شود

![api-ms-win-crt-runtime-xampp](https://user-images.githubusercontent.com/119763541/205466409-af5c686c-f9b4-4f07-851c-e2855c8632d0.jpg)

پس از انتخاب نسخه ویندوز مورد نظر مشابه تصویر زیر به صفحه دیگه‌ای هدایت خواهید شد که با کلیک بر روی دکمه 
Download
یک فایل با فرمت 
msu
با حجم خیلی کم در اختیار شما قرار میگیره، پس از دانلود روی فایل دانلود شده دابل کلیک کرده و پس از اجرا و نصب ساده سیستم خود را ری‌استارت کرده و برنامه زمپ را اجرا کنید تا مشکل برطرف شود

![msu-windows-dll-xampp-error](https://user-images.githubusercontent.com/119763541/205466589-70e54ec8-c559-4744-ae6f-85180ada8687.jpg)

رفع خطای 
xampp-control.ini Access is denied

یکی دیگه از خطاهایی که ممکنه هنگام کار با زمپ یا نصب وردپرس روی لوکال هاست باهاش مواجه بشید، خطای 
xampp-control.ini
هست. اما نگران نباشید با تعریف یک سطح دسترسی ساده مشکل حل میشه. این ارور وقتی رخ میده که چندین مرتبه به صورت مکرر سرویس زمپ را ببندید. نکته: حتی اگه سرویس زمپ را به صورت 
run as administrator
باز کنید باز هم شاهده خطای سطح دسترسی غیر مجاز خواهید بود. بسیار ساده میشه تنظیماتی انجام داد که سرویس زمپ را تحت عنوان مدیریت و بدون خطا اجرا کنید

![php-control-in-xamp](https://user-images.githubusercontent.com/119763541/205466986-acf415e6-16d5-4492-b683-6a80ebb74742.jpg)

1-
برای رفع خطای 
xampp-control.ini access denied
تنها کافیست به محل نصب برنامه زمپ بروید

2-
در پوشه ای که زمپ در آن نصب شده به دنبال فایلی تحت عنوان 
xampp-control.ini
بگردید

3-
روی فایل 
xampp-control.ini
راست کلیک و گزینه 
Properties
را انتخاب کنید

4-
در پنجزه باز شده به سربرگ 
Compatibility
مراجعه کنید

5-
گزینه 
Run this program as an administrator
را فعال کنید

6-
روی دکمه 
ok 
کلیک کنید.

![xampp-control ini-Access-is-denied](https://user-images.githubusercontent.com/119763541/205467068-0b5124d7-2bf2-4a73-845e-d74df0fda5d1.jpg)

حالا سرویس را بسته و مجددا اجرا کنید. اکنون با سطح دسترسی مدیر قادر به استفاده از برنامه هستید





