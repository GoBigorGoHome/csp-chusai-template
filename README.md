# csp-chusai-template

CSP 初赛试卷 LaTeX 模板

使用 [VS Code](https://code.visualstudio.com/) 和 [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop) 扩展。

生成师生两版：
```
xelatex -shell-escape main.tex
```
有 -shell-escape 选项在时，exam-zh 就会编译师生两版，并且此时它会调用 latexmk 来进行多次编译。
