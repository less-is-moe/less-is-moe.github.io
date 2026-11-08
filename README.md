# Less is MoE project page

Static project page for https://less-is-moe.github.io/.

## Preview

Run `python3 -m http.server 8765` from this directory, then open http://localhost:8765.
No build step or package installation is required. GitHub Pages serves the root of `main`.

## Content sources

- Primary source: `assets/less-is-moe-poster.pdf`, supplied revised EMNLP 2026 poster.
- Paper: https://arxiv.org/abs/2606.05538
- Official code: https://github.com/HectorHHZ/Less-is-MoE

The text, dimension count (2.03M), benchmark values, and deployment measurements follow the supplied poster. Earlier paper and code versions use a different dimension count. The page does not combine these counts. The 50% compression ratio refers to routed-expert FFN parameters, not the whole model. Deployment measurements refer to Qwen1.5-MoE on one H100. Ratio cards show IntDim-E; the comparison tables show IntDim-G separately.

`script.js` contains the exact displayed benchmark values. Figure crops come from the supplied poster. `styles.css` contains responsive layouts and reduced-motion support. Typography uses the same system monospace stack as https://jayzou3773.github.io/: SFMono-Regular, Consolas, Liberation Mono, monospace. No external font service is required. The color palette and university logo assets come from the supplied poster. Six authors link to verified personal sites. Xingyuan Ding remains unlinked at the user’s request.
