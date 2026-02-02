# Econometrics

Notes, code, and replication exercises for econometrics.

## Working with JupyterLab (Anaconda)

### 1. Open the project

```bash
cd ~/github/econometrics
```

---

### 2. Activate Anaconda environment

```bash
conda activate base
```

Make sure your terminal prompt shows `(base)`.

---

### 3. Start JupyterLab

```bash
jupyter lab
```

JupyterLab will open in your browser.
All notebooks created here are saved inside this repository.

---

### 4. Create a notebook

* JupyterLab → **New → Python 3**
* Name the notebook (e.g. `ps1.ipynb`)
* Save (`Cmd + S`)

---

### 5. Upload notebook to GitHub

After editing files:

```bash
git status
git add ps1.ipynb
git commit -m "Add or update PS1 notebook"
git push
```

---

### 6. If GitHub files were updated online

```bash
git pull
```

---

### Notes

* JupyterLab is provided by Anaconda
* Always activate conda before running Jupyter
* Git does not auto-sync; you must commit and push


