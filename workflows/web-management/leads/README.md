# leads Workflows
lead_web.json
===============================
## 🌐 Lead Web Workflow

اتوماسیون دریافت لید از فرم وب‌سایت و ثبت خودکار اطلاعات در Google Sheets همراه با ارسال اعلان در تلگرام. <FileCite ref_id="turn0file0" line_range_start={6} line_range_end={24}/>

### ✨ What this workflow does

* دریافت اطلاعات فرم از طریق Webhook
* استخراج نام، شماره تماس و پیام
* ذخیره لید در Google Sheets
* ارسال نوتیفیکیشن به Telegram

### 🧩 Nodes

| Node              | Function                                                  |
| ----------------- | --------------------------------------------------------- |
| **Webhook**       | دریافت درخواست POST از فرم سایت                           |
| **Edit Fields**   | تبدیل داده‌های فرم به فیلدهای `name`، `phone` و `message` |
| **Google Sheets** | افزودن هر لید به یک ردیف جدید                             |
| **Telegram**      | ارسال خلاصه لید برای اطلاع‌رسانی                          |

### 📥 Input

* Name
* Phone
* Message

### 📤 Output

لید در Google Sheets ذخیره شده و هم‌زمان یک پیام در تلگرام ارسال می‌شود. <FileCite ref_id="turn0file0" line_range_start={40} line_range_end={132}/>

===============================
تقدیمتون 😊
