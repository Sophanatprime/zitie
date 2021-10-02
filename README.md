# zitie 

zitie is a LaTeX package for making CJK character calligraphy practicing 
sheet (copybook). 

## Main Interfaces

`\framesingle[<options>]{<CJK char>}`, makes frame for single <CJK char>

`\framezi*[<options>]{<CJK chars>}`, makes frame for every single <CJK chars>

`\framezifile*[<options>]{<filename>}`, makes frame from <filename> 
containning <CJK chars>

`\framerange[<options>]{<char Hex range>}`, makes frame from Hex range,
such as: "4E00 -> "4E27, "4E30. etc

`\frametallrange[<options>]{<char Hex range>}`

`\framezitallfile*[<options>]{<filename>}`

`\zitienewfont*{...}`, declares new font(s) for making frame

`\framezhlipsum[<options>]{<paragraphs>}[<name>]`, frames Lorem ipsum given 
<name> and <paragraphs> made by package `zhlipsum`. Use 
`\usepackage[enable-zhlipsum]{zitie}` to enable this function

`\zitiebackground[<background options>]`, make frames in background,
much faster than `\frame...` family. Use 
`\usepackage[enable-background]{zitie}` to enable this function

`\begin{zitieframe}{<initials>}[<options>] ... \end{zitieframe}`,
environment version for `\framezi`, can cantain `\par`

`\zitieCJKfamily`, use CJK font family declared before

`\zitiecolorlet`, zitie version of `\colorlet` in `xcolor` package

`...`

See PDF documentation (in chinese) for more details.

Please note the frame functions of this package currently do need many TeX 
computation, so the compiling maybe very slow.

Support XeTeX and LuaTeX, but the function in LuaTeX is limited.

## Dependence: 

`LaTeX2e 2020-10-01` and after, `l3draw`, `xeCJK`, `ctexsize`, please note that `l3draw`
is very experimental, some interfaces maybe cannot use later.

Need not `pgf` or `pstricks`.

## TODO:
- **faster and less resource**
- **optimize line breaking algorithm**
- optimize `background` module 
- optimize LuaTeX supporting
- more grid
- more transformation
- support more character Classes
- support opacity (require l3opacity)
- ...

## IMPORTANT!!! 

Please note the attached PDF documentation contains NON-COMMERCIAL font. 
The copyright of those fonts belong to font designer(s), mainly, FounderType.
CANNOT be used for commercial purposes without authorization.

Source file (zitie.tex, zitie.sty) under LPPL 1.3c license. 

## Contact

GitHub: https://github.com/Sophanatprime/zitie

Email: longaster@163.com