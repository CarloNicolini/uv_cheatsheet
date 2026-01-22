## `uv` Cheatsheet

### 🛠️ Usage

To compile the PDF, you will need a LaTeX distribution (such as TeX Live or MiKTeX).

1. **Clone the repository:**
```bash
git clone https://github.com/carlonicolini/uv_cheatsheet.git
cd uv_cheatsheet

```


2. **Compile the document:**
Using `pdflatex`:
```bash
pdflatex cheatsheet.tex

```


*Note: Ensure you have the `pmboxdraw` package installed to render the directory tree symbols.*

### 📦 Prerequisites

The following LaTeX packages are required:

* `geometry`, `multicol`, `titlesec`, `enumitem`
* `tcolorbox`, `xcolor`, `hyperref`
* `pmboxdraw` (for Unicode tree characters)

### 🤝 Contributing

Found a missing command or a typo? Feel free to open an issue or submit a pull request to keep this cheatsheet up to date with the latest `uv` releases.

---

**Maintained by:** [Carlo Nicolini](https://github.com/carlonicolini)

**Inspired by:** The speed of [astral-sh/uv](https://github.com/astral-sh/uv)