# Omar Ashraf | Portfolio

Personal portfolio website showcasing my machine learning, NLP, computer vision, and embedded systems projects.

**Live site:** https://YOUR-SITE.vercel.app *(replace with your link)*

<!-- Add a screenshot after deploying:
![Portfolio screenshot](assets/img/screenshot.png)
-->

## About

I'm a Communications and Electronics Engineering student at Alexandria University (class of 2027) and Vice Head of the ML Team at IEEE SSCS Student Branch. This site collects the projects I've built, the skills behind them, and my CV.

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| **Soundband** | Assistive device that turns speech into text for deaf users, with on-device MFCC feature extraction | ESP, Arduino, MFCC, embedded ML |
| **RECALL** | RAG chatbot that answers from your own documents | LangChain, FAISS, FastAPI |
| **Toxicity classifiers** | 15-class toxicity detection comparing BiLSTM, DistilBERT + LoRA, and Llama Guard | PyTorch, Hugging Face, FastAPI |
| **Financial manager** | Personal finance app, installable as a PWA | FastAPI, PostgreSQL, React, Docker |
| **HackerMode** | Windows lock screen that enforces daily tasks | PyQt6, Python |

## Built with

- Plain HTML, CSS, and JavaScript, with no build step and no dependencies
- Canvas-based interactive network animation in the hero section
- Responsive layout, with reduced-motion support
- Fonts: Space Grotesk and JetBrains Mono (Google Fonts)

## Project structure

```
.
├── index.html     # the whole site
├── cv.pdf         # downloadable CV
├── README.md
└── assets/        # images and media (optional)
```

## Run locally

Open `index.html` in any browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

The site is fully static, so any static host works:

1. Push this repo to GitHub.
2. Import it in [Vercel](https://vercel.com) or [Cloudflare Pages](https://pages.cloudflare.com).
3. Leave the build command empty and set the output directory to the repo root.

Every push to `main` redeploys automatically.

## Contact

- Email: oximas2004@gmail.com
- GitHub: [github.com/oximas](https://github.com/oximas)
- LinkedIn: [Omar Ashraf](https://www.linkedin.com/in/omar-ashraf-790086178/)