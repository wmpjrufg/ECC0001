---
title: Tensões Octaédricas
parent: Tensão
layout: home
nav_order: 5
has_toc: false
has_children: false
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Introdução</h1>

<p align="justify">
    Podemos definir as tensões octaédricas como tensões que atuam em planos inclinados a 45 graus em relação aos eixos principais de tensão, fornecendo uma maneira invariável de descrever o estado de tensão em um ponto. Elas são compostas pela tensão normal octaédrica e pela tensão de cisalhamento octaédrica, as quais têm importante aplicação em análises estruturais e materiais.
    <br>
    <br>
    Dessa forma, estabelecemos a tensão normal octaédrica (\(\sigma_{oct}\)​) como a média das tensões principais:
</p>

<table style = "width:100%">
<tr>
    <td style="width: 90%;">\[\sigma_{\text{oct}} = \frac{\sigma_1 + \sigma_2 + \sigma_3}{3}\]</td>
    <td style="width: 10%;"><p align = "right" id = "eq1">(1)</p></td>
</tr>
</table>

<p align="justify">
    Para o plano octaédrico, a equação da tensão de cisalhamento é derivada das diferenças entre as tensões principais, onde é deduzida a partir do fato de que as tensões cisalhantes em planos inclinados dependem das diferenças entre as tensões principais atuando ao longo dos diferentes eixos:
</p>

<table style = "width:100%">
<tr>
    <td style="width: 90%;">\[\tau_{\text{oct}} = \frac{1}{3}\sqrt{(\sigma_1 - \sigma_2)^2 + (\sigma_2 - \sigma_3)^2 + (\sigma_3 - \sigma_1)^2}\]</td>
    <td style="width: 10%;"><p align = "right" id = "eq1">(1)</p></td>
</tr>
</table>


{: .warning-title }
> IMPORTANTE
>
> As tensões octaédricas são invariantes sob rotações do sistema de coordenadas, o que as torna úteis em análises de estados de tensão complexos. Elas são amplamente aplicadas em teorias de falha, como o critério de von Mises, que utiliza a tensão de cisalhamento octaédrica para prever a falha de materiais dúcteis sob cargas multiaxiais. Quanto as aplicações, podemos citar:
 <li><b>Geomecânica:</b> Usadas para modelar comportamentos de materiais sujeitos a estados complexos de tensão em solos e rochas.</li>
  <li><b>Engenharia Estrutural:</b> Aplicadas para avaliar o comportamento de estruturas sob cargas combinadas.</li>
  <li><b>Ciência dos Materiais:</b> Fundamentais na análise de plasticidade de materiais, determinando o ponto de escoamento sob carregamentos tridimensionais.</li>




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
            <td><p align = "left">Ugural, A. C., & Fenster, S. K. (2012). Advanced Strength and Applied Elasticity. Prentice Hall.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref2">[2]</p></td>
            <td><p align = "left">Timoshenko, S. P., & Goodier, J. N. (1970). Theory of Elasticity. McGraw-Hill.</p></td>
        </tr>
        <tr>
            <td><p align = "center" id = "ref3">[3]</p></td>
            <td><p align = "left">Mase, G. E., Mase, G. T., & Smelser, R. E. (2009). Continuum Mechanics for Engineers. CRC Press.</p></td>
        </tr>        
    </tbody>
</table>

