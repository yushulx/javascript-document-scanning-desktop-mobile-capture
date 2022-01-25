# JavaScript Document Scanning for Desktop and Mobile Browsers
The samples demonstrate how to use [Dynamic Web TWAIN](https://www.dynamsoft.com/web-twain/features/mobile-web-capture-sdk/) to build document scanning applications using JavaScript for desktop and mobile platforms.

## SDK Installation and Activation
- [![](https://img.shields.io/badge/Download-Offline%20SDK-orange)](https://www.dynamsoft.com/web-twain/downloads)
- [![](https://img.shields.io/badge/Get-30--day%20FREE%20Trial%20License-blue)](https://www.dynamsoft.com/customer/license/trialLicense/?product=dwt)

    1. Open `<Dynamic Web TWAIN version>/Resources/dynamsoft.webtwain.config.js` to configure the license key:

        ```javascript
        Dynamsoft.DWT.ProductKey = 'LICENSE KEY';
        ```
    
    2. Copy `<Dynamic Web TWAIN version>/Resources` to the static resource folder of your web project.


## Examples
- scanner.html
  
    - Scan documents from document scanners. 
    - Support Windows, Linux and macOS.
    
- camera.html
    - Scan documents from cameras.
    - Support desktop and mobile web browsers.
    
- advanced.html
    - Scan documents from cameras.
    - Support desktop and mobile web browsers.
    - Support document edge detection and perspective correction.

## Deployment

**HTTP**

```bash
python -m http.server
```

**HTTPS**
1. Install [ngrok](http://ngrok.com/).
2. Run:
    ```
    ngrok http 8000
    ```

## Blog
[How to Scan Document from Scanner and Camera Using JavaScript](https://www.dynamsoft.com/codepool/webassembly-web-document-capture-management-sdk.html)
