# Paywall Remover 9000

Removes paywalls from news/media websites by changing the `User-Agent` request header to GoogleBot's user agent for some requests

## Firefox (desktop)

Go to `about:debugging#/runtime/this-firefox` and click "Load temporary add-on"

## Firefox (Android)

```
npx web-ext run -t firefox-android
```

See [developing-extensions-for-firefox-for-android](https://extensionworkshop.com/documentation/develop/developing-extensions-for-firefox-for-android/) for more info

## Chrome (desktop)

Go to `chrome://extensions/` and click "Load unpacked"
