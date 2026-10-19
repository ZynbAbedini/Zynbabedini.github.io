# زینب عابدینی | وب‌سایت شخصی و رزومه

این مخزن شامل فایل‌های وب‌سایت معرفی و رزومه آنلاین خانم **زینب عابدینی** است که آماده دیپلوی روی **GitHub Pages** می‌باشد.

## 🚀 راهنمای انتشار روی GitHub Pages (`github.io`)

شما می‌توانید این رزومه را به دو روش روی گیتهاب دیپلوی کنید:

### روش اول: به عنوان وب‌سایت اصلی پروفایل (`Zynbabedini.github.io`)
1. در اکانت گیت‌هاب خود یک ریپازیتوری جدید با نام دقیق زیر بسازید:
   `Zynbabedini.github.io`
2. در ترمینال در همین پوشه دستورات زیر را اجرا کنید:
   ```bash
   git add .
   git commit -m "Initial portfolio release"
   git remote add origin https://github.com/Zynbabedini/Zynbabedini.github.io.git
   git push -u origin main
   ```
3. پس از ۱ الی ۲ دقیقه، سایت شما مستقیماً در آدرس زیر در دسترس خواهد بود:
   👉 **`https://zynbabedini.github.io`**

---

### روش دوم: در ریپازیتوری فعلی یا پروژه‌ای (مثلاً `resume` یا `portfolio`)
1. یک ریپازیتوری مثلاً با نام `resume` در گیت‌هاب بسازید.
2. دستورات زیر را اجرا کنید:
   ```bash
   git add .
   git commit -m "Initial portfolio release"
   git remote add origin https://github.com/Zynbabedini/resume.git
   git push -u origin main
   ```
3. وارد تنظیمات ریپازیتوری در گیت‌هاب شوید:
   **Settings** > **Pages**
4. در بخش **Build and deployment**:
   - Source را روی **Deploy from a branch** بگذارید.
   - Branch را روی **main** و پوشه را روی `/ (root)` تنظیم کرده و روی **Save** کلیک کنید.
5. سایت در آدرس زیر منتشر خواهد شد:
   👉 **`https://zynbabedini.github.io/resume/`**

---

## 🛠 ساختار فایل‌ها
- `index.html`: سند ساختاری وب‌سایت با طراحی واکنش‌گرا و راست‌چین (RTL).
- `style.css`: استایل‌های مدرن با پالت رنگی منطبق بر رزومه.
- `profile.jpg`: تصویر پروفایل بهینه‌سازی‌شده برای وب.
