# ⌨️ 3D Wikipedia Speed Typer

## 🌐 Project Overview
This project is a feature-rich, web-based typing speed test application that provides an engaging and customizable environment for practicing typing skills. It combines visual flair (3D buttons and Dark Mode) with dynamic content fetched live from the internet.

---

## ✨ Key Features

* **Dynamic Content:** Fetches clean, short English excerpts from random **Wikipedia articles** for continuous, fresh typing tests.
* **Continuous Flow:** Automatically loads a new sentence instantly upon completion, allowing the user to type continuously until the timer expires.
* **Typing Game Logic:** Tracks user input against the target text, highlighting correct characters (theme color) and errors (red). Calculates final **Words Per Minute (WPM)** and **Accuracy**.
* **Interactive 3D Keyboard:** Virtual keys are styled with a unique 3D press effect.
* **Full Synchronization:** Keys depress visually upon mouse click or physical keyboard press.
* **Custom Audio Feedback:** Includes distinct sound effects for:
    * `click` (Letters, Backspace, Caps)
    * `space` (Spacebar)
    * `enter` (Enter/Return)
    * `finish` (Time's Up)
* **Custom Controls:** Includes a **Dark Mode toggle**, an adjustable **Volume Slider**, and a customizable **Test Duration** setting.

---

## 🛠️ Setup and Requirements

This project is built using pure HTML, CSS, and JavaScript.

### Required Files
For the application to function correctly, the following files **must** be placed in the same directory as your `index.html`:

| Filename | Purpose |
| :--- | :--- |
| **`click.wav`** | Standard key press sound |
| **`enter.wav`** | Enter key press sound |
| **`enter1.wav`** | Spacebar key press sound |
| **`finish.wav`** | Game Over / Result sound |

### Running Locally

1.  Save the entire project code as **`index.html`**.
2.  Ensure the four audio files listed above are in the same folder.
3.  Open **`index.html`** directly in your web browser.

---

## 🚀 Deployment (GitHub Pages)

This project is perfectly suited for free hosting via GitHub Pages.

1.  **Initialize Git:** Open your terminal and navigate to the project folder.
    ```bash
    git init
    git add .
    git commit -m "feat: Add full typing test application"
    ```
2.  **Push to GitHub:** Create a new repository on GitHub and push your local files to the remote repository.
3.  **Activate Pages:** In your repository on GitHub, go to **Settings > Pages**. Select your main branch (`master` or `main`) as the deployment source and save.
4.  Your site will be live at `https://<YOUR-USERNAME>.github.io/<REPO-NAME>/` within minutes.
