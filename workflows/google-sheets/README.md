# google-sheets Workflows


## 📊 انتقال خودکار اطلاعات MySQL به Google Sheets
: ### workflows/google-sheets/Import data from MySQL into Google Sheets.json
این ورک‌فلو به‌صورت زمان‌بندی‌شده اطلاعات را از دیتابیس **MySQL** دریافت کرده، به **Google Sheets** منتقل می‌کند و پس از اتمام عملیات یک پیام اطلاع‌رسانی در **تلگرام** ارسال می‌کند. <FileCite ref_id="turn1file0" line_range_start={6} line_range_end={67}/>

### ✨ کاربردها

* بکاپ خودکار اطلاعات دیتابیس
* انتقال داده‌ها به Google Sheets
* گزارش‌گیری و تحلیل داده‌ها
* اطلاع از موفقیت اجرای فرآیند در تلگرام

### 🧩 نودهای استفاده‌شده

| نود               | وظیفه                             |
| ----------------- | --------------------------------- |
| **Cron**          | اجرای خودکار ورک‌فلو در زمان مشخص |
| **MySQL**         | دریافت اطلاعات با اجرای Query     |
| **Google Sheets** | افزودن داده‌ها به شیت             |
| **Telegram**      | ارسال پیام پایان عملیات           |

### 📥 ورودی

=============================== تقدیمتون 😊

داده‌های جدول `books` از دیتابیس MySQL. <FileCite ref_id="turn1file0" line_range_start={25} line_range_end={45}/>

### 📤 خروجی

تمام رکوردها در Google Sheets ذخیره شده و یک پیام تأیید در تلگرام ارسال می‌شود. <FileCite ref_id="turn1file0" line_range_start={42} line_range_end={67}/>
