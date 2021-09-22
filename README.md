# zitie 字帖
LaTeX package for make CJK calligraphy practicing sheet

生成字帖临摹纸的LaTeX宏包。

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

Currently, only support XeTeX. 目前仅支持 XeTeX

Dependence: `LaTeX2e 2020-10-01` and after, `l3draw`, please note that `l3draw` is very experimental, some functions maybe cannot use later.

依赖 `l3draw`，不依赖 `pgf` 模块。注意：`l3draw` 目前仍然是实验性的，往后版本可能无法使用。

TODO:
- ~~documentation 编写说明文档~~
- faster and less resource 实现更快、消耗资源更少的版本
- optimize `background` module 改进 background 模块
- support LuaTeX 支持 LuaTeX
- support pinyin 支持拼音
- more grid 支持更多的网格效果
- more transform 支持更多的变换
- support opacity (need l3opacity)
- ...

Source file (zitie.tex, zitie.sty) under LPPL 1.3c license.
