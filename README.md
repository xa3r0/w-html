# w-html

**w-html** is a browser-based utility for encoding large text payloads into scannable QR code sequences using JavaScript — fully offline and privacy-preserving. It is useful for sharing long tokens, encoded strings, or base64 data via QR codes, even in restricted or disconnected environments.

---

## 🌐 Features

- No installation required — runs directly in your browser
- Fully offline and self-contained
- Encodes long strings or base64 payloads into QR code chunks
- Displays QR codes in a loop for easy scanning
- Includes optional “Graph View” layout to blend into data analysis workflows

---

## 🧩 Included Tools

| File | Description |
|------|-------------|
| `tools/base64_qr_viewer.html` | Main utility to encode base64 strings into QR chunks and display them |
| `tools/q3_graphview.html`     | Alternative visual layout that mimics a graph dashboard view |

---

## 🛠 Usage Guide

### 1. Open `base64_qr_viewer.html` in your browser

No internet required. You can double-click or open it via `file://` path in any Chromium-based browser.

### 2. Paste or drag your text into the text area

Recommended: base64-encoded text, access tokens, or long strings.

### 3. Click **"Generate QR Sequence"**

- The content will be split into chunks
- A looped QR slideshow will begin
- You can scan each frame using a QR scanner app

### 4. Optional: Use `q3_graphview.html` for stealthy presentation

This variant looks like a data visualization page and is ideal for environments where minimal visual noise is required.

---

## ✅ Browser Compatibility

- Chrome (recommended)
- Firefox
- Edge
- Brave

---

## 🔒 Notes

- All processing is done locally in your browser
- No data is sent or stored remotely
- Ideal for low-connectivity or high-privacy workflows

---

## 📂 Folder Structure
w-html/
├── README.md
└── tools/
     ├── base64_qr_viewer.html
     └── q3_graphview.html

---

## 🕶️ .v2 loading soon
*New modules are being prepped for deployment...*

---

## 📃 License

MIT License — Use freely and responsibly.

---

Made with ❤️ by xa3r0


