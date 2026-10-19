---
title: Folio Privacy Policy
permalink: /privacy/
---
Folio collects no data. It stores your document text, source URLs, file-access bookmarks, and reading preferences on your device, and it has no developer-operated account, analytics, advertising, or document-upload service. PDFs and images are viewed from your files where they are: Folio keeps only their location and a file-access bookmark, never a copy. A PDF or image opened from a link is the exception: Folio downloads it once and keeps that copy with the library until you remove the entry. A document opened through the folder browser shows the pictures it refers to by reading them from inside that folder, on your device; Folio reads nothing outside the folder you chose, and nothing about those pictures leaves your device. Code coloring, search, and the folder browser's look at the first bytes of each file all happen on your device. Documents never run code: HTML inside a Markdown file is reduced to a fixed set of safe tags before it reaches the page, and scripts, styles, and frames are removed.

If you add a GitHub personal access token in Settings so that private repositories can be read, Folio stores it in the device Keychain and sends it only with requests to GitHub's servers. Those requests include the pictures in a document you opened from GitHub, so that a private repository's pictures appear: Folio fetches such a document's own pictures itself, sends the token only for pictures inside that document's own repository, never for a picture anywhere else, and fetches none of them while Load images from the web is off. The token is never transmitted anywhere else, and you can remove it in Settings at any time.

When you open or refresh a remote document, Folio requests it from the source website. Remote HTTPS images, including pictures a linked document references by a relative path (they resolve to the document's own site), are requested from their hosts unless **Load images from the web** is off in Settings, in which case no document can contact an image host. Those services can receive your network address, requested URL, and normal connection information. Source URLs, including any query parameters you supply, are saved with your local document. The selected website document is checked periodically while Folio is active.

Apple processes purchases and offer code redemptions. Folio receives verified purchase and Family Sharing entitlement information from Apple's in-app purchase system so it can unlock paid features, and keeps it on the device. Folio does not receive your payment-card information. Apple's services are governed by Apple's privacy policy.

Copying places text on the system clipboard. Sharing sends the text to the destination you choose. System clipboard synchronization and device backups follow your operating-system settings and may include Folio data.

Removing a document from the library removes Folio's cached copy and saved source metadata. It does not delete the original file or copies that you previously shared or backed up.

Questions about this policy can be sent to [folio@bluetao.com](mailto:folio@bluetao.com).
