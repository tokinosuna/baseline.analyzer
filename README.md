# 萬事屋 Baseline 分析 (Baseline Analyzer)

喂！你這傢伙！還在 MDN 和 CanIUse 之間切來切去，活像個找不到工作的 MADAO 嗎？阿銀我看不下去了。

This is a simple, no-nonsense tool built for the **Baseline Tooling Hackathon**. It analyzes your code snippets in real-time to tell you if the modern web features you're using are actually safe to use, according to the official Web Platform Baseline.

---

[Link](https://tokinosuna.github.io/baseline.analyzer/)

### 諸君的問題 / The Problem

The web platform is evolving faster than Elizabeth's signs can change. There are tons of cool new CSS and JS features, but every developer faces the same annoying question: **"Can I use this yet?"**

This uncertainty is a tax on productivity. It forces us to interrupt our workflow, search through multiple documentation sites, and often leads to playing it safe with older, less efficient code.

### 萬事屋的解決方案 / The Yorozuya Solution

This analyzer cuts through the noise. Just like how a good bowl of parfait solves most of life's problems, this tool solves your compatibility woes:

1.  **貼上你的程式碼 (Paste Your Code):** No setup, no installation. Just dump your CSS or JavaScript into the box.
2.  **我們來做骯髒活 (We Do the Dirty Work):** The tool scans your code for keywords of modern features.
3.  **直通資料庫 (Direct Line to the Source):** It queries the official `api.webstatus.dev` to get the real, up-to-date Baseline status for each detected feature.
4.  **給你簡單的報告 (Get a Simple Report):** Instantly see which features are `Widely Available` (✅ Go for it!), `Newly Available` (🤔 Use with awareness), or `Limited Support` (❌ Stop!).

### 這東東有什麼酷功能？ / Key Features

*   **⚡ 即時分析 (Instant Analysis):** Get feedback as soon as you click the button.
*   **🌍 雙語支援 (Bilingual Support):** Switch between English and Traditional Chinese, because not everyone speaks the language of the aliens.
*   **🎨 主題風格切換 (Super Cool Theming):**
    *   **Pastel Dream:** A dreamy, glassmorphism default theme.
    *   **Night Mode:** For those late-night coding sessions fueled by coffee.
    *   **High Contrast:** An accessibility-focused theme for clarity.
    *   **Y2K Pixel:** A retro theme for when you feel like a 90s hacker.
*   **👓 輔助功能 (Accessibility Ready):** Includes a larger text mode and a high-contrast theme.
*   **📦 零建置步驟 (Zero-Build, All-in-One):** Everything is in a single `index.html` file. You can run it locally or deploy it anywhere in seconds.

### 怎麼用？ / How to Use

真是的，這還要教嗎？

1.  打開網站連結 (Open the website URL).
2.  把你的程式碼貼進去 (Paste your code).
3.  點擊那個大大的分析按鈕 (Click the big 'Analyze' button).
4.  (可選) 點擊右上角的齒輪，玩玩那些酷炫的設定 (Optionally, click the gear icon to play with the cool settings).

### 工具箱 / Tech Stack

This project was built with the most reliable tools known to man:

*   **Vanilla JavaScript:** No frameworks, no nonsense. Pure, unadulterated JS, just like my love for strawberry milk.
*   **HTML5 & CSS3:** The bread and butter.
*   **Web Platform Dashboard API:** The source of all our intel.

### 未來的野望 / Future Ambitions

If I ever get enough money to pay the rent, I might consider adding:

*   Analyzing entire uploaded `.css` or `.js` files.
*   A "Baseline Score" for your code.
*   A VS Code or Browser Extension version.
