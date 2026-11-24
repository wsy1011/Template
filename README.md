# 论文 LaTeX 模板

| 出版社 | 模板 | 编译入口 | 来源 |
| --- | --- | --- | --- |
| Taylor & Francis | Interact + APA v1.05 | [main.tex](templates/taylor-francis/interact-apa/main.tex) | [Overleaf 模板页](https://www.overleaf.com/latex/templates/taylor-and-francis-latex-template-for-authors-interact-layout-plus-apa-reference-style/jqhskrsqqzfz) |
| Elsevier | CAS 2.4 | [单栏](templates/elsevier/cas/cas-sc-template.tex) · [双栏](templates/elsevier/cas/cas-dc-template.tex) | [CTAN 发布页](https://ctan.org/pkg/els-cas-templates) |

在对应目录编译。使用 pdfLaTeX 和 BibTeX 时，依次运行 pdfLaTeX、BibTeX、pdfLaTeX 两次。Elsevier 的示例文件为相应栏数的 `cas-*-sample.tex`，配套说明可见 [CAS 使用手册](templates/elsevier/cas/doc/elsdoc-cas.pdf)。

Taylor & Francis 的模板来源页面将 Carsten Schwemmer 列为作者，并标注 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)。此处的主文件名为 `main.tex`，启用 `apacite` 处理 APA 引用。编译时从 TeX 发行版加载 `subfig`、`booktabs`、`epsfig`、`rotating` 和 `apacite`。Elsevier CAS 的许可声明见 [manifest.txt](templates/elsevier/cas/manifest.txt)。
