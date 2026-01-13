# 🖼️ Hidden Picture Challenge

An interactive web-based game where players uncover hidden images by removing a 30x30 grid of purple squares.

---

## 🚀 How to Update the Images via Git Bash

If you want to replace the current images in this repository with your own, follow these steps using Git Bash:

### 1. Navigate to your project
* Open Git Bash and move into your project folder:
```
cd /path/to/your/project
```
### 2. Delete the old images
* This clears out old files so your repository stays clean:
```
rm -rf images/
```
### 3. Add your new images
* Create a new folder named images in Windows File Explorer.
* Paste your new image files inside.

### 4. Push to GitHub
* Run these commands to sync your new images to the cloud:
```
git add .
git commit -m "Updated image library"
git push origin main
```
---
## ⚠️ Requirements for Images

*   **Naming:** Your code expects files to be named numerically (e.g., `1.png`, `2.png`, etc.).
*   **Format:** Use `.png` or `.jpg`. Note that GitHub is **case-sensitive** (if your code looks for `.png`, the file extension cannot be `.PNG`).
*   **Placeholder:** An `images/0.png` file is required for the initial reset state.
*   **Optimization:** For the best performance, keep individual image sizes under 1MB.

