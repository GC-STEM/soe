<!-- To see this file in a clean, formatted view, select ▼ in the upper-right corner of the editor pane, then select "Markdown Preview".-->

# STEM Standard Operating Environment

![Status](https://img.shields.io/badge/Status-Under%20Development-yellow)
![Platforms](https://img.shields.io/badge/Platforms-Windows%20%7C%20macOS%20%7C%20Linux-blue)
![Reference OS](https://img.shields.io/badge/Reference%20OS-Ubuntu%2024.04%20LTS-E95420?logo=ubuntu&logoColor=white)
[![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-Supported-8250DF?logo=githubcopilot&logoColor=white)](https://github.com/GC-STEM/soe/wiki/GitHub-Copilot)
![AI Agents](https://img.shields.io/badge/AI%20Agents-Supported-8250DF)
![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Supported-8250DF)
![MCP](https://img.shields.io/badge/MCP-Supported-007EC6)
[![Core Validation](https://github.com/GC-STEM/soe/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/GC-STEM/soe/actions/workflows/tests.yml)
[![Command Syntax](https://github.com/GC-STEM/soe/actions/workflows/readme-commands.yml/badge.svg?branch=main)](https://github.com/GC-STEM/soe/actions/workflows/readme-commands.yml)
[![Internal Links](https://github.com/GC-STEM/soe/actions/workflows/internal-links.yml/badge.svg?branch=main)](https://github.com/GC-STEM/soe/actions/workflows/internal-links.yml)
[![External Links](https://github.com/GC-STEM/soe/actions/workflows/external-links.yml/badge.svg?branch=main)](https://github.com/GC-STEM/soe/actions/workflows/external-links.yml)
[![Codespaces SOE](https://github.com/GC-STEM/soe/actions/workflows/codespaces.yml/badge.svg?branch=main)](https://github.com/GC-STEM/soe/actions/workflows/codespaces.yml)

---

> [!WARNING]
> This repository is under active development and may change frequently. It is not ready for student or faculty use

---

## Description

The **STEM Standard Operating Environment** (SOE) provides a common set of tools and configurations for STEM students and faculty. It supports local and remote Windows, macOS, and Linux computing environments. The SOE provides a consistent foundation across programs and courses while allowing individual courses to add specialized tools when needed. This consistency reduces compatibility problems, simplifies technical support, and improves collaboration. [Learn more](https://github.com/GC-STEM/soe/wiki/Home).

## Table of Contents <!-- omit from toc -->

1. [Description](#description)
2. [SOE Setup](#soe-setup)
3. [Remote SOE Options](#remote-soe-options)
4. [Help and Support](#help-and-support)
5. [Contributing](#contributing)

## SOE Setup

### 1. Set up your GitHub account

Setting up your GitHub account is the first step in preparing the STEM Standard Operating Environment (SOE) for your coursework. Start at the step that best describes your situation:

1. I don't have a personal GitHub account. [**Create a new GitHub account**](https://github.com/GC-STEM/soe/wiki/GitHub-Setup#create-a-new-github-account).
2. I already have a personal GitHub account, but haven't set it for up for STEM coursework yet. [**Configure your GitHub account**](https://github.com/GC-STEM/soe/wiki/GitHub-Setup#configure-your-github-account).
3. I already set up my personal GitHub account for STEM coursework. [**Verify your GitHub account**](https://github.com/GC-STEM/soe/wiki/GitHub-Setup#verify-your-github-account).
4. I have not yet applied for GitHub Education benefits. [**Apply for benefits**](https://github.com/GC-STEM/soe/wiki/GitHub-Setup#apply-for-github-education-benefits-recommended).

### 2. Set up the SOE

Setting up the SOE on your local computer provides the tools and configurations needed for technical coursework. Using a common environment helps you spend less time installing and troubleshooting software, follow the same instructions as other students, and move between courses without repeatedly setting up your computer.

Select your operating system to follow the appropriate setup instructions:

- [**Windows**](https://github.com/GC-STEM/soe/wiki/SOE-Setup-on-Windows)
- [**macOS**](https://github.com/GC-STEM/soe/wiki/SOE-Setup-on-macOS)
- [**Linux**](https://github.com/GC-STEM/soe/wiki/SOE-Setup-on-Linux)

> [!TIP]
> If you are unable to set up the SOE on your local computer before starting your coursework, skip to [**Remote SOE Options**](#remote-soe-options) for quick alternatives.

### 3. Clone the SOE repository

After setting up the SOE on your local computer, clone the repository so the SOE files are available locally.

```shell
gh api --method PUT user/starred/GC-STEM/soe
git clone https://github.com/GC-STEM/soe.git "$HOME/Repos/_shared/soe"
```

## Remote SOE Options

## Help and Support

Help is available when you need it. Start with the resources below and choose the option that best matches your question or problem.

### AI Support

Ask **GitHub Copilot** about the SOE, its tools, installation, and configuration. GitHub Copilot is available on GitHub.com, in Visual Studio Code and other IDEs, and from a terminal shell. [Learn more](https://github.com/GC-STEM/soe/wiki/GitHub-Copilot).

### Repository Resources

- **[SOE Wiki](https://github.com/GC-STEM/soe/wiki)**: Find setup instructions, configuration guidance, and troubleshooting information.
- **[SOE Discussions](https://github.com/GC-STEM/soe/discussions)**: Ask questions and share solutions about the SOE, its tools, and setup procedures.
- **[SOE Issues](https://github.com/GC-STEM/soe/issues/new/choose)**: Report installation problems, broken links, incorrect instructions, accessibility barriers, or suggestions for improving the SOE.

### University Support

- **[Brightspace](https://learn.snhu.edu)**: Contact your instructor for coursework questions, assignment requirements, grades, or deadlines.
- **[IT Service Desk](https://snhu.service-now.com/sp)**: Get help with university accounts, access, and university-provided technology.

**Important:** If a technical problem prevents you from completing coursework, notify your instructor promptly. Do not post passwords, personal information, grades, or completed assignments in public GitHub conversations.

For additional guidance, see the [GC-STEM Support Guidelines](https://github.com/GC-STEM/.github/blob/main/SUPPORT.md).

## Contributing

We welcome suggestions for improving the SOE. Students and faculty can report problems or recommend changes through [**GitHub Issues**](https://github.com/GC-STEM/soe/issues/new/choose). Pull requests are reserved for authorized repository collaborators. See the [GC-STEM Contributing Guidelines](https://github.com/GC-STEM/.github/blob/main/CONTRIBUTING.md).
