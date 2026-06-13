# GitHub Setup

Simple steps to upload this project to GitHub.

## 1. Clone your repo

```bash
git clone https://github.com/miqbal-id27/parking-hell.git
cd parking-hell
```

## 2. Copy the project files

Unzip the portfolio package.

Copy everything inside the extracted folder into your cloned GitHub repo folder.

Keep your existing `LICENSE` file if you already have one.

Your folder should look like this:

```text
parking-hell/
├── app.py
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
├── GITHUB_SETUP.md
├── notebooks/
├── screenshots/
└── docs/
```

## 3. Commit and push

```bash
git status
git add .
git commit -m "Add Parking Hell chatbot project"
git push
```

## 4. Optional: Enable GitHub Pages

Go to your GitHub repo:

```text
Settings → Pages → Build and deployment
```

Choose:

```text
Source: Deploy from a branch
Branch: main
Folder: /docs
```

Then click **Save**.

Your page should become:

```text
https://miqbal-id27.github.io/parking-hell/
```

Wait a few minutes after enabling Pages.
