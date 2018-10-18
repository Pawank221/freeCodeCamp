---
title: React Native
localeTitle: تتفاعل الأصلية
---
## تتفاعل الأصلية

React Native عبارة عن إطار متعدد المنصات لبناء تطبيقات الجوال التي يمكن تشغيلها خارج المتصفح - معظم تطبيقات iOS و Android

يمكن استخدامه لإنشاء تطبيقات على أجهزة Windows ، وتطبيقات OS سطح المكتب ، وتطبيقات Apple TV أيضًا ، ولكن هذا الدليل سيغطي فقط الأغراض الأكثر شيوعًا - تطبيقات Android و iOS.

**جدول المحتويات**

*   [ما هو React Native؟](#what-is-react-native)
*   [أسباب لاختيار React Native](#reasons-to-choose-react-native)
*   [كيف تبدأ مع React Native](#how-to-get-started-with-react-native)

### ما هو رد الفعل الأصلية

يقع React Native بين التطبيقات المحلية والتطبيقات المختلطة على طيف التطبيق المحمول. تعد واجهة المستخدم التي تنشئها محلية تمامًا ، كما أن أداء التطبيق العام يكاد يكون جيدًا مثل كتابة تطبيق أصلي. كما أنه يمنحك المرونة لتضمين عرض الويب (صفحات الويب) أو كود أصلي (Java / Kotlin for Android ، Objective C / Swift for iOS) داخل تطبيقاتك أينما تريد.

يتبع نفس نمط رد الفعل حيث يتم عرض طرق العرض (ما تراه على الشاشة) من ملفات JavaScript. ويكمن الاختلاف في أنها توفر واجهة برمجة التطبيقات الخاصة بها للتعامل مع طرق عرض الجوال المحلية مقارنة بـ DOM على الويب. إذا كنت مرتبكًا حول كيفية عمل ذلك ، اتبع هذا الدليل على freeCodeCamp وسيأخذك خطوة بخطوة خلال هذه المفاهيم.

### أسباب لاختيار React Native

1.  **إعادة استخدام الرمز** - يستخدم رمزًا واحدًا يتم مشاركته بين النظامين الأساسيين.
2.  **إعادة استخدام أدوات ومهارات الويب** - يمكنك إعادة استخدام معلومات وأدوات وأدوات مساعدة JavaScript مثل `axios` و Redux والمكتبات الأخرى التي لا تتطلب DOM من الويب.
3.  **محسّن لإنتاجية المطورين** - يأتي بمميزات مثل إعادة تحميل الوحدة النمطية / الفورية وأدوات مطوّري البرامج Chrome لتصحيح الأخطاء خارج المربع!
4.  **الأداء** - أداء أفضل من أطر التطبيقات الهجينة مثل Ionic و Cordova نظرًا لأنها لا تستخدم طرق عرض الويب.
5.  **دعم الشركات** - **تدعم** الكثير من الشركات وتسهم في React Native بما في ذلك Walmart و Airbnb و Wix وبالطبع Facebook.
6.  **المجتمع** - React Native له مجتمع كبير (ومتزايد) مع أكثر من 1500 مساهم في المشروع الأساسي وآلاف أخرى ممن يساهمون في المكتبات المختلفة.
7.  **تجربة مستخدم أفضل** - يستخدم React Native شفرة JavaScript لتقديم المكونات الأصلية من نظام التشغيل الخاص بهاتفك. وبعبارة أخرى ، فإن واجهة المستخدم للتطبيق (UI) هي محلية بالكامل!
8.  **Cross-Platform** - طريقة رائعة لنموذج ووفر الوقت أثناء إنشاء تطبيق عالمي خاص بكل مستخدم على حدة أو تطبيق جوال خاص بالنظام الأساسي يمكن تشغيله على كل من أجهزة iOS و Android.

### كيف تبدأ مع React Native

هناك طريقتان سريعتان سهلتان للبدء مع React Native. اعتمادا على وضعك ، يمكن للمرء أن يكون خيارا أفضل بالنسبة لك.

1.  [Create React Native App](https://www.npmjs.com/package/create-react-native-app) - على غرار إنشاء تطبيق React فإنه الحصول على ما يصل في تشغيل باستخدام المحطة.
2.  [Expo](https://expo.io) - Best for prototyping an app or if above stage. باستخدام Expo ، يمكنك أيضًا إنشاء تطبيق سريع باستخدام ميزات السحب والإفلات من snack.expo.io في broswer.