# 🎥 ClickPlay — Twitter/X Video Campaign Links

## 🚀 الفكرة
حوّل أي فيديو على تويتر/X إلى رابط قابل للنقر يقود إلى صفحة خارجية مع تتبع المشاهدات والنقرات.  
يدعم واجهة عربية RTL، تصميم داكن (#09090B) مع لمسة صفراء (#FACC15).

---

## 📂 هيكل المشروع
app/
├── backend/                  ← الكود الخاص بالخادم (FastAPI + MongoDB)
│   ├── server.py             ← منطق الـ API
│   ├── requirements.txt      ← مكتبات Python
│   └── .env                  ← إعدادات البيئة
│
├── frontend/                 ← واجهة المستخدم (React + Tailwind)
│   ├── package.json          ← مكتبات React
│   ├── .env                  ← إعدادات البيئة
│   ├── tailwind.config.js    ← إعدادات Tailwind
│   └── src/
│       ├── App.js            ← نقطة البداية
│       ├── App.css           ← تنسيقات عامة
│       ├── index.css         ← تنسيقات أساسية
│       ├── lib/api.js        ← axios client
│       └── pages/Dashboard.jsx ← واجهة اللوحة الرئيسية
│
└── memory/                   ← ملفات التوثيق
    └── PRD.md                ← توثيق المشروع
