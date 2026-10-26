# R2T1A Riichi Score Lab

Version: **v1.0.0**

A self-contained English/Chinese/Japanese interactive Riichi Mahjong Fu, Han and point calculator.

## GitHub Pages deployment

1. Create a **new public** GitHub repository named `riichi-score-lab`.
2. Upload `index.html`, `.nojekyll`, and `README.md` to the repository root on the `main` branch.
3. Open **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, and Save.
4. Your website URL will normally be `https://<username>.github.io/riichi-score-lab/` after GitHub Pages deploys successfully. Verify the actual published URL in the Pages settings.

## Notes

- The current scoring engine is a tested preview and has not been exhaustively validated against all Mahjong Soul scoring cases; do not claim complete accuracy.
- Tile art is embedded in `index.html` so no separate assets are required.
- This is a static client-side website; there is no backend.
- Contact information is included in the page footer.
