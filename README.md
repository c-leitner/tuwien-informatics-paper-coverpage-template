# Tuwien Informatics Paper Coverpage Template

This template adaptes the [official cover page](https://informatics.tuwien.ac.at/template-master-thesis-frontispiece-example.pdf) for papers of diploma theses submitted at the faculty for informatics at the TU Wien, Vienna, Austria.

## Getting started

Clone this repository and compile the file `main.tex` with LuaTeX (i.e., execute `lualatex main.tex`). Your output should look like [this](main.pdf).

## Personalizing the template

In order to personalize this template, just redefine the corresponding commands in `titlepage.tex` accordingly.
```
\newcommand{\thesistitle}{Titel}
\newcommand{\thesisdegree}{Ausarbeitung}
\newcommand{\thesisstudies}{Lehrveranstaltungsname}
\newcommand{\thesisauthorone}{Max Muster}
\newcommand{\thesisstudentnumber}{1234567}
\newcommand{\thesisauthortwo}{John Doe}
\newcommand{\thesisstudentnumbe}{1234567}
\newcommand{\thesisauthorthree}{Alice Doe}
\newcommand{\thesisstudentnumb}{1234567}
\newcommand{\thesisinstitute}{Computer Engineering}
\newcommand{\thesisfaculty}{Informatik}
\newcommand{\thesisuniversity}{Technischen Universit\"{a}t Wien}
\newcommand{\thesiscollaboration}{}
\newcommand{\thesissupervisor}{Titel Dr. Vorname Familienname}
\newcommand{\thesiscosupervisor}{Univ.-Ass. Dr. Vorname Familienname}
\newcommand{\thesisplace}{Wien}
\newcommand{\thesisdate}{TT.MM.JJJJ}
```

## Compiling the titlepage

In a bash terminal, run `latexmk -pvc -pdf -lualatex main.tex` for optimal results.

Forked from [tempse/tuwien-thesis-coverpage-template] https://github.com/tempse/tuwien-thesis-coverpage-template
