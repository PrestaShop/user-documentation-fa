---
description: General parameters
---

# پارامترهای عمومی

**پارامترهای عمومی**

صفحه "عمومی" تعداد زیادی تنظیمات خاص را نشان می دهد که نمی توانند در منوهای دیگری قرار بگیرند. با این وجود آنها ضروری هستند:

* **فعالسازی SSL.** SSL به معنی "لایه سوکت های امن" است و شامل TSL (برای "امنیت لایه حمل و نقل") است. هر دو پروتکل اینترنت رمزنگاری شده هستند که ارتباطات وب را ایمن میکنند. اطلاعات بیشتر در مورد این پروتکلها را در [ویکی پدیا](http://en.wikipedia.org/wiki/Secure\_Sockets\_Layer) بخوانید.

ارائه اتصال SSL به فروشگاه شما نه تنها برای هرگونه مبادله اینترنتی عالی است ، بلکه راهی عالی برای اطمینان خاطر مشتریان در مورد ایمنی داده های خود (احراز هویت، کارت اعتباری و غیره) است. در مرورگرهای مدرن، فعال بودن این گزینه به معنی امن بودن اتصال میباشد. اگر هاست شما از SSL پشتیبانی نمی کند ، با کلیک بر روی لینک، پشتیبانی SSL پرستاشاپ را فعال کنید. با این کار یک انتخابگر مشخص می شود ، که باید "بله" را انتخاب کنید. SSL در همه صفحات پرداخت و حساب فعال خواهد شد.

* **فعال سازی SSL در تمامی صفحات.** این گزینه فقط در صورتی موجود است که SSL را فعال کرده باشید. هنگام فعال بودن ، تمام صفحات فروشگاه شما از امنیت SSL برخوردار هستند (و نه فقط صفحات پرداخت و حساب).
* **افزایش امنیت بخش کاربری.** به منظور بهبود امنیت فرئشگاه، نشانه های امنیتی به فروشگاه شما اضافه میکند. در واقع، هر URL مخصوص یک SESSION مشتری است و نمی تواند در مرورگر دیگری استفاده شود ، بنابراین از هر اطلاعاتی که ممکن است در آن session ذخیره کرده باشند محافظت می کند.
* **اجازه به iframe ها در فیلدهای HTML.** این گزینه شما را قادر می سازد iframes را در قسمت های متن مانند توضیحات محصول قرار دهید. Iframes عناصر HTML هستند که امکان بارگذاری یک محتوای خارجی را در محتوای خود صفحه فراهم می کنند. توصیه می کنیم تا در صورت لزوم این گزینه را غیر فعال بگذارید.
* **استفاده از کتابخانه پالاینده HTML.** مشتریان می توانند با استفاده از فیلدهای متنی، اطلاعات (به عنوان مثال توضیحات محصول یا اطلاعات مربوط به مشتری) را به فروشگاه شما ارسال کنند. اما هکرها می توانند از این فیلدها برای ارسال کد مخرب به منظور تلاش برای هک کردن فروشگاه شما استفاده کنند. این گزینه تضمین می کند که هر گونه داده ارسال شده به فروشگاه شما امن است. شما اگر خیلی خوب متوجه هستید که چه کاری را انجام میدهد این گزینه را غیرفعال کنید.
* **نحوه گرد کردن.** پس از اعمال مالیات و تخفیف، قیمت می تواند رقم اعشار زیادی از جمله 420.333333 ریال را نشان دهد. نحوه گرد کردن در سراسر پرستاشاپ مانند نمایش قیمت بخش کاربری و همچنین در طی فرآیند محاسبه قیمت ( مالیات ها، تخفیف ها، و..) استفاده می شود. این گزینه برای مواردی که از قبل محاسبه شده اند تغییر زیادی ایجاد نمی کند اما تأثیر آن برای مواردی چون مجموع فاکتور پس از اعمال مالیات و تخفیفات قابل توجه خواهد بود.

شش حالت وجود دارد:

* **گرد گردن به بالا از صفر، هنگامی که در نیمه باشد(پیشنهاد شده).** این حالت پیشنهادی است. 42.55555 میشود 42.56.
* **گرد گردن رو به پایین به سمت صفر، هنگامی که در نیمه باشد.** 42.55555555 می شود 42.56.
* **گرد کردن به سمت مقدار زوج بعدی**. 42.55555555 می شود 42.56.
* **گرد کردن به سمت عدد فرد بعدی.** 42.55555555 می شود 42.56.
* **گرد کردن رو به بالا به نزدیک ترین مقدار.** 42.55555555 می شود 42.56.
* **گرد کردن رو به پایین به نزدیک ترین مقدار**. 42.55555555 می شود 42.55.
* **نوع گرد کردن.** این گزینه شما را قادر می سازد نوع گرد کردن را انتخاب کنید ، که می تواند در محاسبه کل تأثیر بگذارد. سه نوع موجود به ترتیب تدریجی وجود دارد:
  * **گرد کردن هر مورد.** قیمت هر قلم کالا قبل از محاسبه کل، گرد می شود. اگر بیش از یکی از موارد مشابه وجود داشته باشد ، هر یک از آنها قبل از محاسبه به طور جداگانه گرد می شوند.
  * **گرد کردن هر خط.** هر یک از اقلام قبل از محاسبه کل، گرد می شود. اگر بیش از یکی از موارد مشابه وجود داشته باشد ، گرد کردن بر روی مقدار کل آنها انجام می شود.
  * **گرد کردن کل.** پس از جمع شدن مقادیر همه موارد ، گرد کردن فقط در محاسبه نهایی انجام می شود.
* **تعداد اعداد اعشاری.** می توانید تعداد اعشار را انتخاب کنید که مقدار باید گرد شود. به عنوان مثال ، اگر "3" را انتخاب کنید ، 42.333333333 میشود 42.334.
* **نمایش برندها و فراهم کننده ها.** با فعال کردن این گزینه صفحات توزیع کنندگان و تولیدکنندگان را در بخش کاربری فروشگاه شما نمایش می دهد حتی زمانی که ماژول های مربوط به آن ها غیرفعال باشد.
* **نمایش پرفروشترین ها.** این گزینه صفحات بهترین فروشندگان را در بخش کاربری فعال می کند حتی زمانی که ماژول بلوک بهترین فروشنده ها غیر فعال باشد.
* **فعال سازی چند فروشگاهی.** این گزینه فروشگاه شما را از حالت تک فروشگاهی به چند فروشگاهی تبدیل میکند. صفحه جدیدی با نام "چند فروشگاهی" در منوی "پارامترهای پیشرفته" برای شما ظاهر می شود. در هر صفحه مدیریت این امکان برای شما وجود دارد تا تعیین کنید تغییرات به تمام فروشگاه ها، گروه خاصی از فروشگاه ها و یا تنها یک فروشگاه اعمال شود.

می توانید برای مطالعه بیش تر درباره ویژگی چند فروشگاهی در پرستاشاپ فصل "مدیریت چند فروشگاهی" از این راهنمای کاربری را مطالعه کنید.

* **فعالیت اصلی فروشگاه.** ممکن است هنگام نصب پرستاشاپ با خطای مربوط به فعالیت فروشگاه مواجه شوید. در این قسمت می توانید نوع فعالیت خود را انتخاب کنید.

![](<../../../.gitbook/assets/0 (53).png>)
