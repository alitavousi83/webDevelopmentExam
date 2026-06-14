عالی. بخش **CSS Box Model (مدل جعبه‌ای CSS)** از مهم‌ترین مباحث CSS است و تقریباً هر آزمونی از آن سؤال دارد. باید ترتیب اجزای Box Model را کاملاً حفظ باشی.

# سوالات چهارگزینه‌ای استاندارد

## مبحث: CSS Box Model

---

### سوال 1

مدل جعبه‌ای (Box Model) در CSS از چه اجزایی تشکیل شده است؟

الف) Width، Height، Color
ب) Content، Padding، Border، Margin
ج) Header، Footer، Section
د) Font، Color، Background

✅ **پاسخ صحیح: ب) Content، Padding، Border، Margin**

---

### سوال 2

داخلی‌ترین بخش Box Model کدام است؟

الف) Margin
ب) Border
ج) Content
د) Padding

✅ **پاسخ صحیح: ج) Content**

---

### سوال 3

کدام بخش فاصله بین محتوا و کادر (Border) را مشخص می‌کند؟

الف) Margin
ب) Padding
ج) Width
د) Height

✅ **پاسخ صحیح: ب) Padding**

---

### سوال 4

کدام بخش کادر اطراف عنصر را تشکیل می‌دهد؟

الف) Margin
ب) Border
ج) Padding
د) Content

✅ **پاسخ صحیح: ب) Border**

---

### سوال 5

کدام بخش فاصله بین عنصر و عناصر مجاور را مشخص می‌کند؟

الف) Border
ب) Padding
ج) Margin
د) Content

✅ **پاسخ صحیح: ج) Margin**

---

### سوال 6

ترتیب صحیح اجزای Box Model از داخل به خارج کدام است؟

الف) Margin → Border → Padding → Content
ب) Content → Padding → Border → Margin
ج) Content → Border → Padding → Margin
د) Padding → Content → Border → Margin

✅ **پاسخ صحیح: ب) Content → Padding → Border → Margin**

---

### سوال 7

کدام Property برای تنظیم فاصله داخلی استفاده می‌شود؟

الف) margin
ب) border
ج) padding
د) spacing

✅ **پاسخ صحیح: ج) padding**

---

### سوال 8

کدام Property برای تنظیم فاصله خارجی استفاده می‌شود؟

الف) border
ب) padding
ج) margin
د) content

✅ **پاسخ صحیح: ج) margin**

---

### سوال 9

کدام Property ضخامت کادر را تعیین می‌کند؟

الف) border-width
ب) margin-width
ج) padding-width
د) frame-width

✅ **پاسخ صحیح: الف) border-width**

---

### سوال 10

Property زیر مربوط به کدام بخش Box Model است؟

```css
padding: 20px;
```

الف) Content
ب) Border
ج) Margin
د) Padding

✅ **پاسخ صحیح: د) Padding**

---

### سوال 11

Property زیر مربوط به کدام بخش Box Model است؟

```css
margin: 10px;
```

الف) Margin
ب) Padding
ج) Border
د) Content

✅ **پاسخ صحیح: الف) Margin**

---

### سوال 12

کدام بخش در محاسبه فضای اشغال‌شده توسط عنصر نقش دارد؟

الف) فقط Content
ب) فقط Margin
ج) Content، Padding، Border و Margin
د) فقط Border

✅ **پاسخ صحیح: ج) Content، Padding، Border و Margin**

---

### سوال 13

اگر مقدار `padding` افزایش یابد چه اتفاقی می‌افتد؟

الف) فاصله داخلی عنصر بیشتر می‌شود.
ب) فاصله خارجی بیشتر می‌شود.
ج) عنصر مخفی می‌شود.
د) رنگ عنصر تغییر می‌کند.

✅ **پاسخ صحیح: الف) فاصله داخلی عنصر بیشتر می‌شود.**

---

### سوال 14

اگر مقدار `margin` افزایش یابد چه اتفاقی می‌افتد؟

الف) فاصله بین محتوا و کادر بیشتر می‌شود.
ب) فاصله عنصر با عناصر اطراف بیشتر می‌شود.
ج) ضخامت کادر افزایش می‌یابد.
د) متن بزرگ‌تر می‌شود.

✅ **پاسخ صحیح: ب) فاصله عنصر با عناصر اطراف بیشتر می‌شود.**

---

### سوال 15

کدام Property برای تعیین رنگ کادر استفاده می‌شود؟

الف) border-style
ب) border-color
ج) box-color
د) frame-color

✅ **پاسخ صحیح: ب) border-color**

---

### سوال 16

کدام Property نوع خط کادر را مشخص می‌کند؟

الف) border-type
ب) border-width
ج) border-style
د) border-color

✅ **پاسخ صحیح: ج) border-style**

---

### سوال 17

کدام مقدار برای `border-style` صحیح است؟

الف) solid
ب) center
ج) bold
د) inline

✅ **پاسخ صحیح: الف) solid**

---

### سوال 18

در Box Model، Margin در کدام قسمت قرار دارد؟

الف) داخلی‌ترین بخش
ب) بین Content و Padding
ج) خارج از Border
د) داخل Border

✅ **پاسخ صحیح: ج) خارج از Border**

---

### سوال 19

کدام گزینه درباره Padding صحیح است؟

الف) خارج از Border قرار دارد.
ب) بین Content و Border قرار دارد.
ج) فقط برای متن استفاده می‌شود.
د) رنگ پس‌زمینه را تعیین می‌کند.

✅ **پاسخ صحیح: ب) بین Content و Border قرار دارد.**

---

### سوال 20

کدام گزینه بهترین تعریف Box Model است؟

الف) مدلی برای مدیریت پایگاه داده
ب) مدلی برای نمایش ساختار جعبه‌ای عناصر HTML
ج) مدلی برای برنامه‌نویسی جاوااسکریپت
د) مدلی برای طراحی سرور

✅ **پاسخ صحیح: ب) مدلی برای نمایش ساختار جعبه‌ای عناصر HTML**

---

# سوالات دام‌دار آزمونی

### سوال 21

کدام بخش جزئی از Box Model نیست؟

الف) Content
ب) Padding
ج) Border
د) Selector

✅ **پاسخ صحیح: د) Selector**

---

### سوال 22

برای ایجاد فاصله بین دو عنصر HTML از کدام Property استفاده می‌شود؟

الف) padding
ب) border
ج) margin
د) width

✅ **پاسخ صحیح: ج) margin**

---

### سوال 23

برای افزایش فاصله متن از کادر اطرافش از کدام Property استفاده می‌شود؟

الف) margin
ب) padding
ج) border
د) width

✅ **پاسخ صحیح: ب) padding**

---

## برگه تقلب 20 ثانیه‌ای

### ترتیب Box Model

📦 **Content → Padding → Border → Margin**

---

### حفظی آزمونی

| بخش     | توضیح       |
| ------- | ----------- |
| Content | محتوای اصلی |
| Padding | فاصله داخلی |
| Border  | کادر        |
| Margin  | فاصله خارجی |

---

### نکات طلایی

✅ Padding = فاصله محتوا تا کادر
✅ Margin = فاصله عنصر تا عناصر دیگر
✅ Border = کادر دور عنصر
✅ Content = محتوای اصلی
✅ ترتیب: **Content → Padding → Border → Margin**

این ۵ نکته تقریباً ۷۰٪ سؤالات بخش Box Model را پوشش می‌دهند.
