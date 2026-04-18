<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&size=22&pause=1000&color=F1C40F&center=true&vCenter=true&width=500&lines=%F0%9F%91%87+Click+on+the+image+to+visit+my+profile" alt="Click on the image" />
</p>

[![Click on my profile](readme.png "Demo")](https://dedicateddevexpert.github.io/DedicatedDevExpert/)

# About This Project

This is my personal profile page built with pure HTML, CSS and JavaScript. It features three navigation menus, a full about page, social media links, and a contact form.

> ✅ **No installation needed!** No frameworks, no packages, no dependencies. Just open `index.html` in your browser and it works.

---

# Project Structure

```
DedicatedDevExpert/
├── index.html        # Main page with 3 menus: About Me, Projects, Contact
├── about.html        # Full profile page (skills, education, interests)
├── css/
│   ├── reset.css
│   └── style.css
├── js/
│   └── main.js
└── img/
    ├── logo.png
    └── wallpaper.jpg
```

# Features

- **About Me** — Brief bio, tech stack buttons, link to full profile and GitHub
- **Projects** — Links to GitHub repositories by category (Data Analysis, ML Models, ETL, Visualization)
- **Contact** — Social media buttons (GitHub, LinkedIn, Instagram, Twitter/X), email contact form and WhatsApp link
- **About Page** — Full profile with skills, education, certifications, interests and connect section

---

# Install

First, clone the file with the following command. Then apply the [component](https://github.com/ardacarofficial/links-website/wiki/Component-Settings "component") and [design](https://github.com/ardacarofficial/links-website/wiki/Design-Settings "design") settings. You can check the [wiki](https://github.com/ardacarofficial/links-website/wiki "wiki") for help.

```sh
git clone https://github.com/ardacarofficial/links-website.git
```

You can then upload your files to any hosting.

> ✅ **No installation needed!** This project uses pure HTML, CSS and JavaScript — no frameworks, no packages, no dependencies. Just open `index.html` in your browser and it works.

---

# Git Setup & GitHub CLI (gh)

## 1. Install Git

Download and install Git from [https://git-scm.com](https://git-scm.com), then configure your identity:

```sh
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

## 2. Install GitHub CLI (gh)

Download from [https://cli.github.com](https://cli.github.com) and authenticate:

```sh
gh auth login
```

Follow the prompts and choose **GitHub.com** → **HTTPS** → **Login with a web browser**.

---

# Main Git Commands Used in This Project

### Clone the repository
```sh
git clone https://github.com/DedicatedDevExpert/DedicatedDevExpert.git
cd DedicatedDevExpert
```

### Check the status of your files
```sh
git status
```

### Stage your changes
```sh
git add .
```

### Commit your changes
```sh
git commit -m "Your message here"
```

### Push to GitHub
```sh
git push origin main
```

### Pull latest changes
```sh
git pull origin main
```

---

# Main gh Commands Used in This Project

### Create a new repository directly from the terminal
```sh
gh repo create DedicatedDevExpert --public
```

### Open the repository in the browser
```sh
gh repo view --web
```

### Enable GitHub Pages via CLI
```sh
gh api -X POST repos/DedicatedDevExpert/DedicatedDevExpert/pages \
  --field source.branch=main \
  --field source.path=/
```

### Check repository info
```sh
gh repo view
```

---

# Note

Contributions are what make the open source community a great place to learn, inspire and create. Your contributions are greatly appreciated.

If you have a suggestion to make this better, please fork the repository and create a pull request. You can also open an issue with the "Development" tag. If you want, you can also share it in the [discussions](https://github.com/ardacarofficial/links-website/discussions/ "discussions") section. Don't forget to give stars to the project!

# License

Distributed under the MIT license. See [LICENSE](https://github.com/ardacarofficial/links-website/blob/main/LICENSE "LICENSE") file for more information.
