<div align="center">
  <a href="https://mrsanjayrajshah.github.io/gemini-watermark-remover/">
    <img src="./assets/logo.webp" alt="Gemini Watermark Remover Logo" width="120" height="120" />
  </a>
  
  <br />
  <br />

  <strong>The most powerful free Gemini Watermark Remover to instantly remove Google Gemini watermarks from AI-generated images. Also works as a Gemini Video Watermark Remover for Veo 3, Google Flow & Omni videos.</strong>
  
  <br />

  <p>
    Completely free, private, and runs 100% client-side in your web browser with zero quality loss. Uses inverse alpha compositing for pixel-perfect mathematical restoration — no blur, no AI guessing, no quality loss.
  </p>

  <a href="https://mrsanjayrajshah.github.io/gemini-watermark-remover/"><img src="https://img.shields.io/badge/🚀_Live_Demo-GitHub_Pages-6366f1?style=for-the-badge" alt="Live Demo" /></a>
  <a href="https://github.com/mrsanjayrajshah/gemini-watermark-remover/stargazers"><img src="https://img.shields.io/github/stars/mrsanjayrajshah/gemini-watermark-remover?style=for-the-badge&color=eab308" alt="GitHub Stars" /></a>
  <a href="https://github.com/mrsanjayrajshah/gemini-watermark-remover/issues"><img src="https://img.shields.io/github/issues/mrsanjayrajshah/gemini-watermark-remover?style=for-the-badge&color=10b981" alt="GitHub Issues" /></a>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License" />
</div>

<br />

## 🌐 Live Website

👉 **Try it online instantly:** [https://mrsanjayrajshah.github.io/gemini-watermark-remover/](https://mrsanjayrajshah.github.io/gemini-watermark-remover/)

---

## 💡 Why This Tool?

Most typical watermark removers use **generative AI inpainting**, which hallucinates missing pixels, leaving a blurry mess in place of the watermark. 

Google Gemini, Google Flow, Gemini Omni, and Veo models embed visible watermarks using **transparent alpha blending**. Because the underlying pixels are technically still present beneath the transparency, **Gemini Watermark Remover** uses exact mathematical unblending to subtract the watermark mask pixel-by-pixel, restoring **100% of your original image & video clarity** with zero quality loss.

$$\text{Original} = \frac{\text{Watermarked} - (\text{Logo} \times \alpha)}{1 - \alpha}$$

---

## 🚀 Features

- 🖼️ **Gemini Watermark Remover for Images:** Clean images (PNG, JPG, WebP) with instant high-resolution lossless PNG export. Supports Gemini, Imagen 3, and Nano Banana.
- 🎬 **Gemini Video Watermark Remover:** Fast frame-by-frame processing with MP4 export while preserving original audio tracks for Gemini Omni, Google Flow & Veo 3.
- 🔒 **100% Private & Client-Side:** Files never leave your device. All rendering is handled locally in your browser via HTML5 Canvas and WebCodecs.
- 🎛️ **Live Tuner & Model Presets:** Quick-select model presets alongside real-time sliders and dual zoomed comparison views.
- ⚡ **Zero Quality Loss:** Restores exact pixel colors without blurry inpainting.
- 📱 **Fully Responsive:** Beautiful, clean, modern UI optimized for desktop, tablet, and mobile browsers.
- 🆓 **Unlimited & Free:** No signups, no subscriptions, and no secondary watermarks forever.

---

## 🛠️ Tech Stack

- **Frontend Core:** Pure Semantic HTML5, Modern Vanilla CSS (Custom UI/UX Design System), JavaScript (ES6+)
- **Processing Engine:** HTML5 Canvas API, WebCodecs API, High-performance in-browser video unblending and AVC/H.264 muxing
- **Hosting Infrastructure:** GitHub Pages

---

## 💻 Local Development

Run the project locally without any dependencies using any static web server:

```bash
# 1. Clone the repository
git clone https://github.com/mrsanjayrajshah/gemini-watermark-remover.git

# 2. Navigate to project folder
cd gemini-watermark-remover

# 3. Start a local server (using Python 3, Node, or VS Code Live Server)

# Option A: Python
python3 -m http.server 8000

# Option B: Node.js (npx serve)
npx serve .
```

Open `http://localhost:8000` in your web browser.

---

## 🤝 Contributing

Contributions, issues, and feature requests are highly welcome! Feel free to check the [issues page](https://github.com/mrsanjayrajshah/gemini-watermark-remover/issues) if you want to contribute.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 💖 Support the Project

If you found the **Gemini Watermark Remover** and **Gemini Video Watermark Remover** helpful, please consider giving the repository a ⭐️ star on GitHub to help others discover it!

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="center"><i>Made with modern web APIs. Designed for privacy and mathematical precision.</i></p>
