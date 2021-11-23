---
description: Logs
---

# گزارشها

**گزارشها**

پارامترهای گزارشها

خطاها اتفاق میافتند. بیشتر اوقات، شما از آنها آگاهی ندارید زیرا پرستاشپ بی صدا آنها را اداره میکند. اما ممکن است بخواهید در مورد آنها اطلاعاتی کسب کنید، تا بتوانید رایجترینها را اصلاح کرده و ثبات بیشتری برای فروشگاه خود ایجاد کنید.

![](<../../../.gitbook/assets/0 (77).png>)

صفحه "گزارشها" جایی است که میتوانید به تمام اقدامات انجام شده در فروشگاه خود نگاهی بیندازید و بنابراین خطاهای PHP را که می تواند فروشگاه شما را آزار دهد پیدا کنید. آنها در جدول مرکزی صفحه ذکر شده اند و در 4 سطح ارائه شده اند:

* **1: فقط اطلاع رسانی.** اعلامیههای زمان اجرا. مشخص کنید که اسکریپت با چیزی روبرو شده است که میتواند خطایی را نشان دهد، اما در روند عادی اجرای اسکریپت نیز ممکن است اتفاق بیفتد.
* **2: هشدار.** هشدارهای زمان اجرا (خطاهای غیر کشنده). اجرای متن متوقف نیست.
* **3: خطا.**
* **4: اخطار فوری (از کار افتادن).** خطاهای مهلک زمان اجرا. اینها خطاهایی را نشان میدهد که نمیتوان از آنها بازیابی کرد، مانند مشکل تخصیص حافظه. اجرای متن متوقف شده است.

این توضیحات رسمی موجود در کتابچه راهنمای PHP است. [بیشتر](http://www.php.net/manual/fa/errorfunc.constants.php) بخوانید.

**صورت عملیات با ایمیل**

سطح خطاها همچنین به عنوان مقادیری برای ویژگی " صورت عملیات با ایمیل" عمل میکنند.

پرستاشاپ یک مقدار آخر را میافزاید، 5، که نشان میدهد مدیر نمیخواهد اعلانی دریافت کند، چه برای خطاهای جزئی و چه بزرگ.

![](<../../../.gitbook/assets/1 (58).png>)

ابزار ثبت خطا شما را قادر میسازد در صورت بروز خطا، یک اعلان ایمیل دریافت کنید. اعلانها به آدرس ایمیل صاحب فروشگاه ارسال میشوند و میتوانید درجه اهمیتی دریافت چنین ایمیلهایی را پیکربندی کنید:

* "1" اگر می خواهید در مورد همه چیز ، حتی کوچکترین اطلاعات بدانید.
* "3" اگر فقط می خواهید در مورد مسائل (خطاها و مسائل اصلی) بدانید.
* "4" اگر فقط می خواهید مسائل اصلی را حفظ کنید.
* "5" پیش فرض است ، به این معنی که هیچ اعلانی ارسال نمی شود.