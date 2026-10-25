# Change Log - PRD

What the iRead product promises, release by release: which features, screens, and reader scenarios each PRD change touches, and why the decision was made. The wording of each change is in the PRD files and in `git log`.

Format based on [Keep a Changelog](https://keepachangelog.com/). Versions use Simplified Semantic Versioning (`MAJOR.MINOR`), adapted from [Semantic Versioning](https://semver.org/): **MAJOR** when scope or a flow changes enough that someone has to re-learn it, **MINOR** when screens, scenarios, fields, or copy change inside a flow that still reads the same.

**How to read a row**

- **Version**: the PRD release.
- **Impacted Features**: the product capabilities this release touches.
- **Impacted Screen**: the screens by their names in the PRDs. `-` when only a rule changed.
- **Impacted Scenarios**: what a reader can now do, with the actor in front.
- **Changes Description**: the decisions and their reasons, grouped under Added, Changed, Removed, and Clarified.
- **Date & Time**: local time (WIB) of the release.
- **Author**: the person who decided the change.

| Version | Impacted Features | Impacted Screen | Impacted Scenarios | Changes Description | Date & Time | Author |
|---|---|---|---|---|---|---|
| **1.0** | • **Library & Book Ingestion**<br>• **Reference Passage**<br>• **Symbols** | Central Library; Reading Page; Reference Card; Symbol Pop up; Symbol Control Panel | Reader imports a DRM-free EPUB and reads it right away; Reader continues from the last read position; Reader taps a descriptive phrase and reads the author's passage that explains it; Reader jumps to that passage and back; Reader turns symbols on and recognizes a character mentioned by description; Reader changes a character's symbol and saves or cancels | **Added**<br>• Epic 1 (PRD 1.0 to 1.3): readers import a DRM-free EPUB through the document picker, find it in a central library, and pick up where they left off from a Continue reading card. Every reference feature needs the book in the app as structured text first.<br>• Epic 2 (PRD 2.1): readers tap an underlined Character, Setting, or Event phrase, see the author's own passage that explains it best, and can jump there and back. Desk research on aphantasia.com showed that these readers skim descriptions, then flip back page by page to find who or what is meant.<br>• Epic 3 (PRD 3.1): once the reader turns on the Symbols toggle, each character has a symbol next to the name and next to appearance descriptions. Symbols are off by default. Tapping a symbol opens a pop up, where the reader edits the shape, icon, and color and then saves or cancels.<br>• No spoilers: cards and symbols use only text at or before the reader's position. A description keeps its own symbol until the book reveals who it is.<br>• iRead generates no images or summaries. After the desk research we dropped our first assumption that readers with aphantasia need visual imagery to enjoy fiction. | 2026-10-25 10:51 | AbrMac |
