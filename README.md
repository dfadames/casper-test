# casper-test

Interactive browser experiments & visual demos — served via **GitHub Pages**.

🌐 **Live site:** [dfadames.github.io/casper-test](https://dfadames.github.io/casper-test)

## 🧠 AI Neural Network
**ai.html** — Interactive neural network visualization. Nodes connect, fire, and learn in real-time.

## 🌌 Cosmic Nebula
**cosmic-nebula.html** — 550+ particles in an organic flow-field universe with mouse-attract, constellation connections, 5 color themes, and auto-pilot mode. Zero dependencies — pure HTML5 Canvas + vanilla JS.

## 🖥️ sysinfo
Lightweight system info tool (alternative to neofetch/screenfetch).

```bash
chmod +x sysinfo
./sysinfo
```

## Structure

```
main branch (deployed to GitHub Pages)
├── index.html           # Landing page
├── ai.html              # AI neural network demo
├── cosmic-nebula.html   # Particle universe demo
├── .nojekyll            # Skip Jekyll processing
├── README.md
└── sysinfo              # CLI system info tool
```

## GitHub Pages

This repo uses GitHub Pages from the root of the `main` branch. Any HTML file pushed to `main` is publicly served. The `.nojekyll` file ensures raw HTML is served without Jekyll processing.

To keep the published site stable, develop new features on feature branches and merge to `main` only when ready to publish.
