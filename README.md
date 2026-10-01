# دستیار شخصی OpenAI

## راه‌اندازی

1. کلید API خودت رو در فایل `server.js` جایگزین کن:
   ```
   const OPENAI_API_KEY = "sk-...";
   ```
   یا از متغیر محیطی استفاده کن:
   ```
   export OPENAI_API_KEY=sk-...
   ```

2. سرور رو روشن کن:
   ```
   npm start
   ```
   یا
   ```
   node server.js
   ```

3. برو به آدرس:
   http://localhost:3000

## نکات
- کلید API فقط روی سرور می‌مونه و امنه.
- مدل پیش‌فرض: gpt-4o-mini (ارزان و سریع)
- برای تغییر مدل، تو server.js خط model رو عوض کن.
