### Changing Compiler from Overleaf
* Sometimes for certain languages, classes and packages it may be necessary to use a different compiler like xelatex than the default pdflatex. We have to set XeLatex instead of PdfLatex for writing Bangla</br>

	* To change the compiler, simply click into the left hand menu </br>
	![First Image](/images/first.png)

	* Click on the Compiler menu under Settings </br>
	![Second Image](/images/second.png)




### Code snippet for Bangla

```tex
\documentclass{article}
\usepackage{polyglossia}
\setdefaultlanguage{english}
\setotherlanguage{bengali}

\newfontfamily\englishfont{Noto Sans}
\newfontfamily\bengalifont[Script=Bengali]{Noto Sans Bengali}

\begin{document}

This is an English sentence with some Bengali text: \textbengali{এটি বাংলা ভাষা।} Here is some more English text.

\end{document}

```
