# Econometrics

Notes, code, and replication exercises for econometrics.

## How to Work with JupyterLab

### Open JupyterLab

```bash
cd ~/github/econometrics
jupyter lab
```

JupyterLab will open in the browser.
All notebooks created here are part of this GitHub repository.

---

### Sync changes to GitHub

After editing notebooks or code:

```bash
git status
git add .
git commit -m "Describe changes"
git push
```

---

### Update local files if GitHub changes

```bash
git pull
```
### Upload a Jupyter Notebook (e.g. `ps1.ipynb`)

1. Save the notebook in JupyterLab (`Cmd + S`)
2. Go to the project folder:

```bash
cd ~/github/econometrics
```

3. Upload to GitHub:

```bash
git add ps1.ipynb
git commit -m "Add or update PS1 notebook"
git push
```


