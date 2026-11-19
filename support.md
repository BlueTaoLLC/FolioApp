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
- A code block labelled `mermaid` is drawn as a diagram — flowcharts, sequence and class diagrams, state, entity-relationship, Gantt, pie, user journeys, Git graphs, and mind maps — on your device, with no connection.
- Links open in your browser or mail app. With a mouse or trackpad, rest the pointer on a link to see its address first.
- Show Source reveals the document's own text at the place you were reading, in the text size you chose, and Show Preview returns to the same place. Code files and Show Source number their lines; **Line numbers** in the reading settings, or under Settings → Code, hides them. Share offers Share Source, the document as a file, and Export PDF, a paginated copy of the page; for PDFs and images it sends the file.

## Folio Plus

Complete text documents up to 10 KB read for free, and PDFs and images always do. Larger text documents show a fading preview of the first 10 KB and an invitation to unlock the rest. Folio Plus unlocks them, along with editing, Export PDF, and, on Mac, Print.

- **Folio Plus Lifetime**, $19.99 (USD), one purchase, no recurring charge.
- **Folio Plus Yearly**, $9.99 (USD) per year, renewing automatically until canceled.

Both include Family Sharing. Prices in other regions appear in the app. Buying the lifetime unlock does not cancel a subscription; cancel that in your Apple Account settings.

