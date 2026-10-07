# راه‌اندازی
فایل‌ها را در ریشه ریپو بگذارید. در Cloudflare Workers & Pages یک Worker از Git بسازید، Build command را خالی و Deploy command را `npx wrangler deploy` بگذارید. پس از انتشار، آدرس Worker را در `index.html` وارد کنید. این Worker دامنه را به IP تبدیل می‌کند، کشور IP را از GeoIP می‌گیرد و خروجی `🇺🇸 vless xhttp 443` می‌سازد. برای تست و مصرف سبک مناسب است؛ GeoIP عمومی محدودیت نرخ دارد.
