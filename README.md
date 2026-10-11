# 📄 Premium LaTeX Resume Template (Persian & English)

A highly customizable, single-page, ATS-friendly LaTeX resume template tailored for professionals, executives, engineers, and tech specialists. This repository includes both **Persian (RTL)** and **English (LTR)** versions, featuring clean typography, optimal white-space management, and 8 premium color palettes.

<p align="center">
  <i>(برای خواندن راهنمای فارسی به پایین صفحه مراجعه کنید)</i>
</p>

## ✨ Features
- **Dual-Language Support:** Includes separate files for Persian (`main.tex`) and English (`resume-english.tex`).
- **Perfect Single-Page Layout:** Engineered with precise margins and spacing to ensure your content fits flawlessly on one page without awkward page breaks.
- **8 Premium Color Palettes:** Pre-configured with highly professional color themes (e.g., *Sage Green, Oxford Navy, Emerald Slate, Industrial Yellow*).
- **ATS-Friendly Structure:** Clean LaTeX code that remains readable by Applicant Tracking Systems.
- **Graphic Elements:** Minimalist custom bullet points, sidebar skill bars, and a dynamic profile picture clipping mask.

## 🛠 Prerequisites
To compile this template, you need:
1. A standard TeX distribution (e.g., [TeX Live](https://www.tug.org/texlive/), [MacTeX](https://www.tug.org/mactex/), or [MiKTeX](https://miktex.org/)).
2. **XeLaTeX Engine:** The Persian template relies on `xepersian` and must be compiled using `xelatex`. (The English version can also be compiled with XeLaTeX).
3. **Vazirmatn Font:** The Persian layout uses the beautiful [Vazirmatn](https://github.com/rastikerdar/vazirmatn) font. Please install it on your OS before compiling.

## 🚀 How to Use
1. Download or clone this repository: `git clone https://github.com/MahdiJahangiry/Premium-Persian-CV.git`
2. Place your profile picture in the root folder and name it `photo.jpg`.
3. Open `main.tex` (for Persian) or `resume-english.tex` (for English) in your favorite LaTeX editor (e.g., TeXstudio, VS Code, Overleaf).
4. **Important:** Compile the document **twice** using `XeLaTeX`. The first compile builds the layout, and the second compile perfectly aligns the sidebar background color.
5. **Change Color Palette:** To change the color theme, simply uncomment your preferred palette in the `Custom Color Palettes` section of the `.tex` file by removing the `%` symbol.

---

<div dir="rtl">

# 📄 قالب حرفه‌ای رزومه LaTeX (فارسی و انگلیسی)

یک قالب رزومه مینیمال، یک‌صفحه‌ای و دوستونه که به طور ویژه برای متخصصان، مهندسان و مدیران طراحی شده است. این مخزن (Repository) شامل هر دو نسخه **فارسی (راست‌چین)** و **انگلیسی (چپ‌چین)** است و دارای ۸ پالت رنگی روان‌شناسانه و شرکتی می‌باشد.

## ✨ ویژگی‌های کلیدی
- **پشتیبانی از دو زبان:** فایل `main.tex` برای ساخت رزومه فارسی و فایل `resume-english.tex` برای ساخت رزومه بین‌المللی.
- **طراحی مهندسی‌شده برای یک صفحه:** فاصله‌ها و حاشیه‌ها با دقت میلی‌متری تنظیم شده‌اند تا از ایجاد صفحات خالی و به‌هم‌ریختگی جلوگیری شود.
- **۸ پالت رنگی مدیریتی:** شامل رنگ‌های تخصصی و خاص (مثل سبز سِیج، سرمه‌ای آکسفورد، دودی پلاتینیوم) که تنها با تغییر یک خط کد فعال می‌شوند.
- **ساختار سازگار با ATS:** کدهای استاندارد که به راحتی توسط سیستم‌های بررسی خودکار رزومه خوانده می‌شوند.
- **سایدبار گرافیکی:** شامل نوارهای پیشرفت برای مهارت‌های تخصصی، امتیازدهی مهارت‌های نرم و ماسک دایره‌ای اتوماتیک برای عکس پروفایل.

## 🛠 پیش‌نیازها
برای استفاده از این قالب به موارد زیر نیاز دارید:
۱. نصب بودن توزیع‌های تک (مانند TeX Live یا MacTeX).
۲. استفاده از موتور پردازشی **XeLaTeX** (الزامی به دلیل استفاده از پکیج زی‌پرشین در نسخه فارسی).
۳. نصب فونت [وزیرمتن](https://github.com/rastikerdar/vazirmatn) روی سیستم‌عامل شما.

## 🚀 راهنمای استفاده
۱. این ریپازیتوری را دانلود یا کلون کنید.
۲. عکس پرسنلی خود را با نام `photo.jpg` در کنار فایل‌های اصلی قرار دهید.
۳. فایل `main.tex` (برای رزومه فارسی) یا `resume-english.tex` (برای رزومه انگلیسی) را در ادیتور خود باز کنید.
۴. **نکته بسیار مهم:** برای اینکه رنگ پس‌زمینه ستون کناری دقیقاً در جای خود قرار بگیرد، دکمه کامپایل (XeLaTeX) را **دوبار پشت سر هم** بزنید.
۵. **تغییر تم رنگی:** برای تغییر رنگ رزومه، در کدهای فایل، علامت `%` را از پشت پالت رنگی دلخواه خود بردارید و پالت قبلی را کامنت کنید.

### 🤝 مشارکت (Contributing)
اگر ایده یا کدی برای بهبود این قالب دارید، Pull Request های شما باعث افتخار است. 
</div>