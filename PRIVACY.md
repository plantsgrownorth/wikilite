<h1>WikiLite Privacy Policy</h1>
<p class="updated">Last updated: April 26, 2026</p>

<h2>Summary</h2>
<p>WikiLite is a Chrome extension that improves the reading experience on Wikipedia, Wiktionary, and Wikiquote. It does not collect, transmit, sell, share, or sell access to any user data. Everything WikiLite stores stays on your own device.</p>

<h2>What WikiLite Stores Locally</h2>
<p>WikiLite uses Chrome's built-in <code>chrome.storage.local</code> API to save the following on your computer only:</p>
<ul>
  <li><strong>Reading preferences:</strong> theme choice, font family, font size, line height, column width, justify on/off, drop-cap on/off, table-of-contents visibility, and similar UI settings.</li>
  <li><strong>Recently viewed list:</strong> for each Wikipedia article you read with the extension active, WikiLite records the page title, URL, language, thumbnail URL, and timestamp. This list is capped at 50 entries per language and is used solely to populate the "Recently viewed" panel inside the extension.</li>
  <li><strong>Saved offline articles:</strong> if you click "Save for offline use" on an article, WikiLite stores a snapshot of that article's HTML and images (encoded as data URIs) so you can read it again with no internet connection. Saved articles persist until you remove them or uninstall the extension.</li>
</ul>
<p>All of this data is stored on your local device. None of it is ever transmitted to the WikiLite developer, to any analytics service, to any advertising network, or to any third party. There is no server-side component to WikiLite. There is no server.</p>

<h2>Network Requests WikiLite Makes</h2>
<p>When you actively use a feature that needs live data, WikiLite contacts the official public Wikimedia APIs over HTTPS, exactly the same endpoints your browser would contact when you visit those sites normally:</p>
<ul>
  <li><code>wikipedia.org</code>, <code>wiktionary.org</code>, <code>wikiquote.org</code> and their language subdomains, for article content, link previews, search suggestions, word definitions, and language lists.</li>
  <li><code>upload.wikimedia.org</code>, for article images.</li>
</ul>
<p>WikiLite makes no requests to any other domain, sends no telemetry, and does not include any third-party scripts, advertising SDKs, or trackers.</p>

<h2>Permissions and Why They Are Used</h2>
<ul>
  <li><code>storage</code>: to save reading preferences locally.</li>
  <li><code>unlimitedStorage</code>: so you can save more than one image-heavy article for offline reading.</li>
  <li><code>webNavigation</code>: to detect when a Wikipedia tab fails to load because you're offline, so the extension can show your saved offline copy instead of Chrome's network-error page.</li>
  <li><code>contextMenus</code>: to add right-click menu items for "Search Wikipedia" and "Look up in Wiktionary" on selected text.</li>
  <li>Host access to <code>wikipedia.org</code>, <code>wiktionary.org</code>, and <code>wikiquote.org</code>: required so the extension's content script can restyle and enhance these pages. The extension is not active on any other website.</li>
</ul>

<h2>Data You Can Delete at Any Time</h2>
<p>You can remove all locally stored WikiLite data at any time by:</p>
<ul>
  <li>Clicking "Reset everything to defaults" in the WikiLite options page, or</li>
  <li>Right-clicking the WikiLite icon and choosing "Remove from Chrome," which uninstalls the extension and clears all of its local storage.</li>
</ul>

<h2>Children's Privacy</h2>
<p>WikiLite does not collect any personal information from anyone, including children. The extension is suitable for all ages.</p>

<h2>Changes to This Policy</h2>
<p>If this policy is ever updated, the new version will be posted at the same public URL with a revised "Last updated" date.</p>

<h2>Contact</h2>
<p>If you have any questions about this privacy policy or about WikiLite, email <strong><a href="mailto:plantsgrownorth@gmail.com">plantsgrownorth@gmail.com</a></strong>.</p>
