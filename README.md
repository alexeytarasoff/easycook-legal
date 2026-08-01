# easycook-legal

Published at <https://alexeytarasoff.github.io/easycook-legal/> and linked from the App Store and
Google Play listings, which makes these pages the privacy policy and terms as far as the stores and
anyone reading before they install are concerned.

**This repository is a mirror. Don't edit it here.** The source is `legal/` in the Easy Cook app
repository, where the wording is checked against the in-app documents
(`Sources/HelloSkip/Localization/LegalDocuments.swift`) by `HostedLegalPagesTests` — a hand-edit here
would drift from the app with nothing to catch it, which is what happened before that check existed.
Change the app repository, then copy the whole directory across.

Each page carries English, Russian and Spanish. `lang.js` picks one from the URL fragment (`#es`) or
the browser's languages; with scripting off nothing is hidden and the page reads in all three.
