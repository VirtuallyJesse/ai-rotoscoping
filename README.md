<div align="center">

<img src="assets/banner.png" alt="Roto Studio Banner" width="100%">

# SAM Roto Studio

**AI-assisted rotoscoping in Google Colab. High-quality alpha mattes with no effort, saving you time.**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VirtuallyJesse/ai-rotoscoping/blob/main/sam_roto_studio.ipynb)
&nbsp;
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](#license)

</div>

---

## Demo

All outputs are **untouched** — straight from the pipeline.


> **Difficulty:** 🟦⬜⬜⬜⬜ **Very Easy**  
> **Input Conditions:** motion blur

https://github.com/user-attachments/assets/81bae046-38ae-4d5a-8eda-e7dcebfabae5

<br>

> **Difficulty:** 🟩🟩⬜⬜⬜ **Easy**  
> **Input Conditions:** low contrast, color blending

https://github.com/user-attachments/assets/17efceef-0e77-4679-9d0b-5882346972cd

<br>

> **Difficulty:** 🟨🟨🟨⬜⬜ **Medium**  
> **Input Conditions:** kinetic motion, frame-edge clipping, temporary object occlusion

https://github.com/user-attachments/assets/b36ba78d-ed49-4059-a7e2-3696ab48151f

<br>

> **Difficulty:** 🟧🟧🟧🟧⬜ **Hard**  
> **Input Conditions:** very low contrast, color blending, fine hair

https://github.com/user-attachments/assets/bcb662c7-8e7d-43ff-a9f6-048234e824cd

<br>

> **Difficulty:** 🟥🟥🟥🟥🟥 **Very Hard**  
> **Input Conditions:** low contrast, multiple objects, objects overlapping

https://github.com/user-attachments/assets/9341d4a6-b763-48a4-ab88-275ce53b240b

---

## Quick Start

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VirtuallyJesse/ai-rotoscoping/blob/main/sam_roto_studio.ipynb)

1. **Click the Colab badge** above to open the project
2. **Run both cells** to install then launch
3. **Upload your footage** and pick a tool  
4. **Download your alpha sequence** or composited result

That's it. No local setup. No terminal commands.

---

## Tools

| Tool | Best For | How It Works |
|------|----------|--------------|
| **InSPyReNet** | Salient subjects, good contrast | Fully automatic — no prompts needed |
| **MatAnyone** | More control, faster results | Single SAM prompt → auto-propagation |
| **SAM + ViTMatte** | Complex motion, low contrast | SAM tracking → edge refinement |

> 💡 **Tip:** Results vary by footage, A/B test to find the cleanest matte.  
> **SAM + ViTMatte** is typically the most consistent.

---

## Tutorial

Full walkthrough from zero to compositing.

<div align="center">
<a href="https://www.youtube.com/watch?v=pziVeMbTd-c">
<img src="assets/tutorial-thumb.png" alt="Watch the Tutorial" width="70%">
</a>

*Click to watch on YouTube (3 min)*
</div>

---

## SAM 3 Access

SAM 3 is included and fully functional, but the model weights require approval.

<details>
<summary><strong>How to get access (5 min)</strong></summary>

<br>

1. Go to [**facebook/sam3**](https://huggingface.co/facebook/sam3) on Hugging Face  
2. Click **"Agree and access repository"** (requires HF account)
3. Use **AI researcher** and a **United States University** for guaranteed form approval. (short wait)
4. In Colab, paste your [**huggingface_token**](https://huggingface.co/settings/tokens) when prompted

</details>

---

## License

[MIT](LICENSE) — use freely, attribution appreciated!

---

<div align="center">
  <a href="https://ko-fi.com/virtuallyjesse" target="_blank">
    <img src="https://storage.ko-fi.com/cdn/kofi2.png" alt="Support Me on Ko-fi" height="42px" style="height: 42px;">
  </a>
  <br>
  <sub>Made with ❤️ by <a href="https://github.com/VirtuallyJesse">VirtuallyJesse</a></sub>
</div>