**Already purchased on another device?** Open the purchase screen (the Settings button in the toolbar → Folio Plus, or from the preview's invitation) and choose Restore Purchases.

**Have an offer code?** Choose Redeem Code on the same screen and enter it in Apple's code sheet; Folio Plus unlocks as soon as Apple confirms it. Redeem Code is on iPhone, iPad, and Macs with macOS 15 or later. On a Mac with macOS 14, redeem the code on another device signed in to the same Apple Account, then choose Restore Purchases on the Mac.

**Canceling or refunds.** Subscriptions are managed in Settings → Apple Account → Subscriptions on iPhone and iPad, or in App Store → Account on Mac. Refunds are handled by Apple at reportaproblem.apple.com. Your documents stay in the library either way.

## Editing

With Folio Plus, **Edit** in the reader's toolbar (in the ⋯ menu on iPhone) edits a text file from your device: Markdown, reStructuredText, JSON, YAML, TOML, XML, HTML, CSS, shell scripts, Makefiles, and source code, colored as you type and indented to suit the language.

**Where are my edits?** Folio saves a moment after you stop typing. Until you choose, edits go to a new file in Folio's Edits folder (on iPhone and iPad: Files › On My iPhone or On My iPad › Folio › Edits), and the dot beside the title is red. Choose Replace the Original to save into the file itself, or Save as New File to keep a copy elsewhere; the dot turns green. The full path of each file is shown under the editor. If Folio quit before you chose, opening the document shows where the edits are, with Continue Editing.

**How do I make a new file?** Choose New in the Open row (⌘N; on Mac also File › New Document…). Give the file a name and a type, choose where it is saved, and it opens in the editor, saving into itself as you type. Like editing, it is part of Folio Plus.

**How do I undo all my edits?** Choose Restore Original… from the dot's menu while editing, or from the document's menu in the library (right-click on Mac, touch and hold on iPhone and iPad). Before Folio first saves over a file, it keeps a copy of the file as it was; restoring puts that copy back exactly. In the editor, Undo then brings your edits back. If Folio has not saved over the file yet, restoring simply discards the edits waiting in the Edits folder.

**Folio asks me to choose the file again (Mac).** Files added before editing existed were allowed to be read, not written. Choose the same file once in the panel, and Folio may save there from then on.

**Folio says the file changed elsewhere.** Another app or a sync service changed the file while you edited. Keep Mine writes your version over it, Take Theirs reloads the file, and Save as New File keeps both.

**A file can't be edited.** Folio edits UTF-8 text up to 10 MB that is on your device; a file in another encoding, such as UTF-16, can still be read. For a document opened from a link, Edit offers Download and Edit, which saves a copy where you choose and opens the copy in the editor.

## Privacy

Everything stays on your device: documents, bookmarks, and settings. There is no account, analytics, or advertising. Opening a link contacts the site you typed. A document's images are fetched from their hosts unless Settings → Privacy → Load images from the web is off. A GitHub personal access token, if you add one, lives in the device Keychain and is sent only to GitHub, with the documents you open from it and the pictures in their own repositories. Read the full [privacy policy](../privacy/).

## Troubleshooting

**How do I start over?** The ⋯ button beside Your Library offers Clear Library, which forgets every saved copy, including PDFs and images downloaded from links and the originals kept for Restore Original, and never touches your original files; the folders you gave Folio stay under Settings → Folders until you remove them there. Settings ends with Reset All Settings, which returns appearance, reading, code colors, sidebar, and privacy preferences to their defaults and leaves the library, its folders, the GitHub token, and Folio Plus as they are.

**A reStructuredText page looks different from its website.** Folio renders the file itself. Whatever a documentation build assembles from other files stays out of reach: an included file shows as a one-line placeholder, a reference into another page shows its text without a link, and a version number the build supplies stays as written. Signatures, notes, code, tables, and links to PEPs, RFCs, and issues render as on the site.

**The lines at the top of a Markdown file are not all shown.** A block between `---` lines at the very top is front matter. Folio shows its title, subtitle, authors, date, and abstract as a title page and leaves out the keys meant for a site generator, such as layout and tags. Show Source displays every line.

**A picture shows as a small frame marked Picture.** Folio shows a picture's caption and file name in its place when it may not load it. Pictures at an HTTPS address load, and so do a document's own pictures when it was opened from a link — a private repository's too, once your token is set under Settings → GitHub. A document on your device shows the pictures around it — SVG figures as well as PNG and JPEG, including those in a neighbouring folder such as `../figures/` — once Folio has a folder that holds both the document and its pictures. The system lets Folio read only what you choose, so open that folder with **Folder**, or choose **Allow Access…** in the message above the document, which starts the folder picker in the folder that holds them all. A folder given once serves every document inside it, however you open the document, and **Settings → Folders** lists those folders for removal. A picture whose file has been moved or renamed keeps the frame.

**Part of a README's HTML is missing.** HTML inside Markdown renders for a fixed set of tags: links, images, tables, collapsible sections, alignment, and text formatting. Scripts, styles, frames, and event handlers are removed. Pictures inside HTML follow the same rule as any other picture, above.

**A diagram shows as text under a Diagram label.** A code block labelled `mermaid` is drawn as a diagram. Folio keeps the source instead when the diagram's syntax cannot be read, when the free preview ends partway through it, when it has more than 300 connections, or when its source runs past 8 KB or 400 lines — limits that keep a document from stalling while you read it. Text in scripts such as Chinese takes more room per character, so a diagram written in one reaches 8 KB sooner. Nothing the author wrote is lost, and Show Source always has the original.

**A file is greyed out in the picker.** The picker offers text files, PDFs, and images; other binaries are greyed out. A text file with no extension, or an unfamiliar one, is greyed out there too, but the folder browser lists it because it looks at contents rather than names.

**A file is greyed out in the folder browser.** Its name says text, but its contents are not, for example a binary property list.

**"Source unavailable; showing saved copy."** The original file or website could not be reached; the saved text is shown. Reveal Source Location shows where Folio last found it. Files imported by very early versions may need reopening to reconnect their source.

**A link will not open.** Links must be HTTPS and point at a text file, a PDF, or an image. GitHub file pages are converted automatically. Private repositories need a token with read-only Contents permission under Settings → GitHub; Verify there checks it.

**Words inside a comment are colored.** The file is being read as the wrong language. `.m` files are told apart by their contents; every other file is recognised by its extension. Coloring can be turned off in Settings → Code.

**Export or Print is greyed out on Mac.** Both apply to text documents and need Folio Plus; PDFs and images are shared instead.

## Requirements

iOS 17, iPadOS 17, or macOS 14 or later. One purchase covers all three platforms through your Apple Account.
