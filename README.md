
\documentclass{article}
\usepackage{tikz}
\usetikzlibrary{fadings}

\begin{document}

\begin{tikzpicture}[remember picture,overlay]
    % Background image
    \node[anchor=north west, inner sep=0pt, outer sep=0pt] at (current page.north west) {\includegraphics[width=\paperwidth,height=\paperheight]{https://raw.githubusercontent.com/M4LivesAgain/GTAGWF.github.io/main/rnhbhegj2jhb1.webp}};
    
    % Rainbow overlay
    \foreach \c [count=\i] in {red,orange,yellow,green,blue,indigo,violet} {
        \fill[\c,path fading=north] (current page.north west) ++(0,-\i*\paperheight/7) rectangle ++(\paperwidth,\paperheight/7);
    }
\end{tikzpicture}

\end{document}

