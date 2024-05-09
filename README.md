# Resume

A minimalist and elegant `LaTeX` template for crafting professional resumes. This template is designed to be highly compatible with resume parsers, avoiding complex formatting and elements to ensure your resume is accessible and easily interpreted by **automated HR systems.**

See the [example](examples/example.pdf "Example").

## Prerequisites

Before using this template, ensure you have the following installed:

- **LaTeX:** A full LaTeX distribution is necessary. [TeX Live](https://tug.org/texlive/) is recommended, as it includes `LuaLaTeX`.
- **LuaLaTeX:** This engine offers greater flexibility in font specification and other useful features.

## Installation

Clone the repository:

```sh
git clone https://github.com/korikhin/Resume.git
```

or with the GitHub CLI:

```sh
gh repo clone korikhin/Resume
```

Navigate to the `src` directory:

```sh
cd Resume/src
```

## Building Resume

To compile your resume with `LuaLaTeX` for the _best appearance_, use the following command:

```sh
lualatex --synctex=1 --interaction=nonstopmode --output-directory=build main.tex
```

## Parser Compatibility

This template is designed with parser compatibility in mind, aiming to improve the chances of accurate interpretation by _automated screening systems_. By maintaining simplicity and avoiding complex markup and elements, it seeks to perform consistently across various platforms.
