# Lukas Scheucher

Software engineer at [CollegeVine](https://www.collegevine.com). Lately spending most of my evenings on small language models — the kind you can train end-to-end on a single GPU and ship as a static page.

## Featured

### [ng-video-lecture](https://github.com/scheuclu/ng-video-lecture) — nanoGPT, end-to-end

A hand-extended fork of Karpathy's tiny GPT that grew into a full pipeline:

- **Training**: char + byte-level BPE tokenization with a numba-JIT'd encoder, plateau LR schedule, autosave on Ctrl-C, parallel corpus preparation
- **Inference**: depth-N width-K lookahead sampling, ONNX export with dynamic time axis
- **Observability**: Streamlit dashboard for embedding + vocabulary inspection, TensorBoard for loss curves and per-eval sample text
- **Deploy**: [live demo on GitHub Pages](https://scheuclu.github.io/ng-video-lecture) — a 42 MB ONNX model running fully client-side via ONNX Runtime Web (WebGPU / WASM SIMD), with a service worker injecting COOP/COEP headers so SharedArrayBuffer works on github.io

Everything from "train a transformer" to "serve it as a static webpage" sits in one repo and runs from `uv run …` commands.

## Tech I reach for

PyTorch · ONNX Runtime Web · numba · Streamlit · uv · GitHub Actions · TypeScript

## Contact

[lukas.scheucher@collegevine.com](mailto:lukas.scheucher@collegevine.com)
