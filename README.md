[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://vshymanskyy.github.io/StandWithUkraine)

<p align="center">
    <a href="https://webdriver.io/">
        <img alt="WebdriverIO" src="https://webdriver.io/assets/images/robot-3677788dd63849c56aa5cb3f332b12d5.svg" width="146">
    </a>
</p>

<p align="center">
    إطار عمل اختبار أتمتة الأجهزة المحمولة والمتصفحات من الجيل التالي لـ Node.js

<p align="center">
    <a href="https://github.com/webdriverio/webdriverio/actions/workflows/test.yml">
        <img alt="Build Status" src="https://github.com/webdriverio/webdriverio/actions/workflows/test.yml/badge.svg">
    </a>
    <a href="https://snyk.io/advisor/npm-package/webdriverio">
        <img alt="Package Health" src="https://snyk.io/advisor/npm-package/webdriverio/badge.svg">
    </a>
    <a href="https://bestpractices.coreinfrastructure.org/en/projects/5589">
        <img alt="OpenSSF Best Practices" src="https://bestpractices.coreinfrastructure.org/projects/5589/badge">
    </a>
    <a title="Crowdin" target="_blank" href="https://translate.webdriver.io/project/webdriver-io">
        <img src="https://badges.crowdin.net/webdriver-io/localized.svg">
    </a>
    <br />
    <a href="https://discord.webdriver.io">
        <img alt="Support Channel" src="https://img.shields.io/discord/1097401827202445382?color=%234FB898&label=Join%20us%20on%20Discord">
    </a>
    <a href="https://github.com/webdriverio/webdriverio/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc">
        <img alt="Issue Resolution time" src="http://isitmaintained.com/badge/resolution/webdriverio/webdriverio.svg">
    </a>
    <a href="https://github.com/webdriverio/webdriverio/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc">
        <img alt="Open issues" src="http://isitmaintained.com/badge/open/webdriverio/webdriverio.svg">
    </a>
</p>

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
ويب درايفرهو إطار عمل اتمتة للاختبار، شامل من البداية الى النهاية بالإضافة إلى اختبار الوحدات والمكونات في المتصفح، والذي يسمح لك بإجراء الاختبارات بناءً على 
[WebDriver]
(https://w3c.github.io/webdriver/webdriver-spec.html) 
[WebDriver BiDi](https://github.com/w3c/webdriver-bidi) 
الى جانب تقنية اتمتة 
[Appium](http://appium.io/) 

فهو يوفر الدعم لإطار اختبار BDD/TDD.

كما سيقوم باختباراتك محليًا أو في السحابة باستخدام Sauce Labs أو BrowserStack أو TestingBot أو LambdaTest.


## :woman_technologist: :man_technologist: Contributing

هل تريد المساعدة في تحسين درايفر ويب؟ قم بإلقاء نظرة على [وثائق المساهمين](CONTRIBUTING.md) للبدء ومعرفة المساهمات التي يمكن تقديمها وكيفية تقديمها.
### الشروع في العمل مع جيت هب كود سبيسس

للبدء، قم بإنشاء مساحة كود لهذا المستودع بالنقر فوق 👇

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)]
(https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=2296970)

سيتم فتح كود سبيس لإصدار مستند إلى الويب من فيجوال ستديو كود
تم تكوين [حاوية التطوير](.devcontainer/devcontainer.json) بالكامل بالبرنامج المطلوب لهذا المشروع.

**ملاحظة**: حاويات التطوير هي مواصفات مفتوحة مدعومة بواسطة [GitHub Codespaces](https://github.com/codespaces) و[أدوات أخرى](https://containers.dev/supporting).

### البدء مع Gitpod

يمكنك أيضًا النقر فقط على:

[![فتح في Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/webdriverio/webdriverio)

للحصول على بيئة تطوير جاهزة للاستخدام لبدء العمل على قاعدة التعليمات البرمجية هذه.


## :الحزمة: الحزم

يحتوي هذا المستودع على بعض الحزم الأساسية لمشروع WebdriverIO. هناك العديد من [الموارد المنسقة] الرائعة (https://github.com/webdriverio-community/awesome-webdriverio) التي قام مجتمع WebdriverIO بتجميعها.

### نواة

- [webdriver](https://github.com/webdriverio/webdriverio/tree/main/packages/webdriver) - تنفيذ روابط Node.js لـ W3C WebDriver وMobile JSONWire Protocol
- [webdriverio](https://github.com/webdriverio/webdriverio/blob/main/packages/webdriverio) - إطار عمل اختبار أتمتة الأجهزة المحمولة ومتصفح الجيل التالي لـ Node.js
- [@wdio/cli](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-cli) - واجهة سطر أوامر WebdriverIO testrunner


### مساعد

- [@wdio/config](https://github.com/webdriverio/webdriverio/blob/main/packages/wdio-config) - أداة مساعدة لتحليل خيارات WebdriverIO والتحقق من صحتها
- [@wdio/logger](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-logger) - أداة مساعدة لتسجيل حزم WebdriverIO
- [@wdio/protocols](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-protocols) - حزمة الأدوات المساعدة التي توفر معلومات حول بروتوكولات التشغيل الآلي
- [@wdio/repl](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-repl) - أداة مساعدة WDIO لتوفير واجهة repl لـ WebdriverIO
- [@wdio/reporter](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-reporter) - أداة WebdriverIO للمساعدة في الإبلاغ عن جميع الأحداث
- [@wdio/runner](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-runner) - خدمة WebdriverIO التي تجري اختبارات في بيئات عشوائية
- [@wdio/utils](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-utils) - أداة مساعدة WDIO لتوفير العديد من وظائف الأداة المساعدة المستخدمة عبر المشروع
- [@wdio/globals](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-globals) - أداة مساعدة WDIO لاستيراد المتغيرات العامة مباشرة
### Reporter

- [@wdio/allure-reporter](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-allure-reporter) - A WebdriverIO reporter plugin to create Allure Test Reports
- [@wdio/concise-reporter](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-concise-reporter) - A WebdriverIO reporter plugin to create concise test reports
- [@wdio/dot-reporter](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-dot-reporter) - A WebdriverIO plugin to report in dot style
- [@wdio/junit-reporter](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-junit-reporter) - A WebdriverIO reporter that creates test results in XML format
- [@wdio/spec-reporter](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-spec-reporter) - A WebdriverIO plugin to report in spec style
- [@wdio/sumologic-reporter](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-sumologic-reporter) - A WebdriverIO reporter that sends test results to Sumologic for data analyses

### Services

- [@wdio/appium-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-appium-service) - A WebdriverIO service to start & stop Appium Server
- [@wdio/browserstack-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-browserstack-service) - A WebdriverIO service that can be used to use BrowserStack Test Observability which is a reporting, debugging, and test suite quality tracking tool for any test running anywhere. The service also helps for a better integration with the BrowserStack grid if you're running tests on the grid.
- [@wdio/lighthouse-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-lighthouse-service) - A WebdriverIO service that integrates Google Lighthouse commands to use it for automate tests
- [@wdio/firefox-profile-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-firefox-profile-service) - A WebdriverIO service that lets you define your Firefox profile in your wdio.conf.js
- [@wdio/sauce-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-sauce-service) - A WebdriverIO service that provides a better integration into Sauce Labs
- [@wdio/shared-store-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-shared-store-service) - A WebdriverIO service to exchange data across processes
- [@wdio/testingbot-service](https://github.com/webdriverio/webdriverio/tree/main/packages/wdio-testingbot-service) - A WebdriverIO service that provides a better integration into TestingBot

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

## :handshake: Project Governance

This project is maintained by [awesome people](/AUTHORS.md) following a common [set of rules](/GOVERNANCE.md) and treating each other with [respect and appreciation](/CODE_OF_CONDUCT.md).

## :man_cook: :woman_cook: Backers

[Become a backer](https://opencollective.com/webdriverio) and show your support for our open-source project.

<a href="https://opencollective.com/webdriverio"><img src="https://opencollective.com/webdriverio/tiers/baker.svg?avatarHeight=36&width=600"></a>

## :money_with_wings: Sponsors

Does your company use WebdriverIO? Ask your manager or marketing team if your company would be interested in supporting our project. Support will allow the maintainers to dedicate more time to maintenance and new features for everyone. Also, your company's logo will show [on GitHub](https://github.com/webdriverio/webdriverio#readme) - who doesn't want a little extra exposure? [Here's the info](https://opencollective.com/webdriverio).

<a href="https://opencollective.com/webdriverio"><img src="https://opencollective.com/webdriverio/tiers/gold-sponsor.svg?avatarHeight=36&width=600"></a>

### 💎 Premium Sponsor

We are immensely grateful to our exclusive Premium Sponsor for their invaluable support in the development of this project:

<p align="center">
    <a href="https://www.browserstack.com/automation-webdriverio"><img src="https://webdriver.io/img/sponsors/browserstack_black.svg" alt="BrowserStack" /></a>
    &nbsp; &nbsp; &nbsp;
    <a href="https://saucelabs.com"><img src="https://webdriver.io/img/sponsors/saucelabs_black.svg" alt="Sauce Labs" width=400 /></a>
</p>

### 🥈 Silver Sponsor

<p align="center">
    <a href="https://www.lambdatest.com/"><img src="https://webdriver.io/img/sponsors/lambdatest_black.svg" width="300" alt="Lambdatest" /></a>
</p>

### 🥉 Bronze Sponsor

<p align="center">
    <a href="https://eslint.org/"><img src="https://eslint.org/assets/images/logo/eslint-logo-color.png" alt="Eslint" /></a>
</p>

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
<p align="center"><a href="https://github.com/webdriverio/webdriverio#"><img src="http://randojs.com/images/backToTopButton.png" alt="Back to top" height="29"/></a></p>
