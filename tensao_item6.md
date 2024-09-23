---
title: Tensor Desviador
parent: Tensão
layout: home
nav_order: 6
has_toc: false
has_children: false
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Introdução</h1>

<p align="justify">
    É conviniente separar o tensor de tensões em duas parcelas: (a) a parcela desviadora e (b) a parcela hidrostática. O tensor hidrostático, equação <a href="#eq1">(2)</a>, é dado pela tensão média ou tensão hidrostática descrita na equação <a href="#eq1">(1)</a>.
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ h_{ij} = \frac{1}{3} \cdot \(left \sigma_1 + \sigma_2 + \sigma_3 \right) \]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(1)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">
                                \[ \sigma _{ij}=\begin{bmatrix}
                                \sigma_m &  0 &  0 \\
                                0 & \sigma _m &  0 \\
                                0 &  0 &  \sigma_m \\
                                \end{bmatrix} \]
        </td>
        <td style="width: 10%;"><p align = "right" id = "eq2">(2)</p></td>
    </tr>
</table>

<p align="justify">
    O tensor desviador é dado pela equação <a href="#eq3">(3)</a>. 
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ \begin{bmatrix}
                                    \left(\sigma _{xx} - \sigma_m\right)&  \tau_{xy} &  \tau_{xz}\\
                                    \tau_{xy}&  \left(\sigma_{yy} - \sigma_m\right) &  \tau_{yz}\\
                                    \tau_{xz}&  \tau_{yz}&  \left(\sigma_{zz} - \sigma_m\right)\\
                                    \end{bmatrix}  = 0 \]</td>
        <td style="width: 10%;"><p align = "right" id = "eq3">(3)</p></td>
    </tr>
</table>

{: .highlight-title }
> CONCEITO
>
> Logo o tensor desviador $$s_{ij}$$ representa um estado de cisalhamento puro. 

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
            <td><p align = "left"><a href="https://doi.org/10.1007/978-3-319-18878-2" target="_blank" rel="noopener noreferrer">Lubliner J, Papadopoulos P. Introduction to Solid Mechanics: An Integrated Approach. Cham: Springer International Publishing; 2017.</a></p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref2">[2]</p></td>
            <td><p align = "left">Süssekind JC. Curso de análise estrutural: estruturas isostáticas. vol. 1, 11. ed. São Paulo: Globo, 1991. 3v. ISBN 852502267.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref3">[3]</p></td>
            <td><p align = "left">Parnes R. Solid mechanics in engineering. Chichester: Wiley; 2001.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref4">[4]</p></td>
            <td><p align = "left">Vilaça SF, Taborda LF. Introducao à Teoria da Elasticidade. Rio de Janeiro: COPPE - UFRJ; 1998.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref5">[5]</p></td>
            <td><p align = "left">Shames IH, Pitarresi JM. Introduction to solid mechanics. 3rd ed. Upper Saddle River, NJ: Prentice Hall; 2000.</p></td>
        </tr>
    </tbody>
</table>

