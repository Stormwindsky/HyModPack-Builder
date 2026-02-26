# 🛠️ HyModPack Builder - User Guide

This tool allows you to automatically package Hytale-style modpacks by fetching files from a remote configuration. It generates a structured `.zip` file containing a root folder, a preview image, and a dedicated `mods` folder.

---

## 📋 How to use

1. **Host your files**: Upload your `.jar` mods and a `preview.png` image to a public server or cloud storage (e.g., GitHub, Discord, or a personal VPS).
2. **Create a `.hymp` file**: This is a simple JSON file (instructions below) that tells the builder what to download.
3. **Run the Builder**: 
   * Open the `index.html` file in your browser.
   * Paste the **direct URL** of your `.hymp` file.
   * Click **"Build ModPack"**.
4. **Download**: Once the process is finished, your structured ZIP file will download automatically.

---

## ⚙️ The `.hymp` Configuration Format

The builder expects a JSON structure. You must save your file with the `.hymp` extension (or `.json`) and host it online.

### Example Configuration:

Check the template here:
https://github.com/Stormwindsky/Template-Hytale-ModPack/blob/main/HYMP%20Template.hymp

---

## 📚 Credits & Libraries

This project is built using the following open-source libraries and resources:

* **[JSZip](https://stuk.github.io/jszip/)**: A powerful JavaScript library used to create, read, and edit .zip files with a lovely and simple API.
* **[Cloudflare CDN](https://cdnjs.com/)**: Used to deliver the JSZip library efficiently.
* **[Google Fonts](https://fonts.google.com/)**: Used to provide high-quality typography (Quicksand and Oswald) to match the Hytale aesthetic.
* **[Marked.js](https://marked.js.org/)**: A low-level compiler for parsing markdown without caching or blocking for long periods of time.

---

### ⚖️ License
This tool is provided "as is". When using it, ensure that the content you are packaging (mods, images) complies with the original creators' licenses and terms of service.
