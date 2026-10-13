# REST API عالي الأداء مع التخزين المؤقت المتقدم
**High-Performance REST API with Advanced Caching** · التصنيف: خلفية (Backend)

> هذا المشروع خاص بشركة/عميل محدد، والكود المصدري غير منشور.
> Private client work — the source code is not public.

## نبذة عن المشروع
API كثيف القراءة يخدم أكثر من 50,000 طلب/دقيقة.

## أبرز النقاط
- تخزين مؤقت متعدد الطبقات: IMemoryCache + Redis + HTTP
- Nginx Load Balancing + SSL Termination
- مهام خلفية بـ Hangfire مع لوحة مراقبة

## الدور
مطوّر Backend: تصميم وبناء الخدمات الخلفية وواجهات API، وإدارة قواعد البيانات والتخزين المؤقت، وتنفيذ المصادقة والأمان وتحسين الأداء.

## التقنيات المستخدمة
ASP.NET Core, Dapper, Redis, PostgreSQL, Nginx, Docker, Hangfire

التفاصيل في [TECHSTACK.md](./TECHSTACK.md).
