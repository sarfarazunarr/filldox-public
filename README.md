# FillDox - Automated Document Generator

![Downloads](https://img.shields.io/github/downloads/sarfarazunarr/filldox-public/total)

FillDox is a powerful, user-friendly desktop application designed to automate the creation of Word documents. By using simple templates with placeholders, you can generate hundreds of customized documents (like invoices, contracts, letters) in seconds.

<p align="center"><img src="logo2.png" alt="FillDox Screenshot" width="200" /></p>

## Features

*   **Simple Template Syntax**: Use `[Tag]` for variables and `[REPEAT list]...[/REPEAT]` for loops directly in your Word documents.
*   **Style Preservation**: Maintains your document's original formatting (bold, colors, fonts) during generation.
*   **Bulk Generation**: Generate multiple documents at once.
*   **Library Management**: Built-in library to browse and manage your generated files.
*   **Auto-Update**: Automatically checks for updates and installs the latest version.
*   **Dark Mode**: Sleek, modern dark interface.

## Installation

1.  Go to the [Releases](https://github.com/sarfarazunarr/filldox-public/releases) page.
2.  Download the latest `FillDox.exe`.
3.  Run the executable.
4.  On first run, you will be asked to select a folder where your `templates` and `generated_docs` will be stored.

## Usage Guide

### 1. Creating a Template
Create a standard Word document (`.docx`) and use the following syntax:

*   **Variables**: Enclose variable names in square brackets.
    *   Example: `Hello [Name], your balance is [Balance].`
*   **Loops (Lists)**: Use `[REPEAT list_name]` to start a loop and `[/REPEAT]` to end it. Use `[item]` or `[item.property]` inside.
    *   Example:
        ```text
        Items Purchased:
        [REPEAT items]
        - [item.name]: $[item.price]
        [/REPEAT]
        ```

### 2. Generating Documents
1.  Open FillDox.
2.  Click **Templates** in the sidebar.
3.  Click on a template card.
4.  Fill in the form fields that appear.
    *   For lists, you can add multiple items dynamically.
5.  Click **Generate**.
6.  Your document will be saved in the `generated_docs` folder.

### 3. Managing Files
*   Go to the **Library** tab to browse all your generated documents organized by template.
*   Click **Open** to view a file in Microsoft Word.

## Disclaimer

Modifying or altering the `FillDox.exe` file is strictly at your own risk. Any unauthorized modification or tampering with the executable may lead to software instability and could result in legal issues.



