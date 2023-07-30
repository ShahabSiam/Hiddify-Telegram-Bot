

<p align="center">
  <a href="https://github.com/B3H1Z/Hiddify-Telegram-Bot" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/screenshots/icon.png?raw=True">
      <img width="200" height="200" src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/screenshots/icon.png?raw=True">
    </picture>
  </a>
</p>
<p align="center">
	<a href="./README.md">
	English
	</a>
	|
	<a href="./README-FA.md">
	فارسی
	</a>

</p>

<h1 align="center"/>ربات Hidy</h1>

با استفاده از این ربات می‌توانید پنل Hiddify خود را از طریق تلگرام مدیریت کنید.

ما در نسخه آزمایشی (BETA) هستیم و برای بهبود آن در حال کار هستیم. لطفاً هر گونه باگ یا مشکلی که پیدا می‌کنید را گزارش دهید.

لطفاً توجه داشته باشید که این ربات <b>رسمی نیست</b> و هیچ ارتباطی با Hiddify ندارد.

بعضی از ویژگی‌ها عبارتند از:
- [x] افزودن کاربران
- [x] حذف کاربران
- [x] ویرایش کاربران
- [x] نمایش لیست کاربران
- [x] جستجوی کاربران (بر اساس نام، تنظیمات، UUID)
- [x] نمایش اطلاعات کاربران (نام، ترافیک، تاریخ و غیره)
- [x] نمایش پیکربندی‌ها و لینک‌های اشتراک کاربر
- [x] دریافت پشتیبان از پنل شما
- [x] نمایش وضعیت سرور (رم، پردازنده، دیسک)
- [x] و غیره...

## نصب
     sudo bash -c "$(curl -Lfo- https://raw.githubusercontent.com/B3H1Z/Hiddify-Telegram-Bot/main/install.sh)"

#
### نصب دستی
- #### کلون کردن مخزن و ورود به آن

      git clone https://github.com/B3H1Z/Hiddify-Telegram-Bot.git /opt/Hiddify-Telegram-Bot && cd /opt/Hiddify-Telegram-Bot

- #### نصب نیازمندی‌ها

      pip install -r /opt/Hiddify-Telegram-Bot/requirements.txt
- #### حالا فایل config.py را اجرا کرده و فیلدهای مورد نیاز را پر کنید تا یک فایل config.json تولید شود.

      python3 /opt/Hiddify-Telegram-Bot/config.py

- #### فیلدهای مورد نیاز عبارتند از:

1. `شناسه تلگرام ادمین` : آن را از [ربات User Info](https://t.me/userinfobot) بگیرید (مثال: `123456789`)
2. `توکن ربات تلگرام` : آن را از [BotFather](https://t.me/BotFather) بگیرید (
   مثال: `1234567890:ABCdEfGhIjKlMnOpQrStUvWxYz`)
3. `آدرس پنل Hiddify` : آدرس پنل Hiddify خود را وارد کنید (
   مثال: `https://panel.example.com/7frgemkvtE0/78854985-68dp-425c-989b-7ap0c6kr9bd4`) <b>دقیقاً مانند این الگو!</b>
4. `زبان ربات` : گزینه‌ها `en` و `fa` می‌باشند [پیش‌فرض `fa`]

- ### حالا ربات را در پس‌زمینه با استفاده از nohup اجرا کنید

      nohup python3 /opt/Hiddify-Telegram-Bot/hiddifyTelegramBot.py &

  حالا می‌توانید از ربات در تلگرام با دستور `/start` استفاده کنید.


## دستورات
- ### برای به‌روزرسانی ربات از این دستور استفاده کنید

      cd /opt/Hiddify-Telegram-Bot/ && chmod +x update.sh && ./update.sh
- ### برای راه‌اندازی مجدد ربات از این دستور استفاده کنید

      cd /opt/Hiddify-Telegram-Bot/ && chmod +x restart.sh && ./restart.sh
- ### برای متوقف کردن ربات از این دستور استفاده کنید

      pkill -9 -f hiddifyTelegramBot.py
- ### برای دریافت لاگ ربات از این دستور استفاده کنید

      cat /opt/Hiddify-Telegram-Bot/hiddify-telegram-bot.log
- ### برای دریافت تنظیمات ربات از این دستور استفاده کنید
      cat /opt/Hiddify-Telegram-Bot/config.json

## عکس‌های ن

مایه
بعضی از عکس‌های نمایه ربات:
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/screenshots/Keyboard.PNG?raw=True" width=50% height=50%>
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/screenshots/UsersList.PNG?raw=True" width=50% height=50%>
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/screenshots/UserInfo.PNG?raw=True" width=50% height=50%>
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/screenshots/EditUser.PNG?raw=True" width=50% height=50%>
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/screenshots/ConfigAndSub.PNG?raw=True" width=50% height=50%>
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/screenshots/Search.PNG?raw=True" width=50% height=50%>
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/screenshots/AddUser.PNG?raw=True" width=50% height=50%>
- <img src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/screenshots/BackupAndStartus.PNG?raw=True" width=50% height=50%>
```

Please note that I've translated the content, including the code snippets and URLs, to Persian (Farsi) language.