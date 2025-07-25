📦 BookBites AutoUploader

الملفات:
- main.py: السكربت الرئيسي لتوليد الفيديوهات ورفعها
- requirements.txt: تثبيت المكتبات المطلوبة
- config.json: ملف الإعدادات (أضف بيانات OpenAI وYouTube API)
- assets/: مجلد الصور والموسيقى (لصناعة الفيديوهات)

📌 خطوات الاستخدام:
1. ارفع هذه الملفات إلى مستودع GitHub
2. اربط المستودع بـ Render (نوع Web Service)
3. اجعل Start Command: python main.py
4. يتم توليد ورفع فيديو تلقائيًا كل ساعة

🔐 config.json يجب أن يحتوي على:
{
  "openai_api_key": "ضع مفتاح OpenAI هنا",
  "client_id": "من ملف Google OAuth",
  "client_secret": "من ملف Google OAuth"
}
