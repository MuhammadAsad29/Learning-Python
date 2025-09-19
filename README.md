# Description (for GitHub About)

**Short:** Hands-on Python learning labs — step-by-step Jupyter notebooks covering basics, data handling, NumPy, image handling, and mini-projects.

---

## Detailed description (for README / GitHub About)

This repository contains a curated set of Jupyter notebooks designed for someone learning Python by doing.

Highlights:

- Beginner-friendly labs covering common Python topics (indentation and errors, user input, lists & loops, OOP, NumPy).
- Practical mini-projects using real CSV files for data analysis (e.g., Titanic & Spotify sample data).
- Image-handling examples using PIL / OpenCV.
- Practice exercises to build muscle memory and confidence.

How to use:

1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/learning-python-labs.git
   cd learning-python-labs
   ```
2. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # macOS / Linux
   .venv\Scripts\activate    # Windows PowerShell
   ```
3. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch Jupyter and open a notebook:
   ```bash
   jupyter notebook notebooks/01_indentation_and_errors.ipynb
   ```

Suggested `requirements.txt` (start with these; update if any notebook uses other libraries):

```
jupyter
numpy
pandas
matplotlib
scikit-learn
opencv-python
pillow
ipywidgets
textblob
```
