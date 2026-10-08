# FLORE-AE Audio Examples

Demo page for **FLORE-AE: Rethinking Audio Autoencoding with Waveform Diffusion Decoders**.

The page includes audio reconstruction, text-to-audio generation, audio editing, spectrogram comparisons, and results reported in the paper.

## Preview locally

Run `python3 -m http.server 8000` from this directory, then open <http://localhost:8000>.

## GitHub Pages

This is a static website with no build step. In the repository's **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save. The `.nojekyll` file enables direct serving of the included assets.

`data.js` contains the data used by the page; `data.json` stores the same data as JSON. Keep both files in sync when updating examples.
