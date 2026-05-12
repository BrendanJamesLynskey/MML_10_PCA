# Dimensionality Reduction with PCA

Deck 10 of the [Mathematics for Machine Learning &mdash; Companion Series](https://github.com/BrendanJamesLynskey/MML_Hub).

**Live presentation:** https://brendanjameslynskey.github.io/MML_10_PCA/

Variance-maximisation view, reconstruction-error view, eigenvectors of
the covariance, low-rank approximation, PCA in high dimensions,
probabilistic PCA, the latent-variable perspective. Interactive 2D &rarr; 1D
PCA visualiser with live principal-axis fitting.

## What's inside

- Two equivalent objectives: maximise projected variance vs minimise reconstruction error
- Why both reduce to the eigendecomposition of the covariance matrix
- The whitening / decorrelation reading
- Low-rank PCA via the SVD &mdash; works even when $D \gg N$
- Probabilistic PCA and its generative graphical model
- When does PCA fail? &mdash; non-Gaussian and non-linear structure
- Interactive 2D &rarr; 1D demo: place points and watch the principal axis snap

Companion to chapter 10 of:

> Deisenroth, M. P., Faisal, A. A. &amp; Ong, C. S. (2020). *Mathematics for Machine Learning.* Cambridge University Press. Free PDF: [mml-book.github.io](https://mml-book.github.io/).

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
