# Gut Microbiome Analysis for CRC Detection

This repository contains the source code for the book **"Gut Microbiome Analysis for CRC Detection: From Raw Sequences to Machine Learning Models,"** created using [Quarto](https://quarto.org/). The book is available online at [https://pankajchejara23.github.io/bioinformatics_book/](https://pankajchejara23.github.io/bioinformatics_book/).

## Project Structure

```
├── _quarto.yml          # Quarto project configuration
├── index.qmd            # Homepage for the book
├── chapters/            # Directory containing individual chapter files
├── docs/                # Rendered HTML files
├── images/              # Figures and images used in the book
├── data/                # Datasets used in examples
└── README.md            # This file
```

### Key Files and Directories

- **`_quarto.yml`**: Defines the global settings for the book, including the title, author, and output format.
- **`index.qmd`**: The main landing page for the book.
- **`chapters/`**: Contains the `.qmd` and `.ipynb` files for each chapter.
- **`docs/`**: Contains rendered html files.
- **`images/`**: Stores all images and figures used throughout the book.
- **`data/`**: Includes datasets required for code examples and analysis.

## Prerequisites

To build this book locally, you'll need:

1. **Quarto**: Install from [Quarto's official website](https://quarto.org/docs/get-started/).
2. **R** or **Python**: Depending on the code examples in the book, install the necessary runtime.
3. **Packages**: Install any additional dependencies required for the code snippets.

## How to Build the Book

1. Clone the repository:
   ```bash
   git clone https://github.com/pankajchejara23/bioinformatics_book.git
   cd bioinformatics_book
   ```

2. Render the book locally:
   ```bash
   quarto render
   ```

3. Open the generated HTML files located in the `docs/` directory in your browser.

## License

Copyright © 2024 Pankaj Chejara

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


---


