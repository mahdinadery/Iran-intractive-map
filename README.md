https://mahdinadery.github.io/Iran-intractive-map/


# 🗺️ نقشه تعاملی استان‌های ایران | Interactive Map of Iran Provinces

[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-7-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub_Pages-blue?logo=github)](https://mahdinadery.github.io/iran-map/)

وب‌اپلیکیشن تعاملی، مستقل و بدون نیاز به بک‌اند برای **بصری‌سازی داده‌های استانی ایران (۳۱ استان)** بر روی نقشه و نمودار مقایسه‌ای از طریق آپلود فایل‌های اکسل (`.xlsx`, `.xls`, `.csv`).

A lightweight, fully client-side web application for **visualizing provincial data across Iran’s 31 provinces** on an interactive choropleth map and companion comparison bar chart via Excel/CSV file upload.

---

## ✨ ویژگی‌های کلیدی | Key Features

### 🗺️ نقشه تعاملی ۳۱ استان ایران
- نمایش برداری و باکیفیت تمامی **۳۱ استان ایران** به همراه پهنه‌های آبی (**دریای خزر** و **خلیج فارس**).
- برچسب‌گذاری دقیق کارتوگرافیک: چرخش خودکار برچسب‌ها در راستای امتداد استان‌های کشیده (مانند آذربایجان شرقی و غربی) برای جلوگیری از هم‌پوشانی.
- هایلایت و نمایش مشخصات (Tooltip) با هاور روی هر استان.
- حاشیه هوشمند سفید دور فونت برای خوانایی برچسب‌ها روی رنگ‌های پررنگ.

### 📊 نمودار مقایسه‌ای همگام (Horizontal Bar Chart)
- نمودار میله‌ای افقی مرتب‌شده از بیشترین به کمترین مقدار در کنار نقشه.
- قابلیت تغییر اندازه (حالت فشرده بدون نیاز به اسکرول / حالت بزرگ‌نمایی).
- دکمه پنهان/نمایش نمودار برای اختصاص تمام فضا به نقشه.
- هماهنگی ۱۰۰٪ جهت میله‌ها و رنگ با طیف انتخابی.

### 📂 پردازش و تطبیق هوشمند اکسل
- پشتیبانی از فرمت‌های `.xlsx`، `.xls` و `.csv`.
- **تشخیص خودکار ستون‌ها**: ستون «نام استان» و ستون «مقدار عددی».
- تطبیق هوشمند نام استان‌ها (فارسی، انگلیسی، با و بدون پیشوند «استان»، حروف عربی/فارسی `ی/ي` و `ک/ك`).
- **کلید میانبر کپی سریع**: کپی کل جدول ۳۱ استان با یک کلیک و چسباندن مستقیم (`Ctrl+V`) در اکسل.
- **پردازش ۱۰۰٪ محلی در مرورگر**: هیچ داده‌ای به هیچ سروری ارسال نمی‌شود (امنیت کامل داده‌های محرمانه).

### 🎨 سیستم رنگ‌بندی پیشرفته (Color Scale)
- **۸ پالت رنگی آماده** (آبی، سبز، قرمز، نارنجی، بنفش، فیروزه‌ای، صورتی، خاکستری).
- **انتخاب‌گر رنگ دلخواه (Color Picker)**: انتخاب هر رنگ دلخواه و ساخت خودکار طیف کم‌رنگ تا پررنگ.
- پیش‌نمایش زنده طیف ساخته‌شده.
- **راهنمای رنگ (لجند) گسسته ۵ پله‌ای**: نمایش نام متغیر و بازه عددی هر قطعه رنگی با جهت صحیح.

### 🔤 فونت دلخواه کاربر
- امکان آپلود فونت دلخواه (`TTF`, `OTF`, `WOFF`, `WOFF2`).
- اعمال فونت روی نقشه، برچسب استان‌ها، نمودار و تمام بخش‌های برنامه.
- جاسازی خودکار فونت آپلودشده در خروجی‌های تصویری و فایل مستقل HTML.

### 🌐 دوزبانه کامل (Bilingual)
- پشتیبانی کامل از دو زبان **فارسی (RTL)** و **انگلیسی (LTR)** با یک کلیک.
- ترجمه تمامی رابط کاربری، نام استان‌ها، نمودار و ارقام (اعداد فارسی / لاتین).

### 💾 مرکز خروجی و دانلود
- **تصویر باکیفیت (PNG شفاف)**: خروجی با رزولوشن ۴ برابری (`pixelRatio: 4`) و پس‌زمینه کاملاً شفاف، مناسب برای مقالات، پایان‌نامه‌ها، اسلایدها و گزارش‌ها.
- **نسخه مستقل HTML**: دانلود کل برنامه در قالب یک فایل تک‌فایلی (`.html`) که تمام کدها، استایل‌ها، داده‌ها و فونت را در خود دارد و بدون اینترنت با دابل‌کلیک در هر مرورگری اجرا می‌شود.

---

## 🚀 راهنمای راه‌اندازی محلی | Getting Started

### پیش‌نیازها
- [Node.js](https://nodejs.org/) (نسخه ۱۸ یا بالاتر)
- مدیریت بسته `npm` یا `pnpm` یا `yarn`

### نصب و اجرا

```bash
# ۱. کلون کردن مخزن
git clone https://github.com/mahdinadery/iran-map.git
cd iran-map

# ۲. نصب وابستگی‌ها
npm install

# ۳. اجرای سرور توسعه
npm run dev

# ۴. ساخت نسخه نهایی تک‌فایلی (Single-File Production Build)
npm run build
