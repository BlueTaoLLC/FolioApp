---
title: Folio Support
permalink: /support/
---
Folio is a native reader for Markdown, reStructuredText, text, code, PDFs, and images on iPhone, iPad, and Mac, made by BlueTao LLC. This page answers the common questions; for anything else, write to folio@bluetao.com or open an issue on Folio's support repository at https://github.com/BlueTaoLLC/FolioApp/issues.

## Getting started

Open a file with **Document** in the Open row at the bottom of the sidebar, browse a whole folder with **Folder**, or paste a GitHub file link or a direct HTTPS link with **Link**. You can also drag a file into the window or use Open With from another app. Files you open join Your Library; text is saved for offline reading, while PDFs and images are viewed from where they are. A PDF or image opened from a link is downloaded once and kept with the library.

## Reading

- The outline button jumps between headings in Markdown and reStructuredText and between bookmarks in a PDF.
- Find highlights every match in the page or PDF.
- The Settings button in the toolbar switches between light and dark, and on iPhone so does the top of the reader's ⋯ menu. Reading settings choose the appearance too, including Automatic, which follows the system, along with serif or sans-serif type, text size, line spacing, and page width. Settings → Code chooses a color scheme for code or turns coloring off.
- Settings → Sidebar sets the text size of Your Library, File Browser, and the outline, and the spacing between rows. On iPhone and iPad the sidebar also follows the text size chosen in the system's Settings app.
- Show Source reveals the document's own text. Share offers Share Source, the document as a file, and Export PDF, a paginated copy of the page; for PDFs and images it sends the file.

## Folio Plus

Complete text documents up to 10 KB read for free, and PDFs and images always do. Larger text documents show a fading preview of the first 10 KB and an invitation to unlock the rest. Folio Plus unlocks them, along with Export PDF and, on Mac, Print.

- **Folio Plus Lifetime**, $19.99 (USD), one purchase, no recurring charge.
- **Folio Plus Yearly**, $9.99 (USD) per year, renewing automatically until canceled.

Both include Family Sharing. Prices in other regions appear in the app. Buying the lifetime unlock does not cancel a subscription; cancel that in your Apple Account settings.

**Already purchased on another device?** Open the purchase screen (the Settings button in the toolbar → Folio Plus, or from the preview's invitation) and choose Restore Purchases.

**Canceling or refunds.** Subscriptions are managed in Settings → Apple Account → Subscriptions on iPhone and iPad, or in App Store → Account on Mac. Refunds are handled by Apple at reportaproblem.apple.com. Your documents stay in the library either way.

## Privacy

Everything stays on your device: documents, bookmarks, and settings. There is no account, analytics, or advertising. Opening a link contacts the site you typed. A document's images are fetched from their hosts unless Settings → Privacy → Load images from the web is off. A GitHub personal access token, if you add one, lives in the device Keychain and is sent only to GitHub. Read the full [privacy policy](../privacy/).

## Troubleshooting

**How do I start over?** The ⋯ button beside Your Library offers Clear Library, which forgets every saved copy, including PDFs and images downloaded from links, and never touches your original files. Settings ends with Reset All Settings, which returns appearance, reading, code colors, sidebar, and privacy preferences to their defaults and leaves the library, the GitHub token, and Folio Plus as they are.

**A reStructuredText page looks different from its website.** Folio renders the file itself. Whatever a documentation build assembles from other files stays out of reach: an included file shows as a one-line placeholder, a reference into another page shows its text without a link, and a version number the build supplies stays as written. Signatures, notes, code, tables, and links to PEPs, RFCs, and issues render as on the site.

**The lines at the top of a Markdown file are not all shown.** A block between `---` lines at the very top is front matter. Folio shows its title, subtitle, authors, date, and abstract as a title page and leaves out the keys meant for a site generator, such as layout and tags. Show Source displays every line.

**Part of a README's HTML is missing.** HTML inside Markdown renders for a fixed set of tags: links, images, tables, collapsible sections, alignment, and text formatting. Scripts, styles, frames, and event handlers are removed, and an image with a path relative to a local file shows its alternative text instead.

**A file is greyed out in the picker.** The picker offers text files, PDFs, and images; other binaries are greyed out. A text file with no extension, or an unfamiliar one, is greyed out there too, but the folder browser lists it because it looks at contents rather than names.

**A file is greyed out in the folder browser.** Its name says text, but its contents are not, for example a binary property list.

**"Source unavailable; showing saved copy."** The original file or website could not be reached; the saved text is shown. Reveal Source Location shows where Folio last found it. Files imported by very early versions may need reopening to reconnect their source.

**A link will not open.** Links must be HTTPS and point at a text file, a PDF, or an image. GitHub file pages are converted automatically. Private repositories need a token with read-only Contents permission under Settings → GitHub; Verify there checks it.

**Words inside a comment are colored.** The file is being read as the wrong language. `.m` files are told apart by their contents; every other file is recognised by its extension. Coloring can be turned off in Settings → Code.

**Export or Print is greyed out on Mac.** Both apply to text documents and need Folio Plus; PDFs and images are shared instead.

## Requirements

iOS 17, iPadOS 17, or macOS 14 or later. One purchase covers all three platforms through your Apple Account.
