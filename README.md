# WAPS Tool

**Figure Proportion Checker with Weighted Adult Proportion Score (WAPS) scoring**   
Runs entirely in the browser. No server, no uploads. Just open the page, load an image, and place landmarks.

## 🚀 Features

* **Manual mode** — Upload an image, drag the colored dots to mark head, shoulders, hips, etc.
* **Auto-place** — Uses MediaPipe Tasks Vision to guess landmark positions (face + pose detection) and seeds the markers automatically.
* **Guided mode** — Step-by-step instructions to place each landmark. The guide updates as you click or drag a point.
* **Exports** — Save landmarks as `.json` or export an annotated image as `.png`.
* **Privacy** — Everything runs locally in your browser. No image ever leaves your device.

## 📋 How to Use

1. Open the [GitHub Pages link](https://c0mm4nd3r-iv.github.io/WAPS-Tool/)
2. Click **Upload Image** and select a photo or drawing.
3. Either:

   * **Manual**: Follow the guide, drag dots into position.
   * **Auto-place**: Click the button to auto-detect landmarks, then fine-tune any dots.
4. Check results in the WAPS table. Ignored rows show `N/A`.
5. Use the **Feet visible** button if the feet are cropped out.
6. Export your results if you want to save them.

## ⚠️ Disclaimer

This tool is a **proportion estimator** only.
It is **not** an age verification or safety tool. Use responsibly.
