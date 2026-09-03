<div align="center">

<img src="assets/banner.png" alt="Roto Studio Banner" width="100%">

# SAM Roto Studio

**A free rotoscoping studio in Google Colab. Zero setup, clean alpha mattes.**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VirtuallyJesse/ai-rotoscoping/blob/main/sam_roto_studio.ipynb)
&nbsp;
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](#license)

</div>

---

## Demo

Raw unedited outputs.

https://github.com/user-attachments/assets/c39db68a-4684-4045-be5a-636ca106a520

> 🟦⬜⬜⬜⬜ **Very Easy:** motion blur

---

https://github.com/user-attachments/assets/0588e20e-cc41-4b0e-9632-a0a898627161

> 🟩🟩⬜⬜⬜ **Easy:** low contrast, outfit blending

---

https://github.com/user-attachments/assets/a540cbdd-04a8-45f4-b10a-a6a6a633a401

> 🟨🟨🟨⬜⬜ **Medium:** fast motion, subject and objects leaving frame

---

https://github.com/user-attachments/assets/1ba4366d-f90e-44d4-a3d7-7127aa782247

> 🟧🟧🟧🟧⬜ **Hard:** very low contrast, outfit blending, fine hair

---

https://github.com/user-attachments/assets/849dca05-af3a-45fc-84c4-0d0c6dd65462

> 🟥🟥🟥🟥🟥 **Very Hard:** low contrast, overlapping subjects

---

## Quick Start

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VirtuallyJesse/ai-rotoscoping/blob/main/sam_roto_studio.ipynb)

1. Click **Open In Colab** above
2. Run **Cell 1** to install, then **Cell 2** to launch
3. Upload your video and choose a tool
4. Download your exported alpha sequence

That's it. No local setup or terminal commands.

---

## Tools

| Tool | Best For | Workflow |
|---|---|---|
| **InSPyReNet** | Hands-off cuts for clear subjects | Upload video and click Run |
| **MatAnyone** | Quick results with manual control | Click 1 frame, then click Run |
| **SAM + ViTMatte** | Complex motion, hair, soft edges | Click subject, Track, run ViTMatte |

> 💡 Results vary by footage. Try multiple tools to find the cleanest matte. **SAM + ViTMatte** is usually the most consistent.

---

## Tutorial

<div align="center">
<a href="https://www.youtube.com/watch?v=pziVeMbTd-c">
<img src="assets/tutorial-thumb.png" alt="Watch the Tutorial" width="70%">
</a>

*Click to watch on YouTube (3 min)*
</div>

---

## SAM 3 Access

SAM 3 is supported, but Meta requires approval before downloading the model weights.

<details>
<summary><strong>How to get access</strong></summary>

<br>

1. Go to [**facebook/sam3**](https://huggingface.co/facebook/sam3) on Hugging Face  
2. Click **Agree and access repository** (free account required)
3. Select **AI researcher** and a **United States University** for fast approval
4. In Colab, provide your [**Hugging Face token**](https://huggingface.co/settings/tokens) when prompted

</details>

---

## License

[MIT](LICENSE). Use freely, attribution appreciated!

---

<div align="center">
  <a href="https://ko-fi.com/virtuallyjesse" target="_blank">
    <img src="https://storage.ko-fi.com/cdn/kofi2.png" alt="Support Me on Ko-fi" height="42" style="height: 42px;">
  </a>
  <br>
  <sub>Made with ❤️ by <a href="https://github.com/VirtuallyJesse">VirtuallyJesse</a></sub>
</div>
