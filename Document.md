### manifest Configure

#### Browser or Page

```json
{
    "browser_action": {
        "default_icon": "img/icon-16.png",
        "default_title": "Chrome Extension Quick Start",
        "default_popup": "popup.html"
    },
    "page_action": {
		"default_icon": "img/icon-48.png",
		"default_title": "Chrome Extension Quick Start",
		"default_popup": "popup.html"
    },
}
```

#### permissions

```json
{
    "permissions": [
        "contextMenus",
        "tabs",
        "notifications",
        "webRequest",
        "webRequestBlocking",
        "storage",
        "http://*/*",
        "https://*/*"
    ],
}
```

### Reference

[manifest](https://developer.chrome.com/extensions/manifest)