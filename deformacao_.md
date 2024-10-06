---
title: Deformação
layout: home
nav_order: 3
has_toc: true
has_children: true
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Generalização do Conceito de Tensão</h1>

<p align="justify"> 
    Nas seções anteriores fizemos a extensão do conceito de tensões e agora o mesmo ponto de vista será aplicado ao conceito de deformações. Observando a Figura <a href="#fig1">1</a> são obtidas as expressões de deformação.
</p>

<center><img src="assets/images/fig-deform-1.png" width="70%" height="auto"/></center>
<p align="left" id="fig-intro-1"><b>Figura 1.</b> Vista do plano xy de um sólido deformável sujeito a um campo de deslocamento.</p>

<table style="width:100%">
    <tr>
        <td style="width: 90%;">\[\varepsilon_x = \frac{\partial u}{\partial x}\]</td>
        <td style="width: 10%;"><p align="right" id="eq1">(1)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[\varepsilon_y = \frac{\partial v}{\partial y}\]</td>
        <td style="width: 10%;"><p align="right" id="eq2">(2)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[\varepsilon_z = \frac{\partial w}{\partial z}\]</td>
        <td style="width: 10%;"><p align="right" id="eq3">(3)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[\gamma_{xy} = \frac{\partial u}{\partial y} + \frac{\partial v}{\partial x}\]</td>
        <td style="width: 10%;"><p align="right" id="eq4">(4)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[\gamma_{xz} = \frac{\partial u}{\partial z} + \frac{\partial w}{\partial x}\]</td>
        <td style="width: 10%;"><p align="right" id="eq5">(5)</p></td>
    </tr>
    <tr>
        <td style="width: 90%;">\[\gamma_{yz} = \frac{\partial v}{\partial z} + \frac{\partial w}{\partial y}\]</td>
        <td style="width: 10%;"><p align="right" id="eq6">(6)</p></td>
    </tr>
</table>


{: .highlight-title }
> CONCEITO
>
> $$\mathbf{T}_n$$ é definido em muitas literaturas como o vetor **tração** e por definição representa a intensidade de uma força por unidade de área que atua em uma direção arbitrária em relação ao plano de vetor normal $$\vec{\mathbf{n}}$$.

<p align="justify">
    A força \(\mathbf{T}_n\) poderá ser decomposta nas nas direções nos eixos globais \(x\), \(y\) e \(z\) que será indicada respectivamente pelos vetores diretores \(\mathbf{\hat{i}}\), \(\mathbf{\hat{j}}\) e \(\mathbf{\hat{k}}\). Logo o vetor tração na sua forma geral decomposta poderá ser escrito conforme a equação <a href="#eq2">(2)</a>. A Figura <a href="#fig-tensao-2">2</a> apresenta a intensidade de força por unidade de área de acordo com os eixos diretores diretores \(\mathbf{\hat{n}}\), \(\mathbf{\hat{s}}\) e \(\mathbf{\hat{t}}\) 
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[ \mathbf{T}_n = \sigma _{nn} \, \mathbf{\hat{n}} + \tau _{ns} \, \mathbf{\hat{s}} + \tau _{nt} \, \mathbf{\hat{t}}\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq2">(2)</p></td>
    </tr>
</table>

<center><img src="assets/images/fig-tensao-2.png" width="70%" height="auto"/></center>
<p align="left" id="fig-tensao-2"><b>Figura 2.</b> Decomposição do vetor tração nas coordenadas \(\mathbf{\hat{n}}\), \(\mathbf{\hat{s}}\) e \(\mathbf{\hat{t}}\) <a href="#ref1">[1]</a>.</p>

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
