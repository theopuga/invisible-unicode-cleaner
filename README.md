# 🧹 Invisible Unicode Cleaner

**Invisible Unicode Cleaner** is a lightweight, browser-based tool that detects and removes **zero-width**, **bidi control**, **BOM**, **soft hyphen**, and other **non-printable Unicode characters** that can sneak into your text when copying from PDFs, Word documents, or the web.

Runs **100% client-side** — no data ever leaves your browser.

---

## 🚀 Features

- **Detect & remove** invisible Unicode characters such as:
  - Zero Width Space (ZWSP `\u200B`)
  - Zero Width Joiner/Non-Joiner
  - Left/Right Marks
  - Soft Hyphens
  - Bidirectional controls (`\u202A–\u202E`, `\u2066–\u2069`)
  - Byte Order Marks (`\uFEFF`)
- **Optional control character stripping**  
  Removes non-printable ASCII control codes (C0/C1) except tabs/newlines.

- **Normalization (NFC)**  
  Combines decomposed characters (like `e` + `́`) into canonical forms (`é`).

- **Highlight Invisibles**  
  Visualizes where hidden characters are in your text.

- **Import support:** `.txt`, `.md`, `.csv`, `.json`, `.docx`, `.pdf`
- **Export cleaned text**  
  Copy to clipboard or download as `.txt`.

- **Keyboard Shortcut**  
  `Ctrl / ⌘ + Enter` runs analysis — only when the text box is focused (for safety).

---

## 🧰 Installation

No installation required.

Simply **open `invisible_unicode_cleaner.html`** in your browser, or host it locally with:
```bash
python -m http.server
