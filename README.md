# Privacy Policy — Land Size Unit Converter

**Last updated:** February 2026

Land Size Unit Converter is a browser extension that converts land area measurements between square meters, hectares, and acres on web pages.

## Data collection

This extension does not collect, store, transmit, or share any personal data or browsing information. It has no analytics, no tracking, and no server-side components.

## Data storage

The extension stores two user preferences using Chrome's built-in sync storage API (`chrome.storage.sync`):

- Your preferred display unit (m², ha, or ac)
- Your list of allowed domains

These settings sync across your Chrome browsers via your Google account, using Chrome's own sync infrastructure. The extension developer has no access to this data.

## Permissions

| Permission | Purpose |
|---|---|
| **storage** | Save and sync your preferences (display unit and allowed domains). |
| **activeTab** | Read the current tab's URL when the popup is opened, to determine if the site is already in your allowed list and to power the "Add this Site" button. |
| **tabs** | Reload the current tab after adding a new domain so the extension activates immediately. |
| **scripting** | Programmatically inject the content script and stylesheet only on domains that appear in your allowed list. No code is injected on sites you have not explicitly added. |
| **host_permissions** | Required because the allowed domains list is user-configured at runtime and cannot be known at install time. The extension's background service worker checks each page against your allowed list before injecting any code. If the site is not on your list, nothing is injected and no page content is read or modified. |

## Third-party services

This extension does not communicate with any external servers, APIs, or third-party services. All conversion is performed locally in your browser.

## Disclaimer

This extension is provided as-is with no warranty. Conversions are approximate and should not be relied upon for legal, financial, or surveying purposes. Use at your own risk.

## Contact

If you have questions about this privacy policy, leave a comment.
