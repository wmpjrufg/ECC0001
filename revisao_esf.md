---
title: Análise de estruturas
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

<p align="justify">
  Uma das etapas mais importantes da elaboração de um projeto de engenharia é a análise de estruturas. De modo geral está etapa consiste em obter os esforços internos dos elementos estruturais.
  <br><br>
  Dada essa etapa poderemos verificar a quantidade de armadura necessária em uma viga de concreto armado ou por exemplo a quantidade de parafusos necessários para uma ligação.
  <br><br>
  Süssekind <a href="#ref1">[1]</a> afirma que existem duas grandezas fundamentais: forças e momentos. 
</p>

{: .highlight-title }
> CONCEITO
>
> Força é uma grandeza física vetorial que pode modificar a direção, o sentido e a velocidade dos corpos. Salientamos que uma força é uma grandeza vetorial.
> Já o momento é a grandeza que mede a tendência de rotação de em torno de um ponto provocada por uma força.

<p align="justify">
  Logo para que um corpo esteja em uma condição de equilíbrio é necessário que esse sistema de forças não provoque nenhuma tendência de translação e rotação a um corpo. Portanto:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ \sum \vec F = 0 \]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(1)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[\sum\vec M=\sum\left(\vec r\times\vec F\right)=0\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq2">(2)</p></td>
    </tr>
</table>

<h1>Referências</h1>

<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>Reference</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><p align = "center" id = "ref1">[1]</p></td>
            <td><p align = "left"><a href="https://doi.org/10.1007/s00521-016-2328-2" target="_blank" rel="noopener noreferrer">Sussekind JC. Curso de análise estrutural: estruturas isostáticas. vol. 1, 11. ed. São Paulo: Globo, 1991. 3v. ISBN 852502267.</a></p></td>
        </tr>
    </tbody>
</table>