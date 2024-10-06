---
title: Lei de hooke generalizada
parent:  Comportamento do material
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
    Tal como a análise de tensões, num ponto de um sólido em estado de defomrações existem três direçõesortogonais (direções principais) em relação às quais a distorção é nula (ou seja, os segmentos elementares nestas direções permanecem perpendiculares após a deformação). As deformações destas direção são dadas por \( \epsilon _1, \epsilon _2\;\text{e}\;\epsilon _3\). A equação <a href="#eq1">(1)</a>, caracterizada por ser uma equação algébrica do terceiro grau, possui três raízes que caracterizam as deformações principais. 
</p>

<table style = "width:100%">
<table style="width:100%">
    <tr>
        <td style="width: 90%;">\[ \varepsilon_o^3 - J_1 \varepsilon_o^2 + J_2 \varepsilon_o - J_3 = 0 \]</td>
        <td style="width: 10%;"><p align="right" id="eq1">(1)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ J_1 = \varepsilon_x + \varepsilon_y + \varepsilon_z \]</td>
        <td style="width: 10%;"><p align="right" id="eq2">(2)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">
        \[
            J_2 = 
            \begin{vmatrix}
            \varepsilon_x & \gamma_{xy} & \gamma_{xz} \\
            \gamma_{xy} & \varepsilon_y & \gamma_{yz} \\
            \gamma_{xz} & \gamma_{yz} & \varepsilon_z 
            \end{vmatrix}
        \]
        </td>
        <td style="width: 10%;"><p align="right" id="eq3">(3)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">
        \[
            J_3 = 
            \begin{vmatrix}
            \varepsilon_x & \gamma_{xy} & \gamma_{xz} \\
            \gamma_{xy} & \varepsilon_y & \gamma_{yz} \\
            \gamma_{xz} & \gamma_{yz} & \varepsilon_z
            \end{vmatrix}
        \]
        </td>
        <td style="width: 10%;"><p align="right" id="eq4">(4)</p></td>
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
            <td><p align = "left">Parnes R. Solid mechanics in engineering. Chichester: Wiley; 2001.</p></td>
        </tr>    
    </tbody>
</table>
