# Instagram Grid Slicer 🟢

A fast, 100% private, browser-based tool to perfectly slice large poster designs into Instagram-ready grid panels. 

**[🚀 Try it Live Here](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)** *(Update this link once hosted)*

## 📖 Why this tool exists
Instagram's profile grid forces every post into a **3:4 square** thumbnail. If you design a 3x1 poster and upload it normally, Instagram will chop off the edges, ruining your text and seamless artwork. 

Standard tools just slice the image into 3 equal parts. This tool intelligently handles the math and layouts, ensuring you can preview exactly how it will look in the Instagram grid before you upload.

## ✨ Features
- **100% Private:** All image processing and ZIP generation happens directly in your browser using JavaScript. Your files are *never* uploaded to a server.
- **Multi-Row Support:** Automatically detects the height of your poster and supports up to 6 rows (18 posts).
- **True Grid Preview:** See exactly how the images will stitch together on an Instagram profile.
- **Safe-Zone Cutlines:** Glowing neon cutlines show exactly where the images will split.
- **Instant Download:** Exports all panels at the exact Instagram dimensions (1012 × 1350 px) inside a neatly named `.zip` file.
- **Premium UI:** Built with a custom "Obsidian & Lime" glassmorphism design system.

## 🛠️ How to Use
1. **Design your poster:** The recommended size for 1 row is **3036 × 1350 px** (or 3036 × 2700 px for 2 rows).
2. **Upload:** Drag and drop your image into the tool.
3. **Choose Rows:** Use the dropdown to match your design (e.g., 1 Row, 2 Rows).
4. **Export:** Click **Execute Export** to download the `.zip` file.
5. **Post to Instagram:** Upload the images in order. Make sure to select the **3:4 aspect ratio** in the Instagram app!

## 💻 Tech Stack
- Vanilla HTML, CSS, JavaScript.
- Custom Glassmorphism UI & CSS Grid.
- Zero dependencies (except Google Fonts).
- No build steps, no backend, no tracking.

## 🚀 How to Host it Yourself
This tool is a single static HTML file. You can host it for free using **GitHub Pages**:
1. Fork or clone this repository.
2. Go to **Settings** > **Pages**.
3. Under "Build and deployment", set the Source to **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder.
5. Click **Save**. Your site will be live at `https://yourusername.github.io/repo-name/` in a few minutes.

## 📄 License
This project is open-source and available under the MIT License.
