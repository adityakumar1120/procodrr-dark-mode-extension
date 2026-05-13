# Procodrr Dark Mode Extension 🌙

My eyes were crying every time I opened Procodrr in light mode, so I built a simple Chrome extension that gives the site a clean dark mode by overriding its CSS variables and styles 🌙


---

## Preview
![Preview](preview.png)
---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/adityakumar1120/procodrr-dark-mode-extension.git
```

Or Click the green `Code` button on GitHub and select `Download ZIP`.

---

### 2. Open Chrome Extensions

Open:

```txt
chrome://extensions
```

---

### 3. Enable Developer Mode

Turn on:

```txt
Developer mode
```

(top-right corner)

---

### 4. Load the Extension

Click:

```txt
Load unpacked
```

Then select the project folder.

Example:

```txt
procodrr-dark-mode/
```

---

### 5. Open Procodrr

Visit:

```txt
https://procodrr.com
```

Dark mode should now be active 🎉

---

## Project Structure

```txt
procodrr-dark-mode/
│
├── manifest.json
├── content.js
├── dark.css
└── README.md
└── icons/
    ├── icon16.png
    ├── icon48.png
    └── icon128.png
```

---

## How It Works

The extension:
- Injects custom CSS into Procodrr
- Overrides the site's CSS variables
- Applies dark theme colors dynamically

---

## Development

After making changes:

1. Save files
2. Go to:

```txt
chrome://extensions
```

3. Click:

```txt
Reload
```

on the extension card.

---

## Technologies Used

- CSS
- JavaScript
- Chrome Extension Manifest V3
---

## License

MIT
