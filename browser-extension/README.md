# PhishGuard AI - Browser Extension

This directory contains the source files for the PhishGuard AI client-side browser extension.

## Purpose

To provide real-time protection directly in the user's browser by intercepting and scanning visited URLs, detecting phishing indicators on webpages, and warning users before they interact with malicious content.

## Planned Contents

* **Manifest File**: Extension manifest (Manifest V3) declaring permissions, background scripts, and assets.
* **Background Scripts**: Service workers handling connection with backend APIs, tab events, and threat checks.
* **Content Scripts**: Scripts injected into web pages to extract page characteristics and display safety alerts.
* **Popup & Options Pages**: The user interface displayed when the extension icon is clicked.

## Planned Technologies

* **Target Environment**: Chromium-based browsers (Chrome, Edge, Brave, Opera) and Firefox
* **Languages**: HTML, CSS, TypeScript / JavaScript
* **APIs**: Chrome Extension Web APIs (Tabs, WebRequest, Storage)
