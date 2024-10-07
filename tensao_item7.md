---
title: Equações de Equilíbrio
parent: Tensão
layout: home
nav_order: 7
has_toc: false
has_children: false
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Princípios Fundamentais</h1>

<p align="justify">
    Nos estudos de Mecânica dos Sólidos, as equações de equilíbrio são baseadas no princípio de que a soma das forças atuando em um pequeno elemento de volume deve ser zero para que o corpo esteja em equilíbrio estático. Estas forças incluem tanto as tensões internas que atuam sobre as faces do elemento quanto as forças de volume (como a gravidade) que atuam em todo o corpo.
    <br><br>
    Se considerarmos um elemento infinitesimal retangular em um ponto no espaço, as tensões atuando ao longo de cada uma das três direções coordenadas podem ser descritas pelas componentes de tensão normal (\(\sigma_{xx}\), \(\sigma_{yy}\) e \(\sigma_{zz}\)​) e pelas componentes de tensão de cisalhamento (\(\tau_{xy}\), \(\tau_{yz}\) e \(\tau_{xz}\)​):
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[\frac{\partial \sigma_{xx}}{\partial x} + \frac{\partial \tau_{xy}}{\partial y} + \frac{\partial \tau_{xz}}{\partial z} + f_x = 0\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(1)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[\frac{\partial \tau_{xy}}{\partial x} + \frac{\partial \sigma_{yy}}{\partial y} + \frac{\partial \tau_{yz}}{\partial z} + f_y = 0\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq2">(2)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[\frac{\partial \tau_{xz}}{\partial x} + \frac{\partial \tau_{yz}}{\partial y} + \frac{\partial \sigma_{zz}}{\partial z} + f_z = 0\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq2">(3)</p></td>
    </tr>
</table>

<p align="justify">
    Onde:
</p>

<ul>
  <li>\(\sigma_{xx}\), \(\sigma_{yy}\) e \(\sigma_{zz}\) são as tensões normais nas direções x, y, e z, respectivamente;</li>
  <li>\(\tau_{xy}\), \(\tau_{yz}\) e \(\tau_{xz}\) são as tensões de cisalhamento entre essas direções;</li>
  <li>\(\f_{x}\), \(\f_{y}\) e \(\f_{z}\) são as componentes da força de volume por unidade de volume (como forças gravitacionais) nas direções x, y, e z.</li>
 </ul>

<p align="justify">
    Sabemos que as equações de equilíbrio indicam que, em um estado de equilíbrio estático, a variação espacial das tensões deve balancear as forças de volume atuando sobre o corpo. Dessa forma, se não houver forças de volume, por exemplo, em situações onde as forças externas são negligenciadas, as equações se simplificam para: 
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[\frac{\partial \sigma_{xx}}{\partial x} + \frac{\partial \tau_{xy}}{\partial y} + \frac{\partial \tau_{xz}}{\partial z} = 0\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(4)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[\frac{\partial \tau_{xy}}{\partial x} + \frac{\partial \sigma_{yy}}{\partial y} + \frac{\partial \tau_{yz}}{\partial z} = 0\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq2">(5)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[\frac{\partial \tau_{xz}}{\partial x} + \frac{\partial \tau_{yz}}{\partial y} + \frac{\partial \sigma_{zz}}{\partial z} = 0\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq2">(6)</p></td>
    </tr>
</table>

<p align="justify">
    Na Mecânica do Contínuo, tratamos as equações de equilíbrio de forma mais geral, considerando que o corpo em questão pode estar sujeito a deformações grandes ou pequenas. As equações diferenciais de equilíbrio descritas anteriormente permanecem válidas para qualquer meio contínuo, e sua solução depende das condições de contorno e das propriedades do material, como a elasticidade ou plasticidade.
    <br><br> 
    Essas equações também se integram às equações constitutivas, que relacionam as tensões às deformações de acordo com o comportamento do material (como no caso da Lei de Hooke para materiais elásticos).
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

