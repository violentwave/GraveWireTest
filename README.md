# GraveWire.ai — Digital Necromancy (Single-File React on CDN)

GraveWire is a gothic, multi-model AI assistant UX prototype. It’s **one self-contained `index.html`** that runs React 18 + TypeScript (via Babel Standalone) entirely in the browser — perfect for **Replit** or a quick **GitHub Pages** demo.

> Personas: **Soul Guide** (general), **Code Wraith** (Python/JS), **Knowledge Specter** (research mode), **Phantom Automaton** (automation).  
> Screens: Persona Picker, Chat, Arcane Configuration (settings), Ethereal Archives (history).

---

## ✨ Features
- **Zero build tooling**: React/ReactDOM + Babel via CDN. No npm, no bundlers.
- **Hash routing**: `#/persona`, `#/chat`, `#/settings`, `#/archives`.
- **Local persistence**: settings + sessions in `localStorage`.
- **Voice**: Web Speech APIs (TTS) + `webkitSpeechRecognition` fallback.
- **Themes**: Gothic, Kawaii, Monochrome, High-Contrast (CSS variables).
- **Mobile-first**: drawer sidebar; sticky composer; large touch targets.
- **Marketing polish**: favicon + OG meta tags (add an `og.png` later if you want social previews).

> **Security**: Never ship private keys in client. Only public keys (e.g., Unsplash **Access** key) are OK. Keep secrets server-side.

---

## 🚀 Quick Start (Local)
1. Save this repo and open `index.html` in your browser **or** serve it:
   ```bash
   python3 -m http.server 8000
   # open http://localhost:8000
