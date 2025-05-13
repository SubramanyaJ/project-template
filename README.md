# BMSCE Project Template

Contains no nonsense LaTeX files for a BMSCE CSE project report.

## Usage

Just download the repository as a zip file and plunk it into [Overleaf](https://overleaf.com) or somewhere like that. Works for the most part.


You might also want to work locally :

### Prerequisites
* A LaTeX distribution (I used TeX Live).
* A text editor (I used Neovim).

1. **Clone this repository:**

   ```bash
   git clone https://github.com/SubramanyaJ/project-template.git
   ```

2. **Edit the `src/main.tex` file:**

   * Set the title, author, and other details.
   * Add your chapters, sections, and content.

3. **Add assets (logos, images) in the `assets/` directory:**


4. **Compile the report:**

   ```bash
   pdflatex main.tex
   # If you are using BibTeX
   # bibtex main
   # pdflatex main.tex
   # pdflatex main.tex
   ```

   This will generate the PDF (`main.pdf`).

---

## Contributing

I have only tested this on Debian 12. Contributions for Windows support are welcome.
