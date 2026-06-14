# RayatAuto — توزيع Firefox (موقَّع + تحديث تلقائي)

استضافة التوزيع الذاتي لإضافة **RayatAuto** على Firefox.

- **صفحة التثبيت:** https://myalsh2030.github.io/rayatauto-firefox/
- **updates.json:** بيان التحديث الذي يقرأه Firefox تلقائياً (update_url).
- **الإصدارات (.xpi الموقَّع):** في قسم Releases.

## لإصدار نسخة جديدة (للمطوّر)
1. ارفع الحزمة على AMO (توزيع ذاتي) ونزّل ملف .xpi الموقَّع.
2. أنشئ Release بوسم vX.Y.Z وأرفِق الملف باسم rayatauto-X.Y.Z.xpi.
3. حدّث updates.json: أضف عنصراً بـ version و update_link (ويفضّل update_hash).
4. يكتشف Firefox التحديث تلقائياً ويُثبّته للزملاء.

سياسة الخصوصية: https://gist.github.com/myalsh2030/b0bf3ea4f38564c41fa8d7a2397bfc8b
