# selenium_browser_drivers
browser drivers for web automation by selenium

For IE 11 only, you will need to set a registry entry on the target computer so that the driver can maintain a connection to the instance of Internet Explorer it creates. For 64-bit Windows installations, the key is HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Internet Explorer\Main\FeatureControl\FEATURE_BFCACHE. Please note that the FEATURE_BFCACHE subkey may or may not be present, and should be created if it is not present. Important: Inside this key, create a DWORD value named iexplore.exe with the value of 0.

edge: Release 17134, Microsoft Edge version supported: 17.17134, url: https://download.microsoft.com/download/F/8/A/F8AF50AB-3C3A-4BC4-8773-DC27B32988DD/MicrosoftWebDriver.exe

firefox: geckodriver v0.24.0, Firefox version 67.0, url: https://github.com/mozilla/geckodriver/releases

chrome: ChromeDriver 74.0.3729.6, chrome version 74, url: https://sites.google.com/a/chromium.org/chromedriver/downloads

ie: IEDriver 3.9.0, IE version 11.706.17134.0, url: https://github.com/SeleniumHQ/selenium/wiki/InternetExplorerDriver

safari: 

