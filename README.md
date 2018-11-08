## Alloy Latex Highlighting

Alloy syntax highlighting for the "listings package" (Latex) (It follows MIT's Alloy environment color style).

Based on this  [gist](https://gist.github.com/timvdalen/3796300)

## Installation
Dowload the _.sty_ file you find in this repo.


Add the dependencies and the _.sty_ file to your main file :
```tex
\usepackage[dvipsnames]{xcolor}
\usepackage{listings}
\usepackage{alloy-style}
```

## How to use

To use it just include your alloy source code where you want :
```tex
\lstinputlisting[language=alloy]{path-to-your-alloy-source-code}
```

## License

Do what you want with this library.