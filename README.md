<div align="center">

# Zumyx

### Image, Video & Audio Editor

**Create. Enhance. Convert. All in One Place.**

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D4?logo=windows&logoColor=white)
![Interface](https://img.shields.io/badge/Interface-PySide6-41CD52)

</div>

---

## About Zumyx

**Zumyx** is a desktop application designed to simplify image, video, and audio editing. It brings together practical editing tools and AI-powered features in one modern interface, helping you enhance, optimize, edit, and convert your multimedia files without switching between several programs.

## Features

### 🖼️ AI-Powered Image Editing

- **Remove backgrounds** automatically with AI.
- **Erase unwanted objects** from images using intelligent reconstruction.
- **Enhance and upscale images** with Real-ESRGAN.
- Improve image quality while keeping the original dimensions.
- **Resize and convert** images between PNG, JPEG, and WebP.
- See the difference with an interactive **before-and-after slider**.
- Drag and drop images into the editor.

### 🎬 Video Optimization & Conversion

- Compress videos with adjustable quality settings.
- Convert video files to **MP4, MKV, WebM, and AVI**, or export audio as **MP3**.
- Support **H.264 and H.265 (HEVC)** encoding in video optimization workflows.
- Choose output resolutions including **4K** and vertical video formats.
- Download and convert media from supported URLs with yt-dlp.
- Take advantage of supported hardware acceleration when available.

### 🎵 Video & Audio Editing

- Trim video and audio clips with an interactive timeline.
- Preview your media before exporting.
- Change video resolution and bitrate.
- Remove audio tracks from videos.
- Edit audio metadata, including title, artist, album, track, and genre.

## 📸 Screenshots and Demo

Screenshots and demonstration videos can be added here to show the Zumyx interface and its features.

To add a screenshot, upload an image as `assets/zumyx-preview.png` and add this line to the README:

```markdown
![Zumyx interface](assets/zumyx-preview.png)
```

## 🛠️ Technologies

| Technology | Purpose |
| --- | --- |
| [Python](https://www.python.org/) | Application language |
| [PySide6](https://doc.qt.io/qtforpython-6/) | Desktop graphical interface |
| [Pillow](https://python-pillow.org/) | Image processing |
| [rembg](https://github.com/danielgatis/rembg) | AI background removal |
| [LaMa](https://github.com/advimman/lama) | AI object removal |
| [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) | AI image upscaling |
| [FFmpeg](https://ffmpeg.org/) | Video and audio processing |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | Supported media URL downloads |
| [ONNX Runtime](https://onnxruntime.ai/) | AI model inference |

## 🚀 Running From Source

> The application requires more than Python packages: `theme.py`, FFmpeg, and compatible external AI tools/models are needed for their respective features. The source code and these assets are not yet included in this repository.

### 1. Clone the repository

```bash
git clone https://github.com/FranciscoBPinto/Zumyx.git
cd Zumyx
```

### 2. Install Python dependencies

Use Python 3.10 or newer, then run:

```bash
python -m pip install -r requirements.txt
```

### 3. Provide runtime files

The current Windows source expects a structure similar to:

```text
Zumyx/
├── Zumyx.py
├── theme.py
├── ffmpeg.exe
├── RealESRGAN/
│   ├── realesrgan-ncnn-vulkan.exe
│   └── models/
├── Lama/
│   └── lama_fp32.onnx
└── u2net/
```

External binaries and model files should be obtained from their official projects according to their licenses. An optional `logoZumyx.ico` can be added beside the Python script.

### 4. Launch the app

```bash
python Zumyx.py
```

## ✨ Why Zumyx?

Whether you're creating content, editing photos, optimizing videos for sharing, or converting media files, Zumyx offers useful tools in one convenient desktop application.

## 🙏 Acknowledgements

Zumyx builds on open-source projects including **Real-ESRGAN**, **rembg**, **LaMa**, **FFmpeg**, and **yt-dlp**. Many thanks to their creators and contributors.

External tools and models may have separate licenses. Review their terms before redistributing them.

---

<div align="center">

**Zumyx — Create. Enhance. Convert. All in One Place.**

</div>
