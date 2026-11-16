# مهارات Ashen Arena

مستودع مستقل لقواعد مشروع Ashen Arena وملف سياقه. لا يحتوي على مفاتيح أو أسرار، وليس نسخة من كود اللعبة.

## المحتويات

| الملف | الاستخدام |
|---|---|
| `skills/ashen-arena-user-rules/SKILL.md` | المهارة الدائمة: قواعد التجربة، الضربة، الصوت، الصدارة، والأمان |
| `dist/ashen-arena-user-rules.skill` | حزمة جاهزة لإضافتها من **My Skills** في Manus |
| `ASHEN-ARENA-HANDOFF.md` | سياق المشروع الكامل وقراراته وخطة العمل القادمة |
| `PROMPT.md` | أول رسالة جاهزة للحساب الثاني |

## الاستيراد في حساب Manus آخر

**الطريقة الأسهل:** نزّل `dist/ashen-arena-user-rules.skill` وأضفه من **My Skills**. إن لم يظهر خيار الاستيراد، استخدم محتوى `SKILL.md` في تعليمات المشروع.

**من GitHub مباشرة:** إذا كان الحساب يدعم استيراد مهارة من رابط، استخدم رابط المستودع:

https://github.com/aa9986087-cyber/ashen-arena-skills

أو رابط الملف الخام:

https://raw.githubusercontent.com/aa9986087-cyber/ashen-arena-skills/main/skills/ashen-arena-user-rules/SKILL.md

**ملف السياق:** ارفع `ASHEN-ARENA-HANDOFF.md` كملف `.md` في أول مهمة، ثم ألصق محتوى `PROMPT.md`.

## الاستيراد اليدوي السريع

1. افتح الحساب الثاني وأنشئ مهمة أو مشروعًا جديدًا.
2. أضف المهارة من My Skills، أو ارفع `SKILL.md` واطلب قراءته.
3. ارفع `ASHEN-ARENA-HANDOFF.md`.
4. اربط GitHub من جديد؛ صلاحيات الحساب الأول لا تنتقل.
5. أرسل أول رسالة من `PROMPT.md`.

## تحديث المهارة

عدّل `skills/ashen-arena-user-rules/SKILL.md`، ثم أعد تغليف الحزمة من المصدر، وحدّث `dist/` و`ASHEN-ARENA-HANDOFF.md` عند تغير السياق.

## الأمان

لا تضع رموز GitHub أو مفاتيح Supabase أو أي كلمات مرور في هذا المستودع. المستودع للقواعد والسياق فقط، وكود اللعبة يبقى في مستودع `ashen-arena`.
