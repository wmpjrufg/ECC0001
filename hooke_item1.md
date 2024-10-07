---
title: Lei de Hooke generalizada
parent:  Lei de Hooke
layout: home
nav_order: 1
has_toc: false
has_children: false
---
<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Isotropia</h1>

<p align="justify">
    A isotropia é definida como uma propriedade física do material que indica que as características do material não variam conforme a direção. A propriedade inversa é a anisotropia onde o valor das propriedades variam conforme a direção. 
</p>

{: .highlight-title }
> CONCEITO
>
> Exitem casos particulares desses estados gerais e no caso da anisotropia um estado particular é a ortotropia onde as propriedades físicas são iguais em um plano e variam em uma direão ortogonal a esse plano. Um exemplo clássico desse tipo de material é a madeira.

<h1>Coeficiente de Poisson</h1>

<p align="justify">
    Quando um material é alongado ou comprimido em uma direção (ao longo do eixo longitudinal), ele tende a contrair ou expandir em direções perpendiculares à força aplicada. O coeficiente de Poisson quantifica essa relação entre as deformações:
</p>

<table style="width:100%">
    <tr>
        <td style="width: 90%;">\[ \nu = -\frac{\varepsilon_{lat}}{\varepsilon_{long}} \]</td>
        <td style="width: 10%;"><p align="right" id="eq1">(1)</p></td>
    </tr>
</table>

<p align="justify">
    Onde \(\varepsilon_{lat}\) é a deformação lateral do sólido e \(\varepsilon_{long}\) é a deformação longitudinal.
</p>

<p align="justify">
    Vamos agora escrever o efeito de Poisson nas deformações de um sólido tridimensional conforme descrito na Figura <a href="#fig-hookegen-1">1</a>.
</p>

<center><img src="assets/images/fig-hookegen-1.png" width="90%" height="auto"/></center>
<p align="left" id="fig-hooke-1"><b>Figura 1.</b> Visualização gráfica do conceito de Poisson.</p>

<table style="width:100%">
    <tr>
        <td style="width: 90%;">\[ \varepsilon_x = \frac{\sigma_x}{E} \]</td>
        <td style="width: 10%;"><p align="right" id="eq2">(2)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ \varepsilon_y = - \nu \frac{\sigma_x}{E} \]</td>
        <td style="width: 10%;"><p align="right" id="eq3">(3)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ \varepsilon_z = - \nu \frac{\sigma_x}{E} \]</td>
        <td style="width: 10%;"><p align="right" id="eq4">(4)</p></td>
    </tr>
</table>

<p align="justify">
    Consideração a superposição dos efeitos e um estado tridimensionais de tensões, chega-se as equações de deformações completas:
</p>

<table style="width:100%">
    <tr>
        <td style="width: 90%;">\[ \varepsilon_x = \frac{1}{E} \left( \sigma_x - \nu \sigma_y - \nu \sigma_z \right) \]</td>
        <td style="width: 10%;"><p align="right" id="eq5">(5)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ \varepsilon_y = \frac{1}{E} \left( \sigma_y - \nu \sigma_z - \nu \sigma_x \right) \]</td>
        <td style="width: 10%;"><p align="right" id="eq6">(6)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ \varepsilon_z = \frac{1}{E} \left( \sigma_z - \nu \sigma_x - \nu \sigma_y \right) \]</td>
        <td style="width: 10%;"><p align="right" id="eq7">(7)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ \gamma_{xy} = \frac{1}{G} \tau_{xy} \]</td>
        <td style="width: 10%;"><p align="right" id="eq8">(8)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ \gamma_{yz} = \frac{1}{G} \tau_{yz} \]</td>
        <td style="width: 10%;"><p align="right" id="eq9">(9)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[ \gamma_{zx} = \frac{1}{G} \tau_{zx} \]</td>
        <td style="width: 10%;"><p align="right" id="eq10">(10)</p></td>
    </tr>
</table>

<p align="justify">
    É possível estabelecer uma relação entre os módulos de deformação axial e de distorção conforme equação <a href="#eq11">(11)</a>:
</p>

<table style="width:100%">
    <tr>
        <td style="width: 90%;">\[ G = \frac{E}{2 \cdot \left(1+\nu\right)} \]</td>
        <td style="width: 10%;"><p align="right" id="eq1">(11)</p></td>
    </tr>
</table>

<p align="justify">
    Com as equações de <a href="#eq1">(1)</a> a <a href="#eq11">(11)</a> e possível escrever as relações entre tensões e deformações considerando um estado tridimensional.
</p>

<table style="width:100%">
    <tr>
        <td style="width: 90%;">
        \[
        \begin{pmatrix}
        \sigma_{xx} \\ \sigma_{yy} \\ \sigma_{zz} \\ \tau_{xy} \\ \tau_{xz} \\ \tau_{yz}
        \end{pmatrix}
        =
        \textcolor{red}{
        \frac{E}{(1 + \nu)(1 - 2 \nu)}
        \cdot
        \begin{bmatrix}
        1 - \nu & \nu & \nu & 0 & 0 & 0 \\
        \nu & 1 - \nu & \nu & 0 & 0 & 0 \\
        \nu & \nu & 1 - \nu & 0 & 0 & 0 \\
        0 & 0 & 0 & \frac{1 - 2\nu}{2} & 0 & 0 \\
        0 & 0 & 0 & 0 & \frac{1 - 2\nu}{2} & 0 \\
        0 & 0 & 0 & 0 & 0 & \frac{1 - 2\nu}{2}
        \end{bmatrix}
        }
        \cdot
        \begin{pmatrix}
        \varepsilon_{xx} \\ \varepsilon_{yy} \\ \varepsilon_{zz} \\ \gamma_{xy} \\ \gamma_{xz} \\ \gamma_{yz}
        \end{pmatrix}
        \]
        </td>
        <td style="width: 10%;">
            <p align="right" id="eq12">(12)</p>
        </td>
    </tr>
</table>

<p align="justify">
    Os elementos destacados em cores representam a matriz constitutiva do material. Além disso é possível chegar em estados mais reduzidos dessas matrizes como por exemplo quando se emprega um estado plano de tensão. O sistema pode ser reduzido a uma matriz 3 x 3 conforme equação <a href="#eq13">(13)</a>.
</p>

<table style="width:100%">
    <tr>
        <td style="width: 90%;">
        \[
        \begin{pmatrix}
        \sigma_{xx} \\ \sigma_{yy} \\ \tau_{xy}
        \end{pmatrix}
        =
        \frac{E}{(1 - \nu^2)}
        \cdot
        \begin{bmatrix}
        1 & \nu & 0 \\
        \nu & 1 & 0 \\
        0 & 0 & \frac{(1 - \nu)}{2}
        \end{bmatrix}
        \cdot
        \begin{pmatrix}
        \varepsilon_{xx} \\ \varepsilon_{yy} \\ \gamma_{xy}
        \end{pmatrix}
        \]
        </td>
        <td style="width: 10%;">
            <p align="right" id="eq13">(13)</p>
        </td>
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
