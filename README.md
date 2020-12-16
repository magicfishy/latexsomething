## LaTeX Crash Course

LaTeX is typesetting tool for academic documents, and it is especially powerful when helping you cite sources or type math equations.

### Skeleton Code

There are official distributions for LaTeX on Mac and Windows, but for now, we will use Overleaf. Go to overleaf.com and create an account. There, once you open a blank project, you should be able to see some skeleton code.

```latex
\documentclass{article}
\usepackage[utf8]{inputenc}

\title{Paper Title}
\author{Name}
\date{December 2020}

\begin{document}

\maketitle

\section{Introduction}

\end{document}

```

Try changing the parameters inside `\title`, `\author` and `\date` to see what happens. This is the `.tex` file, and everything you type will be within `\begin{document}` and `\end{document}`. Everything before `\begin{document}` can be treated like a preamble -- basically telling the compiler how you want your document to look.
