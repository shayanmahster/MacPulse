# MacPulse 1.4.0

## English

Liquid Glass redesign plus readability and accuracy improvements.

### Highlights

- **Liquid Glass (macOS 26 Tahoe)** — native `glassEffect` with interactive tint, mesh orbs, and specular highlights across dashboard and menu bar panel
- **Glass Intensity slider** in Settings — adjust card translucency (0.25–1.0) live, stored in UserDefaults
- **Battery Health card** — cycle count, `AppleRawMaxCapacity / DesignCapacity` and `system_profiler` `Maximum Capacity` (matches System Settings), mAh display and Excellent/Good/Service condition
- **Network session totals** — total downloaded / uploaded / combined traffic since boot with one-click copy to clipboard and toast
- Improved readability for dark/light cards (more opaque `0.18/0.62` tint, reduced highlight, stronger shadows)
- Fixed menu bar panel empty cards (removed `GlassEffectContainer` that hid `memoryBar`/`quickStats`/`processList`)
- Fixed battery health showing 2% (was `MaxCapacity 100 / 4563`) — now uses `AppleRawMaxCapacity 3851` and authoritative 89% from `system_profiler`
- Universal Binary for Apple Silicon and Intel, macOS 14+

### Installation

Download `MacPulse-1.4.0.dmg`, drag MacPulse into Applications, and launch it. Locally signed (ad-hoc), not Apple-notarized — use Finder **right-click → Open** on first launch. Do not disable Gatekeeper.

## فارسی

بازطراحی Liquid Glass به همراه بهبود خوانایی و دقت

### تغییرات مهم

- **Liquid Glass (استایل macOS 26 Tahoe)** — افکت شیشهٔ بومی `glassEffect` با تینت تعاملی، حباب‌های مش و هایلایت در داشبورد و منوبار
- **اسلایدر شفافیت شیشه** در تنظیمات — تنظیم ماتی کارت‌ها به صورت زنده (۰.۲۵ تا ۱.۰) و ذخیره در UserDefaults
- **کارت سلامت باتری** — تعداد چرخه، ظرفیت `AppleRawMaxCapacity / DesignCapacity` و درصد سلامت از `system_profiler` (هماهنگ با تنظیمات سیستم)، نمایش mAh و وضعیت عالی/خوب/نیاز به بررسی
- **مجموع ترافیک شبکه** — کل دانلود/آپلود/ترافیک از زمان بوت با کپی یک‌کلیکی و توست
- بهبود خوانایی کارت‌ها در تم روشن/تیره (شیشه مات‌تر ۰.۱۸/۰.۶۲، هایلایت کمتر، سایه قوی‌تر)
- رفع خالی بودن کارت‌های منوبار (حذف `GlassEffectContainer` که محتوا را پنهان می‌کرد)
- رفع نمایش اشتباه سلامت باتری ۲٪ (محاسبهٔ اشتباه `100/4563`) — الان ۸۹٪ درست با `AppleRawMaxCapacity` و `system_profiler`
- نسخه Universal برای Apple Silicon و Intel، حداقل macOS 14

### نصب

فایل `MacPulse-1.4.0.dmg` را دانلود کنید، MacPulse را داخل Applications بکشید و اجرا کنید. امضای محلی (ad-hoc) دارد و Notarize نشده — در اولین اجرا Finder **راست‌کلیک → Open** بزنید. Gatekeeper را خاموش نکنید.

## SHA-256

```text
bb982b77bed073ee646c1809e4a24ba4f57f1da2236c2bf9726ff51c544a76a2  MacPulse-1.4.0.dmg
```

created by **shayanmaher**

---

# MacPulse 1.3.0

## English

This update adds live network monitoring and a new battery and energy dashboard to MacPulse.

### Highlights

- Live download/upload rates and per-process network usage
- Battery charge, charging state, power source, and estimated remaining time
- Ranked per-app Energy Impact based on CPU, memory, and network activity
- CPU, network, and battery quick stats in the compact menu bar panel
- Live CPU, memory, and storage statistics
- English and Persian interface
- Light, Dark, and System appearance
- Safe Quit and Force Quit controls
- Multi-application memory optimizer
- `Command-Q` keeps menu bar monitoring active
- Clear Quit button and `Option-Command-Q` for complete exit
- Universal Binary for Apple Silicon and Intel Macs
- Local-only processing with no telemetry

### Installation

Download the DMG, drag MacPulse into Applications, and launch it. This binary is locally signed but not yet Apple-notarized. If macOS asks for confirmation on first launch, use Finder's standard **right-click → Open** flow. Do not disable Gatekeeper.

## فارسی

این به‌روزرسانی پایش زندهٔ شبکه و داشبورد جدید باتری و انرژی را به مک‌پالس اضافه می‌کند.

### تغییرات مهم

- سرعت زندهٔ دانلود و آپلود و مصرف شبکه به تفکیک فرایند
- درصد شارژ، وضعیت شارژ، منبع تغذیه و زمان تقریبی باقی‌مانده
- رتبه‌بندی Energy Impact برنامه‌ها بر پایهٔ پردازنده، حافظه و شبکه
- آمار سریع CPU، شبکه و باتری در پنل کوچک نوار منو
- آمار زندهٔ پردازنده، حافظه و فضای ذخیره‌سازی
- رابط فارسی و انگلیسی
- تم روشن، تیره و هماهنگ با سیستم
- بستن امن و خروج اجباری برنامه‌ها
- بهینه‌سازی حافظه با انتخاب چند برنامه
- فعال‌ماندن پایش نوار منو پس از `Command-Q`
- دکمهٔ واضح خروج کامل و میان‌بر `Option-Command-Q`
- نسخهٔ Universal برای Apple Silicon و Intel
- پردازش کاملاً محلی و بدون تله‌متری

### نصب

فایل DMG را دانلود کنید، MacPulse را داخل Applications بکشید و اجرا کنید. این نسخه امضای محلی دارد اما هنوز توسط اپل Notarize نشده است. اگر macOS در اجرای اول تأیید خواست، از مسیر استاندارد Finder یعنی **راست‌کلیک → Open** استفاده کنید. Gatekeeper را خاموش نکنید.

## SHA-256

```text
c1b6a87e1f3360809944c89a2b4b4d21429ca291ba98784b623ee18d9ee11d62  MacPulse-1.3.0.dmg
```

created by **shayanmaher**
