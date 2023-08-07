# README

## Overview

This repository contains the necessary files and folders for organizing your thesis at COMSATS University Islamabad. The main file, `Thesis.tex`, serves as the central document and contains all the components of your thesis. To ensure proper organization, follow the guidelines below for placing different types of content.

## File Structure

The repository is structured as follows:

- **Thesis.tex**: This is the main file that brings together all the components of your thesis. You should edit and compile this file to generate the final thesis document.

- **images folder**: Place all your images and graphics in this folder. Use relative paths in your LaTeX code to reference these images. For example: `images/my_figure.png`.

- **references folder**: Store your BibTeX files in this folder. Make sure to keep your references up-to-date and cite them appropriately in your `Thesis.tex` file.

- **extras folder**: Store any additional configuration files or custom styles you might need in this folder. These files should be included in the `Thesis.tex` file using relative paths.

- **chapters folder**: Organize your thesis content chapter-wise in this folder. Each chapter should be defined in its separate `.tex` file. For example, you could have `chapters/introduction.tex`, `chapters/literature_review.tex`, `chapters/methodology.tex`, etc. Remember to include these chapter files in the `Thesis.tex` file using `\input` or `\include` commands.

## Compiling the Thesis

To compile your thesis, follow these steps:

1. Make sure you have LaTeX and BibTeX installed on your system.

2. Open the `Thesis.tex` file in your preferred LaTeX editor.

3. Edit the content of the thesis according to your research and writing.

4. Include any new chapters in the `chapters` folder and reference them in the `Thesis.tex` file.

5. Cite your references using the BibTeX entries stored in the `references` folder.

6. Compile the `Thesis.tex` file using your LaTeX editor to generate the final thesis document.

## Additional Notes

- Keep the file names and folder structure consistent to avoid any potential issues with referencing files within the LaTeX document.

- Make sure to check for any packages or custom commands used in the `Thesis.tex` file and ensure they are available in your LaTeX distribution.

- If you have any questions or issues related to the organization or compilation of the thesis, feel free to contact the repository maintainers.

Good luck with your thesis writing!
