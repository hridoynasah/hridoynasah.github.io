# Contributing to Hridoy Hasan's Personal Website

First off, thank you for considering contributing to my personal website! It's people like you that make the open-source community such an amazing place to learn, inspire, and create.

This repository (`hridoynasah.github.io`) hosts the source code for my personal portfolio. Since this is a static site built primarily with HTML and CSS, contributions are fairly straightforward.

## Table of Contents

- [How to Contribute](#how-to-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Submitting Pull Requests](#submitting-pull-requests)
- [Development Workflow](#development-workflow)
- [Style Guide](#style-guide)
- [License](#license)

## How to Contribute

### Reporting Bugs

If you find a broken link, a typo, or a layout issue on a specific device/browser, please let me know!

1.  Check the **Issues** tab to see if the bug has already been reported.
2.  If not, open a new Issue.
3.  Clearly describe the issue (e.g., "The navigation bar overlaps text on mobile").
4.  If possible, include screenshots or the browser version you are using.

### Suggesting Enhancements

If you have ideas for new features or design improvements:

1.  Open an Issue with the tag `enhancement`.
2.  Explain **why** this change would be beneficial.
3.  Please understand that as this is a personal portfolio, I may not accept major design changes that deviate from my personal branding, but I am open to hearing your ideas!

### Submitting Pull Requests

1.  **Fork** the repository and clone it locally.
2.  Create a new branch for your edit:
    ```bash
    git checkout -b fix/your-fix-name
    ```
3.  Make your changes.
4.  **Test your changes** locally (see [Development Workflow](#development-workflow)).
5.  Commit your changes with a clear message:
    ```bash
    git commit -m "Update hero section copy"
    ```
6.  Push to your fork and submit a **Pull Request** to the `main` branch.
7.  I will review your PR as soon as possible!

## Development Workflow

Since this is a static website, you don't need a complex build system.

1.  **Clone the repo**:
    ```bash
    git clone [https://github.com/hridoynasah/hridoynasah.github.io.git](https://github.com/hridoynasah/hridoynasah.github.io.git)
    ```
2.  **Open the site**:
    * You can simply double-click `index.html` to open it in your browser.
    * Alternatively, for a better experience (to handle relative paths correctly), use a local server like VS Code's **Live Server** extension or Python:
        ```bash
        # Python 3
        python -m http.server 8000
        ```
    * Navigate to `http://localhost:8000` in your browser.

## Style Guide

To keep the code clean and consistent, please adhere to the following simple rules:

* **HTML**:
    * Use semantic tags (`<header>`, `<nav>`, `<section>`, `<footer>`) where possible.
    * Keep indentation consistent (2 or 4 spaces).
* **CSS**:
    * Avoid inline styles; use the `assets/css` files (or wherever your styles are located).
    * Use meaningful class names.
* **Images**:
    * Ensure any new images are optimized to keep page load times low.
    * Place images in the `assets/images` folder.

## License

By contributing, you agree that your contributions will be licensed under the project's [MIT License](./LICENSE).
