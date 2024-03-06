## cintel-01-interactive-Vashti-repo
## Name: Vashti Gambol
## Date: March 7th,2024

# Overview
Professional Analytics - Level 1 Professional Analytics

Contents Data Analytics Analytics Data Cleaning Analytics Data Analytics Statistics Basics Git and GitHub Git Basics GitHub Basics GitHub Repositories GitHub: Adding a File GitHub Pages Python Python Basics Python Collections Python Datasets Python Execution Python File I/O Python Functions Python Modules and Packages Python Project Organization Python Type Hints Python Standard Library Standard Library Overview Python Environment Setup Environment Setup: Jupyter Environment Setup: Virtual Environments Python External Libraries Library: Pandas and Polars Library: Pandas and NumPy Library: Matplotlib Library: Seaborn SQL SQL and Python Integration Development Tools Development Tools: Linters and Formatters Development Editor: VS Code Visual Studio Code Managing This Repository Before installing the linting tools, install Node.js on your system. Download it from the official Node.js website.

After installing Node.js, use the following commands in PowerShell to install and run Markdown linting tools:

Install markdownlint-cli and Prettier globally
npm install -g markdownlint-cli prettier

Run markdownlint on all markdown files in the directory (exclude node_modules)
markdownlint '**/*.md' --ignore node_modules

Run Prettier to check all markdown files
prettier --check '**/*.md'

Run Prettier to fix all markdown files
prettier --write '**/*.md'
