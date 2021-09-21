# zitie
LaTeX package for CJK calligraphy practicing

`\framezi*[<options>]{<chars>}`

`\framezifile*[<options>]{<filename>}`

`\framerange[<options>]{<Hex range>}`

 `\zitienewfont*{...}`
 
`\framezhlipsum[<options>]{<paragraphs>}[<name>]`

`\zitiebackground[<background options>]`

`\begin{zitieframe}{<initials>}[<options>] ... \end{zitieframe}`

 `\zitieCJKfamily`
 
 `\zitiecolorlet`

`...`

options and other macro see the source: `zitie.sty`.

Currently, only support XeTeX.

TODO:
- documentation 编写说明文档
- faster and less resource 实现更快、消耗资源更少的版本
- optimize `background` module 改进 background 模块
- ...
