# Telegram Forward Message and File Bot

این پروژه یک ربات تلگرام است که پیام‌ها و انواع فایل‌ها را از یک کانال به کانال دیگر منتقل می‌کند. این ربات با استفاده از کتابخانه‌ی `pyTelegramBotAPI` نوشته شده است.

## شروع به کار

برای شروع به کار با این ربات، مراحل زیر را دنبال کنید:

### پیش‌نیازها

- `python` 3.x
- کتابخانه‌ی `pyTelegramBotAPI`

برای نصب `pyTelegramBotAPI` از pip استفاده کنید:
```bash
pip install pyTelegramBotAPI



در فایل کد، شناسه کانال‌ها و کلید API ربات خود را وارد کنید:

bot = telebot.TeleBot('کلید API ربات')

source_channel_id = 'شناسه کانال مبدا'
destination_channel_id = 'شناسه کانال مقصد'


برای اجرای ربات، فایل کد را اجرا کنید:

python python_program.py


توابع
channel_post(message)
این تابع پیام‌ها و فایل‌های دریافت شده در کانال مبدا را به کانال مقصد منتقل می‌کند. شامل متن‌ها، اسناد، عکس‌ها و ویدئوها.

run_bot()
این تابع ربات را راه‌اندازی و به صورت مداوم فعال نگه می‌دارد. در صورت بروز خطا، ربات پس از ۵ ثانیه مجدداً راه‌اندازی می‌شود.

یادداشت‌ها
مطمئن شوید که ربات شما به هر دو کانال مبدا و مقصد اضافه شده و دسترسی‌های لازم را دارد.

این کد برای استفاده‌ی شخصی شما بهینه‌سازی شده و نیاز به تغییرات در تنظیمات و دسترسی‌ها دارد.

برای اطلاعات بیشتر درباره‌ی pyTelegramBotAPI به مستندات رسمی مراجعه کنید.

کمک و پشتیبانی
برای کمک و پشتیبانی، می‌توانید به این بخش مراجعه کنید و یا با من تماس بگیری


