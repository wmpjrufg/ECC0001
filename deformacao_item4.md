---
title: def4
parent: Deformação
layout: home
nav_order: 4
has_toc: false
has_children: false
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Descrição do Tensor de Tensões</h1>

<p align="justify">
    Podemos definir o estado de tensões em um ponto de um sólido, ou em uma partícula de dimensões desprezíveis, como um tensor cartesiano composto por nove componentes (equação <a href="#eq1">1</a>) relativas a três planos ortogonais que determinam as tensões em qualquer plano passando por esse ponto, sendo três tensões normais e seis tensões tangenciais. Portanto, podemos considerar o conjunto das nove componentes de tensão como um tensor de segunda ordem, onde a sua representação gráfica está descrita na Figura <a href="#fig-tensor-1">1</a>.
   
</p>

{: .warning-title }
> IMPORTANTE
>
> O tensor de tensões é simétrico, ou seja, $$\sigma _{ij}=\sigma _{ji}$$, e dessa maneira podemos definir o estado plano de tensões em um ponto somente com seis componentes de tensão.

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

{: .warning-title }
> IMPORTANTE
>
> Considerando o formato em que representamos as nove componentes de tensões, o primeiro subscrito identifica a linha e o segundo subscrito denota a coluna do tensor de tensões de segunda ordem. Por sua vez, a diagonal do tensor de tensões armazena as tensões normais atuantes no ponto ou na partícula. 

<center><img src="assets/images/fig-tensor-1.png" width="70%" height="auto"/></center>
<p align="left" id="fig-tensor-1"><b>Figura 1.</b> Representação gráfica do tensor de tensões <a href="#ref1">[1]</a>.</p>

{: .highlight-title }
> CONCEITO
>
> Um tensor é uma generalização de vetores e matrizes para dimensões superiores. Ele é uma entidade matemática que pode representar relações lineares entre vetores, escalando e rotacionando-os de acordo com uma certa transformação.

<p align="justify">
Pode ser difícil visualizar diretamente um tensor de ordem superior, mas pense neles como extensões de vetores e matrizes para várias dimensões. Eles encapsulam informações mais complexas, especialmente em sistemas que requerem múltiplas direções de análise ao mesmo tempo.
</p>

<h1>Referências</h1>

<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>Referência</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><p align = "center" id = "ref1">[1]</p></td>
            <td><p align = "left">Parnes R. Solid mechanics in engineering. Chichester: Wiley; 2001.</p></td>
        </tr>    
    </tbody>
</table>
