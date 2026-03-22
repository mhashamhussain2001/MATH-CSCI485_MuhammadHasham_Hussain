# MATH/CSCI 485 — Assignment 3: Image Compression via Block-wise SVD

Explores block-wise SVD compression on a 512×512 grayscale image using 8×8 blocks, retaining the top-k singular values for k ∈ {1, ..., 8}.

## Files
- `Source_Code.ipynb` — source code, plots, and results
- `report.pdf` — full analysis and report

## Key Findings
- k=1–3 is the practical compression range (ratio > 1)
- k=4 is the crossover point where ratio drops below 1
- k=8 yields perfect reconstruction (error = 0)
