Privacy Policy — Land Size Unit Converter

Last updated: February 2026

Land Size Unit Converter is a browser extension that converts land area measurements between square meters, hectares, and acres on web pages.

Data collection
This extension does not collect, store, transmit, or share any personal data or browsing information. It has no analytics, no tracking, and no server-side components.

Data storage
The extension stores two user preferences using Chrome's built-in sync storage API (chrome.storage.sync):

Your preferred display unit (m², ha, or ac)
Your list of allowed domains
These settings sync across your Chrome browsers via your Google account, using Chrome's own sync infrastructure. The extension developer has no access to this data.

Permissions

storage: Save and sync your preferences (display unit and allowed domains)
activeTab: Read the current tab's URL to determine if the site is in your allowed list, and to power the "Add this Site" button in the popup
tabs: Reload the current tab after adding a new domain so the extension activates immediately
Content script on all URLs: The extension's content script is loaded on all pages so it can activate on any domain the user adds to their allowed list. The script checks the domain against the user's allowed list before doing any work — if the site is not allowed, the script exits immediately and makes no changes to the page.
Third-party services
This extension does not communicate with any external servers, APIs, or third-party services. All conversion is performed locally in your browser.

Contact
If you have questions about this privacy policy, leave a comment.
