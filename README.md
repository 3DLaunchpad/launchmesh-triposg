# 🚀 LaunchMesh · Image to 3D

**Free image-to-3D mesh generation for the 3D Launchpad community — powered by TripoSG.**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/3dlaunchpad/launchmesh-triposg/blob/main/LaunchMesh_TripoSG.ipynb)

---

## How it works

Each person in the community opens their **own** Colab session — they each get independent free GPU time with no shared quota. No accounts, no tokens, no waiting on others.

```
Click "Open in Colab" → Run all cells → Use the LaunchMesh UI
```

## Features

- 🎨 Full LaunchMesh UI (dark space theme, orange/blue style)
- ⚡ Runs on Google's free T4 GPU — no local hardware needed
- 🔧 Adjustable steps, guidance, simplify, and seed settings
- 📦 Downloads as `.glb` — works in Blender, Unity, Unreal, Windows 3D Viewer
- 👥 Each user gets their own independent GPU session

## Share with your community

Post this link anywhere — Discord, Skool, Reddit, YouTube description:

```
https://colab.research.google.com/github/YOUR-USERNAME/launchmesh-triposg/blob/main/LaunchMesh_TripoSG.ipynb
```

## Setup (one time)

1. Upload `LaunchMesh_TripoSG.ipynb` to a new GitHub repo
2. Get a free ngrok token at [ngrok.com](https://ngrok.com) (needed for the public URL)
3. Replace `YOUR-USERNAME` in the Colab badge link above with your GitHub username
4. Share the link!

## Output

TripoSG generates **geometry-only GLB files** (no texture). To add colour, import into Blender and use its texturing tools.

---

*By [3D Launchpad](https://www.skool.com/miless-group-4588) · Powered by [VAST-AI/TripoSG](https://github.com/VAST-AI-Research/TripoSG)*
