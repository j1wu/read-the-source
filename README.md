SAPUI5 / OpenUI5 Source Code Study
======================================

This repository shares some of my findings while studying SAPUI5 / [OpenUI5](https://github.com/SAP/openui5) source code.

### Table of Contents

- SAPUI5 walkthrough and dive in series *([tutorial](https://sapui5.hana.ondemand.com/sdk/#docs/guide/3da5f4be63264db99f2e5b04c5e853db.html) source code can be found [here](https://github.com/j1wu/sapui5-walkthrough))*
	- [Step 1](https://sapui5.netweaver.ondemand.com/sdk/docs/guide/2680aa9b16c14a00b01261d04babbb39.html): Hello World! [Where it all began](walkthrough-dive-in/step1.md)
		- [OO in JavaScript](walkthrough-dive-in/step1.md#oo-in-javascript)
		- [JavaScript function, object, prototype, constructor, proto relationships illustrated](walkthrough-dive-in/step1.md#javascript-function-object-prototype-constructor-proto-relationships-illustrated)
		- [What does createClass method offer?](walkthrough-dive-in/step1.md#what-does-createclass-method-offer)
		- [How does prototype object get enriched?](walkthrough-dive-in/step1.md#how-does-prototype-object-get-enriched)
	- [Step 3](https://sapui5.hana.ondemand.com/sdk/#docs/guide/ddbceecd7d3d42eea9cf78a820a238fb.html): Controls. [How does controls work?](walkthrough-dive-in/step3.md)
		- [How does lazy require work?](walkthrough-dive-in/step3.md#how-does-lazy-require-work)
		- [How does a control module get requested, loaded and executed?](walkthrough-dive-in/step3.md#how-does-a-control-module-get-requested-loaded-and-executed)
		- [How does a control object get created?](walkthrough-dive-in/step3.md#how-does-a-control-object-get-created)
		- [How does a control object get turned into HTML?](walkthrough-dive-in/step3.md#how-does-a-control-object-get-turned-into-html)
	- [Step 6](https://sapui5.netweaver.ondemand.com/sdk/docs/guide/f665d0de4dba405f9af4294de824b03b.html): Modules. [How does modules work?](walkthrough-dive-in/step6.md)
		- [How does a module get defined?](walkthrough-dive-in/step6.md#how-does-a-module-get-defined)
		- [How does a module get consumed?](walkthrough-dive-in/step6.md#how-does-a-module-get-consumed)
		- [What are the module states available?](walkthrough-dive-in/step6.md#what-are-the-module-states-available)
		- [How does a module get loaded?](walkthrough-dive-in/step6.md#how-does-a-module-get-loaded)
		- [How does a module get executed?](walkthrough-dive-in/step6.md#how-does-a-module-get-executed)
		- [How does a module get made available to global name space?](walkthrough-dive-in/step6.md#how-does-a-module-get-made-available-to-global-name-space)
	- [Step 8](https://sapui5.hana.ondemand.com/sdk/#docs/guide/df86bfbeab0645e5b764ffa488ed57dc.html): Translatable Texts. [How does i18n work?](walkthrough-dive-in/step8.md)
		- [How does UI5 pick up the browser language setting?](walkthrough-dive-in/step8.md#how-does-ui5-pick-up-the-browser-language-setting)
		- [How does the i18n files get loaded?](walkthrough-dive-in/step8.md#how-does-the-i18n-files-get-loaded)
		- [How does the parameters get evaluated?](walkthrough-dive-in/step8.md#how-does-the-parameters-get-evaluated)
- How does X work series
	- [How does bindAggregation work?](screenshots/how-does-bindAggregation-work.png)
