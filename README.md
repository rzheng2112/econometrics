# Econometrics

Notes, code, and replication exercises for econometrics.

## Workflow Guide (Anaconda + JupyterLab + GitHub)

This repository is managed with **Git**, **JupyterLab (Anaconda)**, and may be stored inside **iCloud Drive**.
Follow the steps below exactly to avoid sync issues.

---

### 1. Open the project in Terminal

```bash
cd /Users/zhengrudan/Documents/GitHub/github/econometrics
```

Confirm:

```bash
pwd
```

---

### 2. Activate Anaconda

```bash
conda activate base
```

Make sure your prompt shows `(base)`.

---

### 3. Start JupyterLab

```bash
jupyter lab
```

JupyterLab will open in the browser.
All notebooks are saved **inside this repository**.

---

### 4. Create and save a notebook

* JupyterLab → New → Python 3
* Name the file (e.g. `econ_633_ps1.ipynb`)
* Save (`Cmd + S`)

---

### 5. Upload changes to GitHub

Always run these commands **from Terminal**, not from Jupyter’s terminal.

```bash
git status
git add .
git commit -m "Describe changes"
git pull --no-rebase
git push
```

If an editor opens during `git pull` or `git commit`:

* `Ctrl + O` → Enter (save)
* `Ctrl + X` (exit)

---

### 6. If `git push` is rejected

This means GitHub has newer commits.

Fix with:

```bash
git pull --no-rebase
git push
```

---

### 7. Ignore Jupyter and macOS junk files

This repository ignores:

* `.ipynb_checkpoints/`
* `.DS_Store`

Do **not** upload them.

---

### 8. iCloud Drive note (important)

If this folder is inside iCloud Drive:

* Right-click the repo folder
* Select **“Keep Downloaded”**

Do **not** manually remove the `.git` folder from local storage.

---

### Golden rules

* Always `git pull` before starting work
* Always save notebooks before committing
* Never force-push
* Git commands only work inside the repo folder

