---
title: Tensor de Tensões
parent: Tensão
layout: home
nav_order: 1
has_toc: false
has_children: false
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Estado de Tensões</h1>

<p align="justify">
    Podemos definir o estado de tensões em um ponto de um sólido, ou em uma partícula de dimensões desprezíveis, como um tensor cartesiano composto por nove componentes (equação <a href="#eq1">1</a>) relativas a três planos ortogonais que determinam as tensões em qualquer plano passando pelo ponto, sendo três tensões normais e seis tensões tangenciais. Portanto, podemos considerar o conjunto dos nove componentes de tensão como um tensor de segunda ordem.
   
</p>

{: .warning-title }
> IMPORTANTE
>
> O tensor de tensões é simétrico, ou seja, $\sigma _{ij}=\sigma _{ji}$, e dessa maneira podemos definir o estado plano de tensões em um ponto somente com 6 componentes.


<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ \sigma _{ij}=\begin{bmatrix}
 \sigma _{xx}&  \tau_{xy}&  \tau_{xz}\\
 \sigma _{yx}&  \tau_{yy}&  \tau_{yz}\\
 \sigma _{zx}&  \tau_{zy}&  \tau_{zz}\\
\end{bmatrix} \]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(1)</p></td>
    </tr>
</table>

{: .warning-title }
> IMPORTANTE
>
> Neste formato que representamos os nove componentes de tensões, o primeiro subscrito identifica a linha e o segundo subscrito denota a coluna do tensor de tensões de segunda ordem. Por sua vez, a diagonal do tensor de tensões armazena as tensões normais atuantes no ponto ou na partícula. 





