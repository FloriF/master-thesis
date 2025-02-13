# Create PDF

I work on Windows, so I prepared two batchfiles that I can execute. They only include the basic command to use Quarto to render the markdown files into a PDF. One of them includes a second line to keep the command window open in case there is an error.

# Software

I try to use **free open-source software (FOSS)** wherever I can, especially on projects that are intended to be replicable. The following is the list of software I used for creating this Master Thesis document.

- For reference management, I use [JabRef](https://www.jabref.org). Because I do not like having to export a bib file every time (the saved library *is* the bib file). And I can include that file in my thesis without doing anything else.
- To create the final PDF from the given Markdown files, I used [quarto](https://quarto.org), an "open-source scientific and technical publishing system". As far as I know, the only quarto-specific code is located in the `thesis.qmd` file, the `format` section as well as the commands to include the separate files from the `content` folder.
- Quarto uses [Pandoc](https://pandoc.org/installing.html), which is basically a universal converter for a huge number of file formats.
- To create PDF files from Markdown (or text files in general), you also need a LaTeX installation. I prefer [MiKTeX](https://miktex.org), since it can automatically install missing packages and thus it only downloads the stuff you actually need for your document.
- To view the final PDF, I use [SumatraPDF](https://www.sumatrapdfreader.org/free-pdf-reader).

I am currently using [VSCode](https://code.visualstudio.com) as my main text editor, which is not completely open source, but I plan on switching to [VSCodium](https://vscodium.com).