# Lecture 2: NumPy and pandas

Data Science and Machine Learning for Geoscientists  
Academic year: 2026–27  
Lecturer: Samaneh A. Mofrad

## About this lecture

We introduce NumPy and pandas for working with numerical arrays
and tabular data, using examples from geoscience.

## Learning materials

1. Start with [Lecture 2: NumPy and pandas](01-Numpy-and-Pandas.ipynb).
2. For additional practice, explore [Optional: Reindexing](02-Optional-Reindexing.ipynb).


## How to download the materials

You have two options:

1. **Download ZIP** — a straightforward way to download the materials.
2. **Use Git** — download the materials once, then retrieve updates
   without downloading the whole repository again.

You do not need a GitHub account to download this public repository
using either option.

### 1. Download ZIP

1. Click the green **Code** button near the top of this repository.
2. Select **Download ZIP**.
3. Extract (unzip) the downloaded folder.
4. Open JupyterLab or Jupyter Notebook on your computer.
5. Navigate to the extracted folder and open the lecture notebook.

Keep the notebook and its supporting folders together so that
images and file links work correctly.

You now have a local copy and can run and edit the notebooks
on your computer.


### 2. Use Git

Git must be installed on your computer for this option.
If Git is not already installed, follow the [Git installation instructions](https://git-scm.com/install/) and select your operating system (Windows, macOS or Linux).

1. Click the green **Code** button near the top of this repository.
2. Select **HTTPS** and copy the repository link shown there.
3. Open a terminal in the location where you want to store the materials.
4. Type `git clone`, add a space, and paste the copied link:

   ```bash
   git clone PASTE_THE_COPIED_LINK_HERE
   ```

   Replace `PASTE_THE_COPIED_LINK_HERE` with the link you copied.

5. Press **Enter**. Git will create a folder containing the materials.
6. Open JupyterLab or Jupyter Notebook, navigate to that folder,
   and open the lecture notebook.

You now have the materials on your computer and can work locally.
An internet connection is needed to download updates, but not for
ordinary notebook exercises using the supplied local data.

### Getting updates with Git

If the materials in the repository is changed, you do not need to download everything again.

Open a terminal **inside the cloned repository folder**.

To check for updates without changing your working files, run:

```bash
git fetch
git status
```

`git fetch` retrieves information and changes from GitHub without
applying them to your working files. `git status` then shows your
local changes and whether your branch is behind the downloaded updates.

To apply the updates, run:

```bash
git pull
```

You can also run `git pull` directly without checking first.
If there are no updates, Git will report **Already up to date**.

These commands apply only to a folder created using `git clone`,
not to a folder downloaded as a ZIP.

### Keeping your exercise answers

Before starting the exercises, make a copy of the notebook in the
same folder and give it a different name, for example:

`01-Numpy-and-Pandas-my-answers.ipynb`

Work in this personal copy and keep the original notebook unchanged.
This helps avoid conflicts when retrieving updates.

Updates will apply to the original course files; they will not
automatically change your personal notebook copy.


## Getting help

If you get stuck, ask the lecturer or a GTA.
Making mistakes and discussing them is part of learning.

## Acknowledgements

These materials build on resources developed by previous lecturers
and contributors to the Data Science and Machine Learning for
Geoscientists course at Imperial College London.
