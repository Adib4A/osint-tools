# 🕵️ راهنمای OSINT

## مقدمه

اوسینت شامل جمع‌آوری و تحلیل اطلاعاتی است که به صورت عمومی در دسترس هستند. حوزه‌های اصلی شامل موارد زیر است:

- **مقدمه**: اصول اولیه OSINT به عنوان روشی برای جمع‌آوری قانونی اطلاعات.
- **جمع‌آوری اطلاعات**: استخراج داده‌ها از منابع عمومی.
- **Mitre ATT&CK**: چارچوبی برای درک تاکتیک‌ها و تکنیک‌های حملات سایبری. [لینک](https://attack.mitre.org/)
- **OSINT**: تکنیک‌های اوسینت.
- **نشت داده‌ها**: شناسایی داده‌های نشت شده مانند ایمیل و رمز عبور.
- **تصاویر**: تحلیل متادیتا (مانند GPS، تاریخ/زمان) در تصاویر.
- **موتور جستجو**: استفاده از ابزارهای جستجوی پیشرفته.
- **وب عمیق و دارک وب**: دسترسی به لایه‌های پنهان اینترنت.
- **حریم خصوصی**: حفاظت از داده‌های شخصی در هنگام استفاده از OSINT.
- **ایمیل و نام کاربری**: بررسی هویت کاربران.
- **دیتابیس‌های نشت داده**: بررسی پایگاه‌های داده نشت کرده.
- **تست OSINT**: کاربرد عملی روش‌های OSINT.

رشته‌های دیگر اطلاعاتی شامل MASINT، GEOINT، HUMINT، FININT، CYBINT، TECHINT، SIGINT و OSINT هستند.


## چارچوب‌ها و مدل‌ها

- **چارچوب OSINT SANS 497**: دوره آموزشی چارچوب‌های OSINT. [لینک](https://www.sans.org/cyber-security-courses/open-source-intelligence-gathering/)
- **داده‌های بزرگ (Big Data)**: استفاده از مجموعه داده‌های بزرگ برای تحلیل.
- **شبکه‌های اجتماعی**: منبع اصلی داده‌های شخصی و اجتماعی.
- **Cyber Kill Chain**: مدلی برای توصیف مراحل حملات سایبری.


## ابزارهای عمومی جمع‌آوری اطلاعات

- **SpiderFoot**: ابزار اتوماتیک اسکن OSINT. [لینک](https://github.com/smicallef/spiderfoot)
- **Maltego**: ابزار گرافیکی برای ترسیم روابط. [لینک](https://www.maltego.com/)
- **osint.ir**: منبع فارسی OSINT. [لینک](https://osint.ir/)
- **theHarvester**: ابزار جمع‌آوری ایمیل و زیر دامنه‌ها. [لینک](https://github.com/laramies/theHarvester)


## تحلیل تصاویر و رسانه

- **Exif Data**: متادیتای تصاویر شامل GPS، تاریخ/زمان و حق نشر.
- **Document Inspect**: تحلیل متادیتا در اسناد آفیس.
- **ابزارها**:
  - **ExifTool**: ویرایشگر متادیتا در خط فرمان. [لینک](https://exiftool.org/)
  - **Pic2Map**: مشاهده آنلاین موقعیت EXIF. [لینک](https://www.pic2map.com/)
  - **WhereIsThePicture**: [لینک](https://whereisthepicture.com/) شناسایی موقعیت تصاویر
  - **Google Images**: جستجوی معکوس تصاویر. [لینک](https://images.google.com/)
  - **Yandex Images**: جستجوی معکوس پیشرفته. [لینک](https://yandex.com/images/)
  - **Bing Images**: جستجوی معکوس تصاویر. [لینک](https://www.bing.com/images/)
  - **TinEye**: موتور جستجوی معکوس تصاویر. [لینک](https://tineye.com/)


## نقشه‌برداری و ردیابی

- **Wikimapia**: نقشه‌های تعاملی کاربران. [لینک](https://wikimapia.org/)
- **Liveuamap**: نقشه‌های جهانی رویدادها به صورت زنده. [لینک](https://liveuamap.com/)
- **Flightradar24**: ردیابی پروازها. [لینک](https://www.flightradar24.com/)
- **RadarBox**: ردیابی هواپیماها. [لینک](https://www.radarbox.com/)
- **VesselFinder**: ردیابی کشتی‌ها. [لینک](https://www.vesselfinder.com/)
- **IPLocation.net**: موقعیت جغرافیایی IP. [لینک](https://iplocation.net/)


## موتورهای جستجو و دُرک‌ها (Dorks)

- **موتورهای جستجوی متا**:
- **DuckDuckGo**: جستجوی حفظ حریم خصوصی. [لینک](https://duckduckgo.com/)
- **Google**: جستجوی پیشرفته. [لینک](https://www.google.com/)
- **Google Dorks**: اپراتورهایی مانند `site:`, `intitle:`, `filetype:`, `inurl:`, `AND`, `OR`, `NOT`, `~`. مثال: `site:.ir intitle:"index of admin"`
- **Shodan**: موتور جستجوی دستگاه‌های IoT. [لینک](https://www.shodan.io/)
- **Censys**: جستجوی دستگاه. [لینک](https://censys.io/)
- **ZoomEye**: موتور جستجوی سایبری. [لینک](https://www.zoomeye.org/)
- **Biznar**: جستجوی تجاری. [لینک](https://biznar.com/)


## وب عمیق و دارک وب

- **لایه‌های وب**: Surface Web، Deep Web، Dark Web.
- **Torch**: جستجوی سایت‌های .onion
- **Ahmia**: جستجوی امن دارک وب. [لینک](https://ahmia.fi/)
- **Tor**: شبکه ناشناس برای دسترسی به دارک وب. [لینک](https://www.torproject.org/)
- **Proxifier**: ابزار پراکسی. [لینک](https://www.proxifier.com/)
- **Kodachi**: توزیع لینوکس برای ناشناس ماندن. [لینک](https://sourceforge.net/projects/linuxkodachi/)
- **Tails**: سیستم عامل ناشناس از طریق USB. [لینک](https://tails.net/)
- **ProxyChains**: زنجیره‌سازی پراکسی. [لینک](https://github.com/haad/proxychains)
- **Gather Proxy**: [لینک](https://gather-proxy.com/).جمع‌آوری لیست پراکسی
- **Hidden Wiki**: دایرکتوری سایت‌های دارک وب. [لینک (.onion)](https://thehiddenwiki.org/)


## تولیدکننده‌ها و چکرها

- **Fake Name Generator**: تولید نام جعلی. [لینک](https://www.fakenamegenerator.com/)
- **Fake Person Generator**: [لینک](https://www.fakepersongenerator.com/) ایجاد پروفایل جعلی.
- **Username Generator**: ابزارهایی مانند BestRandom. [لینک](https://bestrandoms.com/random-username-generator)


## ابزارهای ایمیل و نام کاربری

- **Hotmail/Outlook**: سرویس ایمیل. [لینک](https://outlook.live.com/)
- **Emailable**: تایید ایمیل. [لینک](https://emailable.com/)
- **Email-Checker.net**: بررسی ایمیل. [لینک](https://email-checker.net/)
- **Hunter.io**: جستجوی ایمیل. [لینک](https://hunter.io/)
- **InfoTracer**: جستجوی داده‌های شخصی. [لینک](https://infotracer.com/)
- **Gravatar**: تصاویر پروفایل. [لینک](https://en.gravatar.com/)
- **Skymem**: جستجوی ایمیل. [لینک](https://skymem.info/)
- **InstantUsername**: بررسی نام کاربری. [لینک](https://instantusername.com/)
- **NameChk**: بررسی نام کاربری. [لینک](https://namechk.com/)
- **EmailRep.io**: بررسی اعتبار ایمیل. [لینک](https://emailrep.io/)


## ابزارهای نشت داده

- **DeHashed**: جستجوی داده‌های نشت کرده. [لینک](https://dehashed.com/)
- **HaveIBeenPwned**: بررسی نشت ایمیل. [لینک](https://haveibeenpwned.com/)
- **Spokeo**: جستجوی افراد. [لینک](https://www.spokeo.com/)
- **IntelX**: جستجوی پیشرفته. [لینک](https://intelx.io/)
- **Pastebin**: جستجوی متن‌های نشت شده. [لینک](https://pastebin.com/)
- **SpyCloud**: تحلیل نشت داده‌ها. [لینک](https://spycloud.com/)


## ابزارهای شبکه و سطح حمله

- **ViewDNS**: ابزارهای DNS. [لینک](https://viewdns.info/)
- **Pentest-Tools**: ابزارهای تست نفوذ. [لینک](https://pentest-tools.com/)
- **Bettercap**: MITM و DNS poisoning. [لینک](https://www.bettercap.org/)
- **Wayback Machine**: آرشیو وب. [لینک](https://archive.org/web/)


## سرویس‌های API

- **AbuseIPDB**: گزارش IP مخرب. [لینک](https://www.abuseipdb.com/)
- **Etherscan**: اکسپلورر بلاکچین. [لینک](https://etherscan.io/)
- **FullHunt**: جستجوی سطح حمله. [لینک](https://fullhunt.io/)
- **Viz.GreyNoise**: تحلیل نویز IP. [لینک](https://viz.greynoise.io/)
- **Hybrid-Analysis**: تحلیل بدافزار. [لینک](https://hybrid-analysis.com/)
- **IKnowWhatYouDownload**: ردیابی دانلود. [لینک](https://iknowwhatyoudownload.com/)
- **IPAPI**: اطلاعات IP. [لینک](https://ipapi.com/)
- **Host.io**: داده‌های دامنه. [لینک](https://host.io/)
- **Leak-Lookup**: جستجوی نشت داده‌ها. [لینک](https://leak-lookup.com/)
- **Maltiverse**: اطلاعات تهدیدات. [لینک](https://maltiverse.com/)
- **NetworksDB**: پایگاه داده شبکه. [لینک](https://networksdb.io/)
- **Pulsedive**: تحلیل IOC. [لینک](https://pulsedive.com/)
- **URLScan**: اسکن URL. [لینک](https://urlscan.io/)
- **WhatCMS**: شناسایی CMS. [لینک](https://whatcms.org/)

