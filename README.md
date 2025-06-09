<div align="center">
  <img src="assets/upwork.svg" alt="BitByteLab Logo" height="100">
 

**Upwork API Automation Toolkit for Freelancers**  
Automate and streamline your Upwork freelancer workflow using the Upwork API directly from the terminal.

[![Release](https://img.shields.io/github/v/tag/rsmahmud/upwork-cli)](https://github.com/rsmahmud/upwork-cli/tag)
[![Platforms](https://img.shields.io/badge/platform-windows%20%7C%20macOS%20%7C%20linux-blue)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![PyPI](https://img.shields.io/badge/PyPI-upwork-cli-lightgrey.svg)](https://pypi.org/project/upwork-cli)

</div>

Upwork API Automation Toolkit for Freelancers
=============================================

This Python package helps Upwork freelancers automate their daily workflows using the official Upwork API. It is designed to boost efficiency and reduce manual effort by providing programmable access to common tasks and events on the platform.

Features:
- Fetch and display public reviews from your Upwork profile for your personal portfolio
- Set up real-time alerts for:
  - New messages from clients with active contracts
  - Invitations to interview
  - General inbox messages
- Periodically scan job posts using custom filter logic and notify you with relevant links
- Retrieve and monitor personal data such as:
  - Earnings
  - Work diary
- Automate common actions via the command line

Whether you're an experienced freelancer or just starting out, this tool helps you stay responsive, informed, and efficient — all while remaining compliant with Upwork’s terms of service.

---
Setup Requirement
=================

1. Get an API Key from upwork https://www.upwork.com/developer/keys/apply
2. Set an environment variable `export UPWORK_API_KEY=<your-upwork-api-key>`
2. Set an environment variable `export UPWORK_API_SECRET=<your-upwork-api-secret>`
3. Install this package from pypi `pip install upwork-cli`

---
Usage
=====

`upwork-cli` or `upcli` can be used to run this tool from terminal.

use `upcli --help` to view the available options and commands.

---
## 🧪 Project Structure

<pre>
<!-- dir-tree-start -->
📁 upwork-cli/
├── 📁 src/
│   └── 📁 upwork_cli/
│       ├── __init__.py
│       ├── __main__.py
│       ├── __init__.py
├── 📁 examples/
│   └── sample_usage.py
├── 📁 tests/
│   └── test.py
├── ⚙️ .env
├── 🚫 .gitignore
├── 📃 LICENSE
├── 📃 LICENSE.txt
├── ⚙️ pyproject.toml
├── 📝 README.md
└── ⚙️ ruff.toml
<!-- dir-tree-end -->
</pre>

---

## 📄 License

Licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing

- Open an issue for ideas, bugs, or suggestions.
- Pull requests are welcome!

---

## 🔗 Links

- 📦 [PyPI](https://pypi.org/project/upwork-cli)
- 🛠️ [Issues](https://github.com/rsmahmud/upwork-cli/issues)
- ⭐ [Star on GitHub](https://github.com/rsmahmud/upwork-cli)

---


