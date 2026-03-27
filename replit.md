# مركز سرعة انجاز - تيليجرام

## نظرة عامة
نظام إدارة تيليجرام متقدم يدعم 5 مستخدمين مسبقي التعريف مع ميزات المراقبة والإرسال التلقائي والانضمام التلقائي للمجموعات.

## البنية التقنية
- **Backend:** Python Flask + Flask-SocketIO
- **Telegram Library:** Telethon
- **Frontend:** HTML/CSS/JS (served by Flask via templates/)
- **Sessions:** ملفات `.session` في مجلد `sessions/`
- **Port:** 5000

## تشغيل التطبيق
```
python3 app.py
```

## الميزات الرئيسية
- ربط حسابات تيليجرام بطرق متعددة (كود OTP، باسورد 2FA)
- مراقبة الرسائل بكلمات مفتاحية
- إرسال تلقائي للمجموعات مع جدولة زمنية
- انضمام تلقائي للمجموعات من روابط دعوة
- دعم 5 مستخدمين مسبقي التعريف (user_1 إلى user_5)
- إشعارات فورية عبر Socket.IO

## المكتبات المثبتة
- flask
- flask-socketio
- telethon
- simple-websocket

## API Keys
- API_ID: 22043994 (مدمج في app.py)
- API_HASH: مدمج في app.py
