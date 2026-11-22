<!-- To see this file in a clean, formatted view, select ▼ in the upper-right corner of the editor pane, then select "Markdown Preview".-->

# STEM Standard Operating Environment

---

> [!WARNING]
> This repository is under active development and may change frequently. It is not ready for student or faculty use

---

The **STEM Standard Operating Environment** (SOE) provides a common set of development tools and configurations for Windows, macOS, and Linux computers. Organizations use standard computing environments to reduce compatibility problems, simplify technical support, and improve collaboration. The SOE gives STEM students and faculty a consistent foundation across programs and courses while allowing individual courses to add specialized tools when needed. [Learn more](https://github.com/GC-STEM/soe/wiki/Home).

## Table of Contents <!-- omit from toc -->

1. [GitHub Setup](#github-setup)
2. [SOE Setup](#soe-setup)
3. [Remote Computing Options](#remote-computing-options)
4. [Help and Support](#help-and-support)
5. [Contributing](#contributing)

## GitHub Setup

**GitHub** is a widely used platform for managing code and collaborating on technical projects. A free personal account lets you store and share your work, track changes, collaborate with others, and use cloud-based development tools. Your GitHub account also provides a portfolio of projects that can demonstrate your technical skills to potential employers.

Setting up your GitHub account is the first step in preparing the STEM Standard Operating Environment (SOE) for your coursework. Start at the step that best describes your situation:

1. I don't have a personal GitHub account. [**Create a new GitHub account**](https://github.com/GC-STEM/soe/wiki/GitHub-Setup#create-a-new-github-account).

2. I already have a personal GitHub account, but haven't set it for up for STEM coursework yet. [**Configure your GitHub account**](https://github.com/GC-STEM/soe/wiki/GitHub-Setup#configure-your-github-account).

3. I already set up my personal GitHub account for STEM coursework. [**Verify your GitHub account**](https://github.com/GC-STEM/soe/wiki/GitHub-Setup#verify-your-github-account).

## SOE Setup

Setting up the SOE on your local computer provides the tools and configurations needed for technical coursework. Using a common environment helps you spend less time installing and troubleshooting software, follow the same instructions as other students, and move between courses without repeatedly setting up your computer.

Select your operating system to follow the appropriate setup instructions:

- [**Windows**](https://github.com/GC-STEM/soe/wiki/SOE-Setup-on-Windows)
- [**macOS**](https://github.com/GC-STEM/soe/wiki/SOE-Setup-on-macOS)
- [**Linux**](https://github.com/GC-STEM/soe/wiki/SOE-Setup-on-Linux)

> ![TIP]
> If you are unable to set up the SOE on your local computer before starting your coursework, skip to [**Remote Computing Options**](#remote-computing-options) for alternative solutions.

### Clone the repository

After setting up the SOE on your computer, you can clone the repository so the SOE files are available locally.

```shell
gh api --method PUT user/starred/GC-STEM/soe
git clone https://github.com/GC-STEM/soe.git "$HOME/Repos/_shared/soe"
```

## Remote Computing Options

**Remote Computing Options (RCOs)** let you access development tools or edit code through a web browser without installing the SOE on your computer. They are especially useful when your computer cannot run the required software, you are away from your usual computer, or you need temporary access to your coursework.

The options below offer different capabilities. **University-provided environments are the only recommended option for course-long remote computing.** The other options are intended for temporary or limited use.

### University-Provided Environments

The university provides remote computing environments for many STEM courses, such as **Codio Virtual Desktop**. These environments include the software and configurations needed for your course, helping you complete assignments without installing software on your computer. They also provide a common setup that instructors and technical support teams can help troubleshoot.

**When to use:** Recommended for regular coursework throughout the term, especially if your computer cannot run the required software.

**Get started:** Check your [Brightspace](https://learn.snhu.edu) course under **Course Menu > Learning Modules**, particularly **Start Here**. If you cannot find a remote environment, ask in your course's **General Questions** discussion.

### GitHub Codespaces

**GitHub Codespaces** provides a cloud-based development environment with VS Code, a terminal, and tools for running and testing code. When launched from the SOE repository, it uses the repository's development environment configuration. Unlike a local installation, the computing work happens on GitHub's servers. [Learn more](https://github.com/features/codespaces).

**When to use:** As a temporary backup when your usual computing environment is unavailable or when you need to run code from another computer.

**Requirements:** A personal GitHub account is required. Free monthly usage is included, but limits apply, and additional usage may incur charges. Students and faculty can [apply for GitHub Education benefits](https://github.com/settings/education/benefits) for increased allowances.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/GC-STEM/soe)

### VS Code for the Web

**VS Code for the Web** is a free, browser-based code editor that lets you view and edit GitHub repository files without installing software. Unlike Codespaces, it does not provide a terminal or a computing environment for running and testing programs. [Learn more](https://code.visualstudio.com/docs/remote/vscode-web).

**When to use:** To quickly review or make small changes to code and other files, especially when you do not need to run or test a program.

**Requirements:** No installation is required. You can view public repositories without a GitHub account, but saving changes to GitHub requires signing in and having permission to modify the repository.

[![Open in VS Code for Web](https://raw.githubusercontent.com/GC-STEM/.github/refs/heads/main/.github/assets/open-in-vscode-web.svg)](https://github.dev/GC-STEM/soe)

## Help and Support

Help is available when you need it. Start with the resources below and choose the option that best matches your question or problem.

### GitHub Resources

- **[SOE Wiki](https://github.com/GC-STEM/soe/wiki):** Find setup instructions, configuration guidance, and troubleshooting information.
- **[Discussions](https://github.com/GC-STEM/soe/discussions):** Ask questions and share solutions about the SOE, its tools, and setup procedures.
- **[Issues](https://github.com/GC-STEM/soe/issues/new/choose):** Report installation problems, broken links, incorrect instructions, accessibility barriers, or suggestions for improving the SOE.
- **[GitHub Copilot](https://docs.github.com/en/copilot):** Get AI-assisted help understanding commands, explaining errors, and troubleshooting code. Check its suggestions and follow your course's AI-use rules.

GitHub Copilot icon ![GitHub Copilot](https://raw.githubusercontent.com/primer/octicons/main/icons/copilot-24.svg)

[![Open in VS Code for Web](https://raw.githubusercontent.com/GC-STEM/.github/refs/heads/main/.github/assets/copilot-24.svg)](https://github.dev/GC-STEM/soe)

### University Support

- **[Brightspace](https://learn.snhu.edu):** Contact your instructor for coursework questions, assignment requirements, grades, or deadlines.
- **[IT Service Desk](https://snhu.service-now.com/sp):** Get help with university accounts, access, and university-provided technology.

**Important:** If a technical problem prevents you from completing coursework, notify your instructor promptly. Do not post passwords, personal information, grades, or completed assignments in public GitHub conversations.

For additional guidance, see the [GC-STEM Support Guidelines](https://github.com/GC-STEM/.github/blob/main/SUPPORT.md).

## Contributing

We welcome suggestions for improving the SOE. Students and faculty can report problems or recommend changes through [**GitHub Issues**](https://github.com/GC-STEM/soe/issues/new/choose). Pull requests are reserved for authorized repository collaborators. See the [GC-STEM Contributing Guidelines](https://github.com/GC-STEM/.github/blob/main/CONTRIBUTING.md).
