# ذاكرة جازان - نسخة الأعضاء والمراجعة

تحتوي هذه النسخة على:
- موقع عام لا يعرض إلا المحتوى المعتمد.
- دخول وتسجيل أعضاء.
- صفحة عضو لإرسال الوثائق والصور للمراجعة.
- لوحة إدارة لاعتماد أو رفض أو حذف الإضافات.
- خيار حظر العضو من الإضافة.
- قاعدة بيانات مجانية عبر Firebase Firestore.
- تخزين ملفات مجاني عبر Firebase Storage.

## خطوات التشغيل
1. فعّلي Firebase Authentication > Email/Password.
2. أضيفي بريد الإدارة وكلمة مرور.
3. فعّلي Firestore Database.
4. فعّلي Storage.
5. انسخي إعدادات Web App إلى firebase-config.js.
6. تأكدي أن بريدك موجود في adminEmails داخل firebase-config.js.
7. انسخي firestore.rules إلى Firestore Rules.
8. انسخي storage.rules إلى Storage Rules.
9. ارفعي الملفات إلى GitHub ثم Cloudflare.
