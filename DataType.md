<h1 dir="rtl">انواع Data Type ها در پایگاه داده</h1>
<h2 dir="rtl">احمد میرزائی</h2>

<div dir="rtl">
در پایگاه داده‌ها، انواع داده‌ها (Data Types) برای تعریف نوع اطلاعاتی که در ستون‌های جداول ذخیره می‌شود استفاده می‌شوند. انواع داده‌های مختلف بسته به نوع پایگاه داده می‌توانند متفاوت باشند، اما به طور کلی به دسته‌های زیر تقسیم می‌شوند:
</div>
</br>


<div dir="rtl">
اعداد صحیح (Integer Types):
</br>
- INT: عدد صحیح با اندازه معمولی.
</br>
- SMALLINT: عدد صحیح کوچک‌تر.
</br>
- BIGINT: عدد صحیح بزرگ‌تر.
</br>
- TINYINT: عدد صحیح کوچک (معمولاً ۸ بیتی).
</br>
</br>
اعداد اعشاری (Floating Point Types):
</br>
- FLOAT: عدد اعشاری با دقت کمتر.
</br>
- DOUBLE: عدد اعشاری با دقت بیشتر.
</br>
- DECIMAL (یا NUMERIC): عدد اعشاری با دقت ثابت که برای محاسبات مالی مناسب است.
</br>
</br>
رشته‌ها (String Types):
</br>
- CHAR: رشته با طول ثابت.
</br>
- VARCHAR: رشته با طول متغیر.
</br>
- TEXT: رشته با طول زیاد.
</br>
</br>
تاریخ و زمان (Date and Time Types):
</br>
- DATE: تاریخ (سال، ماه، روز).
</br>
- TIME: زمان (ساعت، دقیقه، ثانیه).
</br>
- DATETIME: ترکیب تاریخ و زمان.
</br>
- TIMESTAMP: زمان با قابلیت نگهداری اطلاعات منطقه زمانی.
</br>
</br>
باینری (Binary Types):
</br>
- BINARY: داده باینری با طول ثابت.
</br>
- VARBINARY: داده باینری با طول متغیر.
</br>
- BLOB: داده باینری بزرگ، مناسب برای ذخیره تصاویر و فایل‌ها.
</br>
</br>
انواع خاص (Special Types):
</br>
- BOOLEAN: نوع داده بولین (درستی/نادرستی).
</br>
- ENUM: نوع داده شمارشی که از مجموعه‌ای از مقادیر از پیش تعریف شده استفاده می‌کند.
</br>
- SET: نوع داده‌ای که می‌تواند چندین مقدار را از یک مجموعه از پیش تعریف شده نگهداری کند.
</br>
</br>
این دسته‌بندی‌ها ممکن است بسته به سیستم مدیریت پایگاه داده (مانند MySQL، PostgreSQL، Oracle و SQL Server) کمی متفاوت باشند و هر سیستم ممکن است انواع داده‌های خاص خود را داشته باشد. برای مثال، MySQL و PostgreSQL انواع داده‌های JSON را برای ذخیره‌سازی اسناد JSON پشتیبانی می‌کنند.
</div>
