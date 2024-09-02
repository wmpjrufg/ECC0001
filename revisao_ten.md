---
title: Tensões e deformações
parent: Introdução
layout: home
nav_order: 1
has_toc: false
has_children: false
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Conceito de Tensão</h1>

<p align="justify">
  Dado que conhecemos os esforços em um seção qualquer do sólido podemos nos por a pensar sobre o efeito dessa força em toda a área dessa seção <i>S</i>. Tal fato poderia nos permitir a determinar a capacidade de carga daquela área genérica. Isso nos leva ao conceito mais básico de tensão que corresponde a uma intensidade médida das forças em uma área <i>A</i> qualquer. Chamaremos essa intensidade de forças por unidade de área de tensão. Um exemplo dessa distribuição pode ser visto na Figura <a href="#fig-tensao-1">1</a> e a equação <a href="#eq1">(1)</a> define essa tensão.
</p>

<center><img src="assets/images/fig-tensao-1.png" width="30%" height="auto"/></center>
<p align="left" id="fig-tensao-1"><b>Figura 1.</b> Força \( \vec{P} \) atuando em um corpo livre do tipo barra reta <a href="#ref1">[1]</a>.</p>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[  \sigma = \frac{dF}{dA} \]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(1)</p></td>
    </tr>
</table>

<p align="justify">
  Em condições mais complexas de carregamento essas tensões poderiam ser decompostas em outras componentes porém isso será abordado na sequência do material para que assim possamos generalizar o conceito de tensão e então empregar uma formulação tensorial.
</p>

<h1>Conceito de Deformação</h1>

<p align="justify">
  O segundo conceito a ser abordado nesta seção é o de deformação. Este consiste na variação de formas e dimensões de um sólido passando para uma nova configuração conforme <a href="#fig-tensao-2">2</a>. Nesta Figura é possível ver um ponto material do sólido mudando sua posição de <i>A</i> para <i>A<sup>*</sup></i>.
</p>

<center><img src="assets/images/fig-tensao-2.png" width="80%" height="auto"/></center>
<p align="left" id="fig-tensao-2"><b>Figura 2.</b> Efeito de um campo <i>u</i> de deslocamento sobre um sólido deformável <a href="#ref1">[1]</a>.</p>

{: .warning-title }
> IMPORTANTE
>
> Um campo de deslocamento pode ser decomposto em duas parcelas, uma delas representando o movimento de corpo rígido, o qual não envolve mudança de forma e dimensões do corpo, e a outra traduzindo justamente este efeito.

<p align="justify">
  Portanto considerando um elemento unidimensional de comprimento inicial <i>L</i> podemos definir a deformação na sua forma infinitesimal:
</p>

<center><img src="assets/images/fig-tensao-3.png" width="70%" height="auto"/></center>
<p align="left" id="fig-tensao-3"><b>Figura 3.</b> Efeito do campo de deslocamento <i>u</i> em uma barra de comprimento <i>L</i> <a href="#ref3">[3]</a>.</p>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[  \varepsilon  = \frac{du(x)}{dx} \]</td>
        <td style="width: 10%;"><p align = "right" id = "eq2">(2)</p></td>
    </tr>
</table>

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
            <td><p align = "left">
            Beer FP, Johnston Jr. ER, DeWolf JT, Mazurek DF. Mecânica dos materiais. 5o. McGraw-Hill e Bookman; 2021.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref2">[2]</p></td>
            <td><p align = "left">Vilaça SF, Taborda LF. Introducao à Teoria da Elasticidade. Rio de Janeiro: COPPE - UFRJ; 1998.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref3">[3]</p></td>
            <td><p align = "left">Parnes R. Solid mechanics in engineering. Chichester: Wiley; 2001.</p></td>
        </tr>
    </tbody>
</table>