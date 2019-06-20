# Cordova-Plugin-Html2pdf
Plugin for **cordova greater or equal than v3.0.0_** to enable to call Mobile.

[![Build status](https://dev.azure.com/public-org/AzurePipeline/_apis/build/status/Cordova-Phone-Html2Pdf%20Plugin)](https://dev.azure.com/public-org/AzurePipeline/_build/latest?definitionId=0)


Installation
===============

Just type the following statement in your cli Cordova for install.

`cordova plugin add cordova-plugin-html2pdf`

if you want to install a specific version just add `@<version>` to the link

Example:

`cordova plugin add cordova-plugin-html2pdf@0.0.1`

Description
===========
Enables Cordova apps on the iPhone and Android platforms
to create pdf based on html and store it on device.


Usage
=====

##### On Download function: 

```javascript

cordova.plugins.html2pdf.create(
  "<html><head></head><body><h1>Some</h1><p>html content.</p></body></html>",
  "~/Documents/test.pdf", // on iOS,
// "test.pdf", on Android (will be stored in /mnt/sdcard/cordova.plugin.html2pdf/test.pdf)
  success,
  error
);

```

## License

This plugin was created under the MIT license.