# LoreScripts
Lore Scripts — Web (.html) Story Maker

Your data is yours alone: `This is a single-file, client-side app designed to run locally in a web browser.`

This project is contained entirely within the **`index.html`** file, making it portable online/offline.

`HTML, CSS, and JavaScript.` Compiled into one.

---

## Quick Start

**Web Usage:** [xetsue.github.io/lost](https://xetsue.github.io/lost/) without downloading the file.

**Self Usage:**
1.  **Download the File:** **`index.html`**
2.  **Open:** Double-click **`index.html`** or open it using any modern web browser (Chrome, Firefox, Safari etc.).
3.  **Start Editing:** The application will load and immediately be ready for editing.

## Usage
#### **Visual Scene Builder** — Tap anything to brings up the editor to customize the site.

> 
| Control / Panel | Purpose | Interaction |
| :--- | :--- | :--- |
| **Top Controls** | Access scene settings, save data, and switch between scenes. | Click buttons like **Tabs**, **Save Scene**, **Clear Scene**, or **Reset All**. |
| **Media Panel** | Displays images, videos, or backgrounds for the scene. | **Click the panel** to open detailed settings for media content and style. |
| **Dialogue Panel** | Displays speaker name and text. | **Click the panel** to edit dialogue content and font styles. |
| **Controls Panel** | Holds interactive buttons to link to other scenes. | **Click the `+` button** to add a new option. **Click an existing button** to edit its text and target scene. |

### Saving and Loading

All scene data is saved directly in your browser's local storage.

* Click **`Save Scene`** to save the current scene's configuration and download your current scene as `.html` file.
* Note that the options will open up the next scene file.
<img width="1903" height="980" alt="image" src="https://github.com/user-attachments/assets/5c1b18cb-6fc6-4c3f-bfa5-a9de95c1a562" />


* Click **`Tabs`** to view all saved scenes and switch between them.

### Optional Local Assets

The editor supports loading media (images/videos) either from a web URL or from a local folder named `res/`.

* To use local assets, create a folder named **`res`** in the same directory as your **`index.html`** file.
* Place your image (`.jpg`, `.png`) or video (`.mp4`, etc.) files inside the `res` folder.
* In the editor settings, reference the files by name (e.g., if you upload `scene_bg.jpg` to `res/`, just enter `scene_bg.jpg` in the appropriate URL field).

---
