---
title:  قواعد البيانات
anchor: databases
---

# قواعد البيانات {#databases_title}

عادةً ما تقوم بٱستخدام قاعدة بيانات لبرنامجك لتخزين المعلومات. لديك خيارات محدودة للٱتصال والتعامل مع قاعدة البيانات.
الطريقة المستحسنة **حتى إصدار PHP 5.1.0** هي ٱستخدام لاحقات التشغيل المدمجة مثل [mysqli] و [pgsql] و [mssql] ... ألخ.

لاحقات التشغيل المدمجة ممتازة إذا كنت تستخدم _قاعدة بيانات واحدة_ في برنامجك، ولكن مثلاً إذا كنت تستخدم MySQL والقليل من MSSQL، أو ربما تريد أن تتصل مع قاعدة بيانات أوراكل، عندها لن تتمكن من ٱستخدام نفس تلك اللواحق. 
سوف تحتاج لتعلم طريقة API جديدة لكل لاحقة قاعدة بيانات &mdash; وهذا شيء مجهد.


[mysqli]: http://php.net/mysqli
[pgsql]: http://php.net/pgsql
[mssql]: http://php.net/mssql
