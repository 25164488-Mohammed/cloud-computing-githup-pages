# GitHub Pages — Cloud-Based Static Website Hosting and Deployment

منصة تعليمية عربية تفاعلية مصممة ومبرمجة بلغات الويب القياسية (**HTML5** و**CSS3** و**JavaScript**) دون أي مكتبات خارجية أو خوادم خلفية، لشرح خدمة **GitHub Pages** ضمن مقرر **الحوسبة السحابية (Cloud Computing)**.

---

## بنية المشروع

```text
github-pages-project/
├── index.html                 # المنصة التعليمية الرئيسية (11 قسماً + مخططات تفاعلية)
├── github_pages_motion.html   # فيلم الموشن جرافيك التفاعلي (8 مشاهد — 02:45)
└── README.md                  # دليل المشروع وخطوات النشر
```

---

## أبرز المميزات

- **لغة عربية فصحى واتجاه RTL حقيقي** مع عزل المصطلحات الإنجليزية والأكواد البرمجية باتجاهها الصحيح (`LTR`).
- **عمل كامل دون إنترنت ودون خادم محلي**: يمكن فتح `index.html` أو `github_pages_motion.html` مباشرة في أي متصفح حديث، كما يعمل المشروع مباشرة على **GitHub Pages**.
- **رسوم SVG أصلية وتفاعلات عملية**:
  - رسم متحرك في القسم الافتتاحي يوضح رحلة انتقال ملفات الموقع إلى الإنترنت.
  - مخطط تفاعلي لآلية العمل (`Developer → Repository → Build & Deployment → Published Website → Visitor`).
  - مخطط معماري تفاعلي يوضح المكونات الثمانية وتدفق البيانات مع إمكانية تصفية المراحل.
  - دليل تطبيقي من 9 خطوات مدعوم بواجهات تمثيلية توضيحية.
  - مقارنة منظمة بين **GitHub Pages** والاستضافة التقليدية.
  - تكامل مباشر عبر روابط داخلية بين الصفحة الرئيسية وفيلم الموشن جرافيك (`github_pages_motion.html`).

---

## تخصيص الهوية الأكاديمية (اختياري)

يعرض التذييل افتراضياً:
- `مشروع تطبيقي في مقرر الحوسبة السحابية`
- `إعداد الطالب: محمد البكير`

لإضافة اسم الدكتورة أو اسم الجامعة اختيارياً، افتح ملف `index.html` وعدّل كائن `ACADEMIC_CONFIG` في بداية وسم `<script>`:

```javascript
const ACADEMIC_CONFIG = {
  courseTitle: 'مشروع تطبيقي في مقرر الحوسبة السحابية',
  studentName: 'محمد البكير',
  instructorName: '', // اختياري: أضف اسم الدكتورة هنا
  universityName: ''  // اختياري: أضف اسم الجامعة هنا
};
```

---

## خطوات النشر على GitHub Pages

1. أنشئ مستودعاً عاماً (`Public Repository`) جديداً على حسابك في GitHub.
2. ارفع الملفات الثلاثة (`index.html`، `github_pages_motion.html`، `README.md`) مباشرة إلى المجلد الرئيسي للمستودع.
3. انتقل إلى **Settings** ← **Pages**.
4. من قسم **Build and deployment** اختر **Deploy from a branch**، ثم حدد الفرع الرئيسي (`main`) والمجلد الجذري (`/ root`) واضغط **Save**.
5. انتظر اكتمال عملية **Deployment**، ثم افتح رابط الموقع المنشور الذي يظهر في أعلى صفحة **Pages**.

---

## المصادر الرسمية

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Pages Official Site](https://pages.github.com/)
- [GitHub Repositories Documentation](https://docs.github.com/en/repositories)

---

**مشروع تطبيقي في مقرر الحوسبة السحابية**  
**إعداد الطالب: محمد البكير**
