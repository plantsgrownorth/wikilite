WikiLite Privacy Policy
Last updated: April 26, 2026
Summary
WikiLite is a Chrome extension that improves the reading experience on Wikipedia, Wiktionary, and Wikiquote. It does not collect, transmit, sell, share, or sell access to any user data. Everything WikiLite stores stays on your own device.
What WikiLite Stores Locally
WikiLite uses Chrome's built-in chrome.storage.local API to save the following on your computer only:

Reading preferences: theme choice, font family, font size, line height, column width, justify on/off, drop-cap on/off, table-of-contents visibility, and similar UI settings.
Recently viewed list: for each Wikipedia article you read with the extension active, WikiLite records the page title, URL, language, thumbnail URL, and timestamp. This list is capped at 50 entries per language and is used solely to populate the "Recently viewed" panel inside the extension.
Saved offline articles: if you click "Save for offline use" on an article, WikiLite stores a snapshot of that article's HTML and images (encoded as data URIs) so you can read it again with no internet connection. Saved articles persist until you remove them or uninstall the extension.

All of this data is stored on your local device. None of it is ever transmitted to the WikiLite developer, to any analytics service, to any advertising network, or to any third party. There is no server-side component to WikiLite. There is no server.
Network Requests WikiLite Makes
When you actively use a feature that needs live data, WikiLite contacts the official public Wikimedia APIs over HTTPS, exactly the same endpoints your browser would contact when you visit those sites normally:

wikipedia.org, wiktionary.org, wikiquote.org and their language subdomains, for article content, link previews, search suggestions, word definitions, and language lists.
upload.wikimedia.org, for article images.

WikiLite makes no requests to any other domain, sends no telemetry, and does not include any third-party scripts, advertising SDKs, or trackers.
Permissions and Why They Are Used

storage: to save reading preferences locally.
unlimitedStorage: so you can save more than one image-heavy article for offline reading.
webNavigation: to detect when a Wikipedia tab fails to load because you're offline, so the extension can show your saved offline copy instead of Chrome's network-error page.
contextMenus: to add right-click menu items for "Search Wikipedia" and "Look up in Wiktionary" on selected text.
Host access to wikipedia.org, wiktionary.org, and wikiquote.org: required so the extension's content script can restyle and enhance these pages. The extension is not active on any other website.

Data You Can Delete at Any Time
You can remove all locally stored WikiLite data at any time by:

Clicking "Reset everything to defaults" in the WikiLite options page, or
Right-clicking the WikiLite icon and choosing "Remove from Chrome," which uninstalls the extension and clears all of its local storage.

Children's Privacy
WikiLite does not collect any personal information from anyone, including children. The extension is suitable for all ages.
Changes to This Policy
If this policy is ever updated, the new version will be posted at the same public URL with a revised "Last updated" date.
Contact
If you have any questions about this privacy policy or about WikiLite, email plantsgrownorth@gmail.com.
