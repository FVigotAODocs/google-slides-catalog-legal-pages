# Google Slides Catalog - Privacy Policy

Last updated: February 23, 2026

This Privacy Policy explains how the Google Slides Catalog Chrome extension ("Extension") handles data.

## 1. Who We Are

Google Slides Catalog is a Chrome extension used to save, tag, and find reusable Google Slides.

Contact: francois@altirnao.com

## 2. Data We Access

When you use the Extension, it may access:

- Google account basic identity data, through Google OAuth scopes:
  - email address (`userinfo.email`)
  - basic profile (`userinfo.profile`)
- Google Slides metadata needed to retrieve thumbnails for specific slides you save/view (`presentations.readonly`)
- Extension catalog data you create:
  - slide link (Google Slides URL)
  - slide thumbnail URL
  - tags and metadata (language, customer, topics)

## 3. How Data Is Used

Data is used only to provide Extension features:

- authenticate you with your Google account
- fetch slide thumbnails from Google Slides APIs
- save and display your cataloged slides and tags
- let you edit/delete tags and saved slides

## 4. Data Storage

- Extension data is stored locally in your browser using `chrome.storage.local`.
- We do not operate a dedicated backend server for this Extension.
- We do not store your catalog data in our own remote database.

## 5. Data Sharing

We do not sell personal data.

Data is shared only with Google services as required for functionality, for example:

- Google OAuth (sign-in/token handling)
- Google Slides API (thumbnail retrieval for selected slides)

## 6. Chrome Permissions and Why They Are Needed

- `identity`: Google sign-in and OAuth token retrieval.
- `storage`: save your catalog and tags locally.
- `activeTab` and `scripting`: run the extension UI inside Google Slides pages.
- Host permission `https://docs.google.com/presentation/d/*`: operate on Google Slides deck pages where the extension is used.

## 7. Retention and Deletion

- Saved slides/tags remain in local browser storage until you edit/delete them, clear browser extension data, or uninstall the extension.
- Sign-out removes cached auth token(s) managed by the extension flow.

## 8. Security

We use Chrome extension APIs and Google OAuth to reduce direct credential handling.  
No solution is 100% secure, but we aim to minimize data access to what is necessary for the product features.

## 9. Children's Privacy

This Extension is not directed to children under 13.

## 10. Changes to This Policy

We may update this Privacy Policy over time. The "Last updated" date will reflect the latest revision.

## 11. Contact

For privacy questions or requests, contact:

francois@altirnao.com
