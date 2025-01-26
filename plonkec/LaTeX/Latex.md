# Latex

<kbd>{obvezni}</kbd>
<kbd>[neobvezi]</kbd>

## Preambula mora vsabovati:

* z <kbd>\documentclass</kbd> ustrezno določiti razred *article* ali *beamer* ter nastaviti velikost papirja in pisave (a4paper, 10pt, 14pt, …)

* z <kbd>\usepackage</kbd> našteti ustrezne pakete

    * s paketi <kbd>babel</kbd>, <kbd>inputenc</kbd> in <kbd>fontenc</kbd> nastaviti ustrezno kodiranje ter podporo za slovenščino

    * Paket <kbd>amsmath</kbd> ponuja različne izboljšave za izboljšanje informacijske strukture in natisnjenega izpisa dokumentov, ki vsebujejo matematične formule

    * Paket <kbd>amssymb</kbd> omogoca uporbo ams simbolov
    
    * Paket <kbd>amsthm</kbd> zagotavlja izboljšano različico ukaza LATEX \newtheorem za definiranje okolij, podobnih izrekom

    * Paket <kbd>hyperref</kbd> nudi LaTeXu možnost ustvarjanja hiperpovezav znotraj dokumenta

    * Paket <kbd>booktabs</kbd> izboljšuje kakovost tabel v LaTeXu, zagotavlja dodatne ukaze in optimizacijo v zakulisju

    * Paket <kbd>graphicx</kbd> izboljša podporo za grafiko

    * Paket <kbd>tikz</kbd> omogoča ustvarjanje visokokakovostnih diagramov

    * Paket <kbd>pgfplots</kbd> riše visokokakovostne diagrame funkcij v običajnem ali logaritemskem skaliranju z uporabniku prijaznim vmesnikom neposredno v TEX-u

* z <kbd>\newcommand</kbd> definirati nove ukaze
    * <kbd>\newcommand{\⟨ime-ukaza⟩}[⟨st-parametrov⟩]{⟨definicija⟩}</kbd>

* z <kbd>\newtheorem</kbd> definirati nova okolja za definicije in trditve (vključno z ustrezno uporabo <kbd>\theoremstyle</kbd>)

## V dokumentu morate znati vključiti:

* naslov: <kbd>\title</kbd>, <kbd>\author</kbd>, <kbd>\date</kbd>, <kbd>\maketitle</kbd>

* dodatne datoteke: <kbd>\input</kbd>
    * <kbd>\input{pot do dokumenta}</kbd>

* povzetek in kazalo: <kbd>abstract</kbd>, <kbd>\tableofcontents</kbd>
    * <kbd>(\begin{abstract} ... \end{abstract})</kbd>

* razdelke: <kbd>\section</kbd>, <kbd>\subsection</kbd>, …

* oblikovano besedilo: <kbd>\emph</kbd> (*italic*, ce ni v \textit), <kbd>\textbf</kbd> (**bold**), <kbd>\textit</kbd> (*italic*), <kbd>\texttt</kbd> (lahko pisemo tekst v formulah), <kbd>\verb</kbd>, <kbd>\url</kbd>, <kbd>\noindent</kbd>, <kbd>\centering</kbd>, <kbd>center</kbd>, <kbd>verbatim</kbd> ()
* oblikovano besedilo: <kbd>\emph</kbd> (*italic*, ce ni v \textit), <kbd>\textbf</kbd> (**bold**), <kbd>\textit</kbd> (*italic*), <kbd>\texttt</kbd> (lahko pisemo tekst v formulah), <kbd>\verb</kbd>, <kbd>\url</kbd>, <kbd>\noindent</kbd>, <kbd>\centering</kbd>, <kbd>center</kbd>, <kbd>verbatim</kbd> ( \verb|\begin{verbatim}|...\verb|\end{verbatim}|:
\begin{verbatim}
Use \LaTeX to typeset the LaTeX logo.
\end{verbatim} )