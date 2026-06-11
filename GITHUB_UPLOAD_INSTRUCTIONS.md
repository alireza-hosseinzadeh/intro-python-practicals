# GitHub Upload Instructions

These are the steps to upload the practicals to GitHub.

## 1. Create a new GitHub repository

Suggested repository name:

```text
intro-python-practicals
```

Do not add a README on GitHub if you are uploading this package, because this package already contains one.

## 2. Move your notebooks into the folder

Place your student notebooks here:

```text
practicals/
```

For example:

```text
practicals/practical_1.ipynb
practicals/practical_2.ipynb
practicals/practical_3.ipynb
practicals/practical_4.ipynb
```

Place solution notebooks here:

```text
solutions/
```

For example:

```text
solutions/practical_1_solutions.ipynb
solutions/practical_2_solutions.ipynb
solutions/practical_3_solutions.ipynb
solutions/practical_4_solutions.ipynb
```

## 3. Open Anaconda Prompt, Command Prompt, or Terminal

Go to the folder:

```bash
cd path/to/intro-python-practicals
```

## 4. Initialize Git

```bash
git init
git add .
git commit -m "Add Python practical materials"
```

## 5. Connect the local folder to GitHub

```bash
git remote add origin https://github.com/alireza-hosseinzadeh/intro-python-practicals.git
```

## 6. Push the files

```bash
git branch -M main
git push -u origin main
```

## 7. Updating later

Whenever you make changes:

```bash
git add .
git commit -m "Update practical notebooks"
git push
```
