# IvanProject

A lightweight, GitHub Gist-style interactive HTML showcase page designed for GitHub Pages.

## 🌟 Features

- **GitHub Primer UI**: Authentic GitHub Gist styling with user avatar, repository breadcrumb, file badge, and timestamps.
- **Code & Live Preview Tabs**:
  - **Code Tab**: Displays formatted code with line numbers, Copy button, and Raw button.
  - **Preview Tab**: Renders the HTML in a live sandboxed `<iframe>` so anyone can view and interact with the page directly.
- **Interactive Actions**:
  - **Copy**: One-click copy code to clipboard with toast notification.
  - **Raw**: Open raw HTML in a new tab.
  - **Download**: Download snippet as `.html` directly.
- **Dark & Light Mode**: Built-in theme toggle with automatic persistence in `localStorage`.
- **Zero Build Dependencies**: Single self-contained HTML file. No npm build steps required.

## 🚀 Quick Start (Local)

To view it locally:

```bash
# Simply open in your default web browser
open index.html
```

Or run a local static server:
```bash
npx serve .
# or
python3 -m http.server 8000
```

## 🌐 Deploy to GitHub Pages

1. Commit and push the files:
   ```bash
   git add .
   git commit -m "Add GitHub Gist-style HTML showcase page"
   git push -u origin main
   ```

2. Enable GitHub Pages:
   - Go to your repository on GitHub: `https://github.com/vanyadiamant18-debug/IvanProject`
   - Navigate to **Settings** > **Pages**
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**
   - Select branch: `main` and folder: `/ (root)`
   - Click **Save**

3. Your page will be live at:
   ```
   https://vanyadiamant18-debug.github.io/IvanProject/
   ```
