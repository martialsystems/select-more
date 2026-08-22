# Privacy Policy

**Select More** (the “Extension”)

**Effective date:** August 13, 2026  
**Last updated:** August 22, 2026  
**Developer / Data controller:** Martial Systems LLC  
**Contact:** martialsys@gmail.com  
**Website:** https://martialsys.net/

---

### 1. Summary (plain language)

**We do not save your data.**

| Question | Answer |
|----------|--------|
| Do we save the text you select? | **No.** |
| Do we save page content or browsing history? | **No.** |
| Do we collect accounts, passwords, or payment data? | **No.** |
| Do we sell or share personal data with advertisers? | **No.** |
| Do we run analytics or tracking pixels? | **No.** |
| Does the Extension send data to Martial Systems LLC servers? | **No.** We do not operate a backend that receives your selections or pages. |
| What does the Extension access? | Text you select in the current browser session, only to keep a live multi-selection list until you copy or dismiss it. |
| What is written to disk? | Selected text is **not** written to disk. No local database. No `chrome.storage.local`. **Search browser** is on from install. If you change that preference, Chrome may persist the on/off value in `chrome.storage.sync`. |

---

### 2. Who we are

The Extension is developed and offered by **Martial Systems LLC**, an Indiana limited liability company (“we,” “us,” or “our”).

Privacy inquiries: **martialsys@gmail.com**  
Company site: **https://martialsys.net/**

---

### 3. Scope

This Policy applies only to the Extension as distributed through the Chrome Web Store (or as an unpacked build you install yourself). It does not apply to:

- Google LLC, the Chrome browser, or the Chrome Web Store platform;
- Websites you visit while the Extension is installed;
- Any third-party website or extension.

Your use of Google services and of third-party sites is governed by their respective terms and privacy policies.

---

### 4. Information the Extension processes

#### 4.1 Processed only in your browser, not saved

When you select text and choose **Select more**, the Extension may:

- Read the **text you just selected** in that tab;
- Keep those pieces in **Chrome memory** (`chrome.storage.session` and the extension service worker) so you can add more pieces on other tabs;
- Show highlights and a small box in the page;
- On **Copy**, write the joined text to **your clipboard** at your request.

This happens **on your device**. We do **not** upload selected text, URLs, or page HTML to Martial Systems LLC.

`chrome.storage.session` is **in-memory**. Chrome does not write that store to disk. The list is discarded when you press **Copy** or **Not now**, or when the Chrome session ends.

We do **not** use `chrome.storage.local` or IndexedDB for your content.

**Search browser** is on from install. You can turn it off in the toolbar popup. If you click **Search**, Chrome opens your default search engine (often Google) with the selected text. That query goes to the search provider, not to Martial Systems LLC. The on/off preference is stored in `chrome.storage.sync` so it survives a Chrome restart. It is not selected text.

#### 4.2 What we do not collect

We do not collect, upload, or keep:

- The text you select;
- Page contents, titles, or URLs as a history log;
- Names, email addresses, or contact details (except if you email us for support);
- Precise geolocation;
- Authentication credentials or payment card data;
- Advertising identifiers or cross-site tracking profiles;
- Analytics event streams.

#### 4.3 Voluntary contact

If you email **martialsys@gmail.com**, we use your message to reply. That email is outside the Extension. Optional support via [Ko-fi](https://ko-fi.com/martialgames) is a third-party site under that provider’s policies. We do not receive your selected text through Ko-fi.

---

### 5. Permissions

| Permission | Why |
|------------|-----|
| Host access to `http` and `https` pages | So the box can appear where you select text |
| `storage` | In-memory session for the live list across tabs. Sync storage only for the Search-browser on/off preference. **Not** used to save selected text to disk or to us |
| `search` | Used only when you click **Search**, so Chrome can open your default search engine. On from install. You can turn it off in the toolbar popup |

The Extension does not request identity, history, or unlimited downloads.

---

### 6. Children

The Extension is not directed at children under 13. We do not knowingly save children’s data.

---

### 7. Changes

We may update this Policy by posting a new version at the same public URL or in the Store listing. The “Last updated” date will change.

---

### 8. Contact

Martial Systems LLC  
Email: martialsys@gmail.com  
Web: https://martialsys.net/
