# 📟 Cyberpunk / Hacker Terminal Loading Screen

A cinematic, stylized "hacker" loading screen featuring a Matrix-style digital rain background, CRT monitor effects, and a simulated terminal boot sequence. 

This project is a single-file template perfect for landing pages, capture the flag (CTF) events, or portfolio intros.

<!-- Add a screenshot or GIF here if you have one -->
<!-- ![Demo Screenshot](path/to/screenshot.png) -->

## ✨ Features

*   **Matrix Rain Background:** A lightweight HTML5 Canvas implementation of the classic falling code effect.
*   **CRT Aesthetics:** CSS-only scanlines, screen flicker, and text glitch animations.
*   **Simulated Boot Sequence:** JavaScript-driven "typing" effect that simulates a kernel boot/hacking process.
*   **Interactive:** Users can press any key or click the button to "Skip" the sequence immediately.
*   **Responsive:** Built with Tailwind CSS to look great on mobile and desktop.
*   **Accessible:** Includes support for `prefers-reduced-motion` to disable flashing effects for sensitive users.

## 🚀 Quick Start

Since this project uses the Tailwind CSS CDN, no build step is required.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/cyberpunk-terminal-loader.git
    ```

2.  **Open the file:**
    Simply open `index.html` in your web browser.

    > **Note:** Because this uses the Tailwind Play CDN, an internet connection is required to render styles correctly.

## 🛠️ Customization

You can easily modify the look and feel by editing the `<script>` and `<style>` sections within `index.html`.

### Changing the Text Logs
Locate the `lines` array in the JavaScript section:

```javascript
const lines = [
  '[BOOT] Initiating secure environment…',
  '[OK]  Kernel modules verified',
  // Add your own custom messages here
];
