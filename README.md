
<p align="center">
    إطار عمل اختبار أتمتة الأجهزة المحمولة والمتصفحات من الجيل التالي لـ Node.js

<p align="center">
***

<p align="center">
    <a href="https://webdriver.io">الصفحة الرئيسية</a> |
    <a href="https://webdriver.io/docs/gettingstarted.html">دليل المطور</a> |
    <a href="https://webdriver.io/docs/api.html">API مرجع</a> |
    <a href="https://github.com/webdriverio/webdriverio/blob/main/CONTRIBUTING.md">المساهمة</a> |
    <a href="https://github.com/webdriverio/webdriverio/blob/main/CHANGELOG.md">سجل التغيير</a> |
    <a href="https://github.com/webdriverio/webdriverio/blob/main/ROADMAP.md">خارطة الطريق</a>
</p>

***
ويب درايفرهو إطار عمل اتمتة للاختبار، شامل من البداية الى النهاية بالإضافة إلى اختبار الوحدات والمكونات في المتصفح، والذي يسمح لك بإجراء الاختبارات بناءً على [WebDriver] (https://w3c.github.io/webdriver/webdriver-spec.html).[WebDriver BiDi](https://github.com/w3c/webdriver-bidi) الى جانب تقنية اتمتة [Appium](http://appium.io/) 

كما يوفر الدعم لإطار اختبار BDD/TDD. ويقوم باختباراتك محليًا أو في السحابة باستخدام Sauce Labs أو BrowserStack أو TestingBot أو LambdaTest.

### البدء مع github


للبدء من خلال إنشاء المساحات البرمجية لهذا المستودع, قم بالنقر على👇
[![افتح من خلال مساحات جيت هب البرمجية](https://github.com/codespaces/badge.svg)] (https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=2296970)

سيتم فتح مساحة برمجية لإصدار قائم على الويب من فيجوال ستديو كود.
لتكوين حاوية تطوير شاملة لكل البرامج المطلوبة لهذا المشروع قم بالنقر على 👇
[حاوية التطوير](.devcontainer/devcontainer.json).

**ملاحظة**: حاويات التطوير مفتوحة و مدعومة بواسطة [جيت هب المساحات البرمجية](https://github.com/codespaces) و[أدوات أخرى](https://containers.dev/supporting).

### البدء مع Gitpod

يمكنك أيضًا النقر فقط على:

[![فتح في جيت بود ](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/webdriverio/webdriverio)

للحصول على بيئة تطوير جاهزة للاستخدام لبدء العمل على قاعدة التعليمات البرمجية هذه.


## : الحزم

يحتوي هذا المستودع على بعض الحزم الأساسية لمشروع WebdriverIO. 
و العديد من [الموارد المنسقة] (https://github.com/webdriverio-community/awesome-webdriverio)
التي قام مجتمع WebdriverIO بتجميعها.

### نواة
- التنفيذ ب Node.js لـ W3C WebDriver وMobile JSONWire Protocol.
- [ويب درايفر](https://github.com/webdriverio/webdriverio/tree/main/packages/webdriver)

- [ويب درايفر اي او](https://github.com/webdriverio/webdriverio/blob/main/packages/webdriverio)

- إطار عمل اختبار  لـ Node.js و أتمتة الأجهزة المحمولة ومتصفح الجيل التالي[@wdio/cli](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-cli)
واجهة سطر أوامر WebdriverIO testrunner


### مساعد

- [@wdio/config](https://github.com/webdriverio/webdriverio/blob/main/packages/wdio-config)
- أداة مساعدة لتحليل خيارات ويب درايفر اي او والتحقق من صحتها.
     
- [@wdio/logger](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-logger)
- أداة مساعدة لتسجيل حزم ويب درايفر اي او.
  
- [@wdio/protocols](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-protocols)
- حزمة الأدوات المساعدة التي توفر معلومات حول بروتوكولات التشغيل الآلي.
  
- [@wdio/repl](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-repl)
- أداة مساعدة WDIO لتوفير واجهة repl لـ ويب درايفر اي او.
  
- [@wdio/reporter](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-reporter)
- أداة ويب درايفر اي او للمساعدة في الإبلاغ عن جميع الأحداث.
  
- [@wdio/runner](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-runner) 
-  خدمة ويب درايفر التي تجري اختبارات في بيئات عشوائية.
  
- [@wdio/utils](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-utils)
أداة مساعدة WDIO لتوفير العديد من وظائف الأداة المساعدة المستخدمة عبر المشروع.

- [@wdio/globals](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-globals)
-  أداة مساعدة WDIO لاستيراد المتغيرات العامة مباشرة.
### المراسل

- [@wdio/allure-reporter](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-allure-reporter)
- برنامج المساعد لمراسل WebdriverIO لتقارير اختبار Allure.

- [@wdio/concise-reporter](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-concise-reporter)
- مكون إضافي لمراسل WebdriverIO لإنشاء تقارير اختبار موجزة.
  
- [@wdio/dot-reporter](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-dot-reporter)
- مكون إضافي WebdriverIO للإبلاغ بأسلوب النقطة.
    
- [@wdio/junit-reporter](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-junit-reporter)
- مراسل WebdriverIO الذي يقوم بإنشاء نتائج الاختبار بتنسيق XML.
  
- [@wdio/spec-reporter](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-spec-reporter)
- مكون إضافي WebdriverIO للإبلاغ بأسلوب spec.
- 
- [@wdio/sumologic-reporter](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-sumologic-reporter)
- مراسل WebdriverIO الذي يرسل نتائج الاختبار إلى Sumologic لتحليل البيانات.
       

### الخدمات

- [@wdio/appium-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-appium-service)
- خدمة WebdriverIO لبدء وإيقاف خادم Appium
  
- [@wdio/browserstack-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-browserstack-service)
- خدمة WebdriverIO التي يمكن استخدامها لاستخدام BrowserStack Test Observability وهي أداة لتتبع جودة التقارير وتصحيح الأخطاء ومجموعة الاختبارات لأي اختبار يتم إجراؤه في أي مكان. تساعد الخدمة أيضًا في تحقيق تكامل أفضل مع شبكة BrowserStack إذا كنت تجري اختبارات على الشبكة.
  
- [@wdio/lighthouse-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-lighthouse-service)
- خدمة WebdriverIO التي تدمج أوامر Google Lighthouse لاستخدامها في الاختبارات التلقائية
  
- [@wdio/firefox-profile-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-firefox-profile-service)
- خدمة WebdriverIO التي تتيح لك تحديد ملف تعريف Firefox الخاص بك في wdio.conf.js
  
- [@wdio/sauce-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-sauce-service)
- خدمة WebdriverIO التي توفر تكاملًا أفضل مع Sauce Labs
- 
- [@wdio/shared-store-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-shared-store-service)
- خدمة WebdriverIO لتبادل البيانات عبر العمليات
- 
- [@wdio/testingbot-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-testingbot-service)
- خدمة WebdriverIO التي توفر تكاملًا أفضل في TestingBot.
### Runner

- [@wdio/local-runner](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-local-runner) - A WebdriverIO runner to run tests locally
- [@wdio/browser-runner](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-browser-runner) - A WebdriverIO runner to run unit or component tests in the browser

### Framework Adapters

- [@wdio/cucumber-framework](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-cucumber-framework) - Adapter for [Cucumber](https://cucumber.io/) testing framework
- [@wdio/jasmine-framework](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-jasmine-framework) - Adapter for [Jasmine](https://jasmine.github.io/) testing framework
- [@wdio/mocha-framework](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-mocha-framework) - Adapter for [Mocha](https://mochajs.org/) testing framework.

### Others

- [eslint-plugin-wdio](https://github.com/webdriverio/webdriverio/tree/main/packages/eslint-plugin-wdio) - Eslint rules for WebdriverIO
- [@wdio/smoke-test-reporter](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-smoke-test-reporter) - A WebdriverIO utility to smoke test reporters for internal testing purposes
- [@wdio/smoke-test-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-smoke-test-service) - A WebdriverIO utility to smoke test services for internal testing purposes
- [@wdio/webdriver-mock-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-webdriver-mock-service) - A WebdriverIO service to stub all endpoints for internal testing purposes


## :page_facing_up: License

[MIT](/LICENSE-MIT)

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fwebdriverio%2Fwebdriverio.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fwebdriverio%2Fwebdriverio?ref=badge_large)

## :beginner: Badge

Show the world you're using webdriver.io → [![tested with webdriverio](https://img.shields.io/badge/tested%20with-webdriver.io-%23ea5906)](https://webdriver.io/)

###### GitHub markup
```
[![tested with webdriver.io](https://img.shields.io/badge/tested%20with-webdriver.io-%23ea5906)](https://webdriver.io/)
```
###### HTML
```
<a href="https://webdriver.io/">
    <img alt="WebdriverIO" src="https://img.shields.io/badge/tested%20with-webdriver.io-%23ea5906">
</a>
```

## :clap:  Supporters
[![Stargazers repo roster for WebdriverIO](https://reporoster.com/stars/webdriverio/webdriverio)](https://github.com/webdriverio/webdriverio/stargazers)
[![Forkers repo roster for WebdriverIO](https://reporoster.com/forks/webdriverio/webdriverio)](https://github.com/webdriverio/webdriverio/network/members)
<p align="center"><a href="https://github.com/webdriverio/webdriverio#nastyox"><img src="http://randojs.com/images/barsSmall.gif" alt="Animated footer bars" width="100%"/></a></p>
<br/>
<p align="center"><a href="https://github.com/mEleventh/webdriverio#"><img src="http://randojs.com/images/backToTopButton.png" alt="العودة لأعلى" height="29"/></a></p>
