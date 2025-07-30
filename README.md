# Academic LaTex template

A clean, simple, and customizable LaTeX template for academic reports written in Spanish.

## Features

- Structured layout: it is split into logical files for configuration, front page, and main content.

- Pre-configured packages: it includes common packages for mathematics (`asmath`), images (`praphicx`), algorithms (`algpseudocode`) and professional tables (`booktabs`).

- Custom commands: it comes with pre-defined commands for math notations like norms (`\norm`), absolute values (`\abs`) and more.

- Spanish language support: configured with `\usepackage[spanish]{babel}` for proper hyphenation and Spanish-language text elements.

## File structure

- `main.tex`: this is the **main file** you will compile. It defines the document's overall structure and includes the other parts.

- `preamble.tex`: contains all **package imports**, custom commands, and page layout settings (like margins).

- `front_page.tex`: defines the **title**, **author**, and **date** for the tilte pages.

- `assets/`: a directory where you should place your image files.

	> The template is already configured to look for images here.
