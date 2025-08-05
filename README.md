# CMM307- Advanced Artificial Intelligence 
## Aida Ovalle Filippova (2006512), July, 2025

Repository for my CMM307 Advanced Artificial Intelligence Coursework.

It contains a Google Colab Notebook and the research paper from which I implemented an algorithm.

Dataset Link: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews?resource=download

Paper Link: https://arxiv.org/pdf/1412.1058v2

---

## NOTES:
### (For reproducibility)
When using this notebook for the first time (if getting errors like `ValueError: numpy.dtype size changed`), follow these steps:

1. Go to the `INSTALL_DEPENDENCIES` cell at the top.
2. Set `INSTALL_DEPENDENCIES = True`.
3. Run that cell to install the correct versions of packages.
4. Restart the runtime (Runtime > Restart runtime).
5. Set `INSTALL_DEPENDENCIES = False` again.
6. Run all cells from the top.
7. It should all run smoothly now.

---

### Compatible versions:
- `gensim==4.3.1`
- `numpy==1.23.5`
- `scipy==1.10.1`
