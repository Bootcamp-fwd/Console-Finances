<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>CONSOLE-FINANCES</h1>
<h3>◦ Control your cash, code your future.</h3>
<h3>◦ Developed with the software and tools below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat-square&logo=JavaScript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=flat-square&logo=HTML5&logoColor=white" alt="HTML5" />
</p>
<img src="https://img.shields.io/github/license/pmAdriaan/Console-Finances?style=flat-square&color=5D6D7E" alt="GitHub license" />
<img src="https://img.shields.io/github/last-commit/pmAdriaan/Console-Finances?style=flat-square&color=5D6D7E" alt="git-last-commit" />
<img src="https://img.shields.io/github/commit-activity/m/pmAdriaan/Console-Finances?style=flat-square&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/languages/top/pmAdriaan/Console-Finances?style=flat-square&color=5D6D7E" alt="GitHub top language" />
</div>

---

## 📖 Table of Contents
- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📦 Features](#-features)
- [📂 Repository Structure](#-repository-structure)
- [⚙️ Modules](#%EF%B8%8F-modules)
- [🚀 Getting Started](#-getting-started)
    - [🔧 Installation](#-installation)
    - [🤖 Running Console-Finances](#-running-console-finances)
    - [🌐 Live Demo Console-Finances](#-live-demo-console-finances)
    - [📸 Console-Finances Screenshot](#-console-finances-screenshot)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---


## 📍 Overview

The repository contains a simple console-based financial analysis tool. It takes a dataset of monthly profits and losses, and calculates various metrics such as total number of months, total profit/loss, average change in profit/loss, and identifies the months with the highest increase and decrease in profit/loss. Results are displayed in the console.

---

## 📦 Features

|     | Feature           | Description                                                                                                                                                 |
|-----|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ⚙️  | **Architecture**  | The codebase follows a simple structure with an HTML file (index.html) serving as the user interface and a JavaScript file (index.js) handling data processing.                                                   |
| 🔗  | **Dependencies**  | The codebase relies on HTML and JavaScript as dependencies to function.                                                                                     |
| 🧩  | **Modularity**    | The codebase is not modular, primarily consisting of two files working together.                                                                    |
| 🧪  | **Testing**       | The codebase lacks testing strategies and tools.                                                                                                            |
| ⚡️   | **Performance**   | Performance analysis is not applicable as the codebase mainly deals with calculations and does not have heavy computational or data processing requirements. |
| 🔐  | **Security**      | No security measures are implemented in the codebase.                                                                                               |
| 🔀  | **Version Control** | The repository uses Git for version control.                                                                                               |
| 🔌  | **Integrations**  | The codebase does not have any integrations.                                                                                                        |
| 📶  | **Scalability**   | The codebase lacks scalability considerations, being a small script primarily focused on financial analysis.                                               |

---


## 📂 Repository Structure

```sh
└── Console-Finances/
    ├── index.html
    └── index.js

```

---


## ⚙️ Modules

<details closed><summary>Root</summary>

| File                                                                             | Summary                                                                                                                                                                                                                                                                                                                                                     |
| ---                                                                              | ---                                                                                                                                                                                                                                                                                                                                                         |
| [index.html](https://github.com/pmAdriaan/Console-Finances/blob/main/index.html) | The code is a basic HTML file with an associated JavaScript file. The HTML file contains a title and a heading, instructing the user to open the console. The JavaScript file is included in the HTML file and will be executed when the page loads.                                                                                                        |
| [index.js](https://github.com/pmAdriaan/Console-Finances/blob/main/index.js)     | The code performs financial analysis on a dataset of monthly profits and losses. It calculates the total number of months, the sum of all profits and losses, the average change in profit/loss over the given period, and identifies the months with the greatest increase and decrease in profit/loss. The results are then printed to the console. |

</details>

---

## 🚀 Getting Started

### 🔧 Installation

1. Clone the Console-Finances repository:
```sh
git clone https://github.com/pmAdriaan/Console-Finances
```

2. Change to the project directory:
```sh
cd Console-Finances
```

3. Install the dependencies:
```sh
► N/A
```

### 🤖 Running Console-Finances

```sh
► 1. Open index.html with Live Server plugin in VS Code;
► 2. Open DevTools in your browser and check the console.
```

### 🌐 Live Demo Console-Finances
► [Console-Finances](https://pmadriaan.github.io/Console-Finances/)


### 📸 Console-Finances Screenshot

![Console-Finances Screenshot](./images/Console-Finances_screenshot.png?raw=true "Bootstrap-Portfolio")
---

## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github.com/pmAdriaan/Console-Finances/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/pmAdriaan/Console-Finances/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github.com/pmAdriaan/Console-Finances/issues)**: Submit bugs found or log feature requests for PMADRIAAN.

#### *Contributing Guidelines*

<details closed>
<summary>Click to expand</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone <your-forked-repo-url>
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear and concise message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---

## 📄 License


Copyright © 2023 Mihai-Adrian P.
This project is licensed under the `ℹ️  MIT-License`. See the [MIT License](https://github.com/pmAdriaan/Console-Finances/blob/main/LICENSE) file for additional info.

---

[**Return**](#Top)

---
