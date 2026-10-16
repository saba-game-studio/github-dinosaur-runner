<div align="center">

<img src="docs/icon.png" width="128" alt="آیکن دایناسور دونده">

# دایناسور دونده | Viro Dino Runner

**یک بازی دوندگی سه‌بعدی، رنگی و آفلاین با ویرو، شخصیت بنفش و بامزه‌ی Viro Games**

![نسخه](https://img.shields.io/badge/version-0.2.1-8b5cf6)
![پلتفرم](https://img.shields.io/badge/platform-Windows%20%7C%20Android%20%7C%20Web-ee6c48)
![three.js](https://img.shields.io/badge/three.js-3D-black)
![آفلاین](https://img.shields.io/badge/offline-100%25-3fc59a)

<img src="docs/banner.jpg" alt="صفحه‌ی اصلی بازی" width="100%">

</div>

<div dir="rtl">

## درباره‌ی بازی

ویرو، موجود بنفش کوچولو با آنتن فنری و چراغ زردش، راه افتاده تا از بیابان داغ تا جنگل سبز، دشت برفی و پاییز طلایی بدود. سر راهش سنگ و کنده و کاکتوس هست، مارها کمین کرده‌اند و زنبورها از بالا حمله می‌کنند. بپر، خم شو، مسیر عوض کن و تا می‌تونی سکه جمع کن.

بازی کاملاً آفلاین است، تبلیغ ندارد، ثبت‌نام نمی‌خواهد و برای همه‌ی سنین مناسب است.

## ویژگی‌ها

- 🟣 **ویروی سه‌بعدی** با انیمیشن دویدن، پریدن، پلک‌زدن و آنتنی که تکان می‌خورد
- 🌍 **چهار سرزمین**: بیابان، جنگل، برفی و پاییز که در طول بازی عوض می‌شوند
- 🌙 **شب و روز** با آسمان، ابر، مه، نور و سایه‌ی نرم
- 🐝 **موانع متنوع**: سنگ، کنده، کاکتوس، مار و زنبور پرنده
- 🧲 **قدرت‌ها**: آهن‌ربای سکه و سپر محافظ
- 👕 **کمد ویرو**: ۵ لباس (دایناسوری، کلاه‌قرمزی، پادشاه، فضانورد) و ۶ رنگ که با سکه باز می‌شوند
- 🎯 **چالش روزانه** با جایزه‌ی سکه
- ❤️ **ادامه‌ی بازی** بعد از برخورد با سکه
- ⚙️ تنظیم صدا، لرزش و کیفیت گرافیک برای گوشی‌های ضعیف‌تر
- 🔤 رابط کاملاً فارسی و راست‌به‌چپ با فونت وزیرمتن

## تصاویر

<table>
<tr>
<td><img src="docs/screenshots/desert.jpg" alt="بیابان"></td>
<td><img src="docs/screenshots/forest.jpg" alt="جنگل"></td>
</tr>
<tr>
<td align="center">بیابان</td>
<td align="center">جنگل</td>
</tr>
<tr>
<td><img src="docs/screenshots/snow.jpg" alt="شب برفی"></td>
<td><img src="docs/screenshots/autumn.jpg" alt="پاییز"></td>
</tr>
<tr>
<td align="center">شب برفی</td>
<td align="center">پاییز</td>
</tr>
<tr>
<td><img src="docs/screenshots/wasp.jpg" alt="حمله‌ی زنبورها"></td>
<td><img src="docs/screenshots/over.jpg" alt="پایان بازی"></td>
</tr>
<tr>
<td align="center">حمله‌ی زنبورها، وقت خم شدن!</td>
<td align="center">پایان بازی و رکورد جدید</td>
</tr>
</table>

<p align="center">
<img src="docs/screenshots/mobile-home.jpg" width="280" alt="صفحه‌ی اصلی موبایل">
&nbsp;&nbsp;
<img src="docs/screenshots/viro-closet.jpg" width="280" alt="کمد ویرو">
</p>

<p align="center"><img src="docs/screenshots/outfits.png" alt="لباس‌های ویرو"></p>
<p align="center">ویرو، ویرو دایناسوری، ویرو کلاه‌قرمزی، ویرو پادشاه، ویرو فضانورد</p>

## کنترل‌ها

| کار | کیبورد | لمسی |
|---|---|---|
| تغییر مسیر | ← → یا A D | کشیدن به چپ و راست |
| پرش | ↑ یا W یا Space | کشیدن به بالا یا ضربه |
| خم شدن | ↓ یا S | کشیدن به پایین |
| توقف | P یا Esc | دکمه‌ی توقف |

## دانلود

- **ویندوز:** نسخه‌ی نصبی (`setup.exe`) یا قابل‌حمل (`portable.exe`) از بخش [Releases](../../releases)
- **اندروید:** به‌زودی در کافه‌بازار و مایکت

> اگر ویندوز هشدار SmartScreen داد، روی More info و بعد Run anyway بزنید.

## ساخت از سورس

```bash
npm install
npm run dev            # اجرا در مرورگر
npx vite build         # ساخت نسخه‌ی وب در dist/
npx tauri build        # بسته‌ی دسکتاپ با Tauri 2
```

## فناوری‌ها

Vite · JavaScript · three.js · Tauri 2 · WebAudio · localStorage

## اعتبار منابع

- مدل‌های سه‌بعدی محیط و موانع: [Quaternius](https://quaternius.com) (CC0)
- فونت: [Vazirmatn](https://github.com/rastikerdar/vazirmatn) (OFL)
- موتور سه‌بعدی: [three.js](https://threejs.org) (MIT)

جزئیات در [CREDITS.md](CREDITS.md).

---

<p align="center">ساخته‌شده با 💜 توسط <b>Viro Games</b></p>

</div>

---

## English

**Viro Dino Runner** is a colorful, fully offline 3D endless runner starring Viro, the purple mascot of Viro Games. Run through desert, forest, snowy and autumn lands with a day/night cycle, dodge rocks, cactuses, snakes and flying wasps, grab coins, magnets and shields, and unlock 5 outfits and 6 colors in Viro's Closet. No ads, no sign-up, Persian RTL interface.

Built with Vite, vanilla JavaScript, three.js and Tauri 2. 3D scenery by Quaternius (CC0).
