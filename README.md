<!-- To see this file in a clean, formatted view, select ▼ in the upper-right corner of the editor pane, then select "Markdown Preview".-->

# STEM Standard Operating Environment

---

> [!WARNING]
> This repository is under active development and may change frequently. It is not ready for student or faculty use

---

## Overview

The **STEM Standard Operating Environment** (SOE) provides a common set of development tools and configurations for Windows, macOS, and Linux computers. Organizations use standard computing environments to reduce compatibility problems, simplify technical support, and improve collaboration. The SOE gives STEM students and faculty a consistent foundation across programs and courses while allowing individual courses to add specialized tools when needed. [Learn more](https://github.com/GC-STEM/soe/wiki/Home).

## Set up your GitHub account

**GitHub** is a widely used platform for managing code and collaborating on technical projects. A free personal account lets you store and share your work, track changes, collaborate with others, and use cloud-based development tools. Your GitHub account also provides a portfolio of projects that can demonstrate your technical skills to potential employers.

Setting up your GitHub account is the first step in preparing the STEM Standard Operating Environment (SOE) for your coursework. Start at the step that best describes your situation:

1. I don't have a personal GitHub account. [**Create a new GitHub account**](https://github.com/GC-STEM/soe/wiki/GitHub-Setup#create-a-new-github-account).

2. I already have a personal GitHub account, but haven't set it for up for STEM coursework yet. [**Configure your GitHub account**](https://github.com/GC-STEM/soe/wiki/GitHub-Setup#configure-your-github-account).

3. I already set up my personal GitHub account for STEM coursework. [**Verify your GitHub account**](https://github.com/GC-STEM/soe/wiki/GitHub-Setup#verify-your-github-account). Optionally, you may also wish to:
   - [**Apply for GitHub Education benefits**](https://github.com/GC-STEM/soe/wiki/GitHub-Setup#apply-for-github-education-benefits-optional)
   - [**Customize your GitHub profile**](https://github.com/GC-STEM/soe/wiki/GitHub-Setup#customize-your-github-profile-optional)

## Set up the SOE on your computer

Setting up the SOE on your local computer provides the tools and configurations needed for technical coursework. Using a common environment helps you spend less time installing and troubleshooting software, follow the same instructions as other students, and move between courses without repeatedly setting up your computer.

Select your operating system to follow the appropriate setup instructions:

- [**Windows**](https://github.com/GC-STEM/soe/wiki/SOE-Setup-on-Windows)
- [**macOS**](https://github.com/GC-STEM/soe/wiki/SOE-Setup-on-macOS)
- [**Linux**](https://github.com/GC-STEM/soe/wiki/SOE-Setup-on-Linux)

### Configure and Verify the SOE

**Procedure**. Click the copy icon (two squares overlapping) on the right side of the command block to copy the entire command to your clipboard. Then paste it into your terminal and press **Enter** to run the command. Follow the on-screen instructions to complete the authentication process.

```shell
git --version
gh --version
pwsh --version
python3 --version
code --version
gh auth login --clipboard --hostname github.com --git-protocol https --web
git config --global user.name "$(gh api user --jq 'if (.name | length) > 0 then .name else .login end')"
git config --global user.email "$(gh api user --jq '.id')+$(gh api user --jq '.login')@users.noreply.github.com"
gh auth setup-git
git config --global --get-regexp '^user\.(name|email)$'
```

## Clone the repository

```shell
gh api --method PUT user/starred/GC-STEM/soe
git clone https://github.com/GC-STEM/soe.git "$HOME/Repos/_shared/soe"
```

## Remote Computing Options

Remote computing options allow you to work in the **STEM Standard Operating Environment** (SOE) using a web browser, without needing to install the SOE locally. This can be especially useful if you are using a computer that is not able to install the SOE or if you want to quickly start coding from any device.

### GitHub Codespaces

GitHub Codespaces provides a full-featured development environment in your browser, preconfigured with the tools and settings needed for the SOE. You can start coding immediately without installing software locally.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/GC-STEM/soe)

### VS Code for Web

VS Code for Web allows you to edit and work on your STEM coursework directly in your browser. While it may not have all the features of GitHub Codespaces ora full local installation, it provides a convenient way to quickly access and modify your code from any device.

[![Open in VS Code for Web](https://raw.githubusercontent.com/GC-STEM/.github/refs/heads/main/.github/assets/open-in-vscode-web.svg)](https://github.dev/GC-STEM/soe)
