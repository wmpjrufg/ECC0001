---
title: Princípio de Cauchy
parent: Tensão
layout: home
nav_order: 3
has_toc: false
has_children: false
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Princípio de Cauchy</h1>

<p align="justify">
    De acordo com o Princípio de Cauchy podemos afirmar que as tensões em um ponto de um corpo contínuo podem ser descritas por um tensor de tensões de Cauchy \(\mathbf{\sigma }\), que é um tensor de segunda ordem. Esse tensor relaciona o vetor de força de tração \(\textbf{T}\left ( \textbf{n} \right )\), que é a força por unidade de área atuando em uma superfície com normal \(\mathbf{ n }\), às tensões internas do material.
    <br>
    <br>
    Dessa forma, podemos escrever o vetor de força como:
</p>

<table style = "width:100%">
<tr>
    <td style="width: 90%;">\[ \mathbf{T}(n) = \boldsymbol{\sigma} \cdot \mathbf{n} \]</td>
    <td style="width: 10%;"><p align = "right" id = "eq1">(1)</p></td>
</tr>
</table>

<p align="justify">
    Onde:
</p>

<ul>
  <li>\(\textbf{T}\left ( \textbf{n} \right )\) é o vetor de força de tração, que indica a direção e magnitude da força por unidade de área em um plano com normal \(\mathbf{ n }\);</li>
  <li>\(\mathbf{\sigma }\) é o tensor de tensões de Cauchy, que possui 9 componentes (3x3 matriz) que descrevem as tensões normais e de cisalhamento em três direções mutuamente ortogonais;</li>
  <li>\(\mathbf{ n }\) é o vetor normal à superfície na qual as tensões estão sendo calculadas.</li>
</ul>

<p align="justify">
    Geralmente representamos o Tensor de tensões de Cauchy como uma matriz quadrada 3x3:      
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ \sigma _{ij}=\begin{bmatrix}
 \sigma_{xx}&  \tau_{xy}&  \tau_{xz}\\
 \tau_{xy}&  \sigma _{yy}&  \tau_{yz}\\
 \tau_{xz}&  \tau_{yz}&  \sigma_{zz}\\
\end{bmatrix} \]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(1)</p></td>
    </tr>
</table>

<p align="justify">
    Onde:
</p>

<ul>
  <li>\(\sigma_{xx}\), \(\sigma_{yy}\) e \(\sigma_{zz}\) são as tensões normais nas direções x, y, e z, respectivamente;</li>
  <li>\(\tau_{xy}\), \(\tau_{yz}\) e \(\tau_{xz}\) são as tensões de cisalhamento entre essas direções.</li>
 </ul>