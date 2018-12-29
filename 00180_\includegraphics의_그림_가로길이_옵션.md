```
[width=0.8\textwidth]
```


| Abbreviation | Definition |
| ------------ | ---------- |
| pt | A point, is the default length unit. About 0.3515mm |
| mm | a millimetre |
| cm | a centimetre |
| in | an inch |
| ex | the height of an x in the current font |
| em | the width of an m in the current font |
| \columnsep | distance between columns |
| \columnwidth | width of the column |
| \linewidth | width of the line in the current environment |
| \paperwidth | width of the page |
| \paperheight | height of the page |  
| \textwidth | width of the text |
| \textheight | height of the text |
| \unitleght | units of length in the picture environment. |

```
\documentclass[serif]{beamer} 

\usetheme{Warsaw}

\usecolortheme{default}

\usepackage[english]{babel}

\usepackage{kotex} 



\title[Short Paper Title ]{Long Paper Title}
\subtitle{Paper Subtitle}
\author[Author, Another]{Min Eun Gi\inst{1} \and S.~Another\inst{2}}
\institute[Universities of Somewhere and Elsewhere] 
{
  \inst{1}%
  Department of Mathematice\\
  Kangwon Science High School
  \and
  \inst{2}%
  Department of Theoretical Philosophy\\
  University of Elsewhere
}
\date[CFP 2003] {Conference on Fabulous Presentations, 2003}
\subject{Theoretical Computer Science}




\begin{document}

\begin{frame}
\titlepage
\end{frame}

\begin{frame}
\frametitle{Frame Title}
\framesubtitle{Frame Subtitle}

\begin{center}
	Beamer presentation 시작합니다.
\end{center}

\includegraphics[width=0.8\textwidth]{a1}

\end{frame}


\end{document}
```

[목차](./README.md)



