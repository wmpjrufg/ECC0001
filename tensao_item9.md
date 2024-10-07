---
title: Representação Geométrica
parent: Tensão
layout: home
nav_order: 9
has_toc: false
has_children: false
---

<!--Don't delete this script-->
<script src = "https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id = "MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<!--Don't delete this script-->

<h1>Representação Geométrica do Estado de Tensão</h1>

<p align="justify">
    A representação geométrica do estado de tensão é uma ferramenta crucial em diversas áreas da mecânica dos sólidos e da mecânica dos meios contínuos, oferecendo uma forma visual e matemática de entender como as tensões atuam em um ponto de um corpo. Essa abordagem se baseia na decomposição do tensor de tensões em diferentes componentes e na análise do comportamento das tensões em diferentes planos e estados. Para isso, o conceito de linha ou eixo hidrostático e a separação do vetor de tensões nos estados original, hidrostático, e desviador são essenciais.
    <br><br>
    O eixo hidrostático é uma linha no espaço tridimensional das tensões principais (\(\sigma_{1}\), \(\sigma_{2}\) e \(\sigma_{3}\)​) em que as tensões normais são iguais em todas as direções. Nesse estado, conhecido como tensão hidrostática, temos:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[\sigma_1 = \sigma_2 = \sigma_3 = \sigma_h\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(1)</p></td>    </tr>

</table>

<p align="justify">
    Em que, (\(\sigma_{h}\))​ representa a tensão hidrostática, que é a média das tensões principais, onde calculamos como:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[\sigma_h = \frac{\sigma_1 + \sigma_2 + \sigma_3}{3}\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(2)</p></td>    </tr>
</table>

<p align="justify">
    No estado hidrostático, as tensões de cisalhamento são nulas e todas as tensões normais são iguais. Isso significa que o vetor de tensões (\(\mathbf{T_{h}}\))​ para qualquer plano será puramente normal, descrito por: 
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[\mathbf{T_h} = \sigma_h \mathbf{n}\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(3)</p></td>    </tr>
</table>

<p align="justify">
    Dessa maneira, como a tensão hidrostática (\(\sigma_{h}\))​ é igual em todas as direções, observamos que o vetor de tensões (\(\mathbf{T_{h}}\))​ é o mesmo independentemente da orientação do plano, o que resulta em uma compressão ou expansão uniforme do material.
</p>

<p align="justify">
    Por outro lado, o estado desviador refere-se à parte do estado de tensão que causa distorção no material, ou seja, altera a forma sem mudar o volume. O vetor de tensões no estado desviador é obtido ao subtrair a tensão hidrostática do tensor de tensões original. O tensor das tensões desviadoras (\(\sigma'_{ij}\))​ é calculado como:
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[\sigma'_{ij} = \sigma_{ij} - \sigma_h \delta_{ij}\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(4)</p></td>    </tr>
</table>

<p align="justify">
    onde \(\sigma'_{ij}\)​ é o delta de Kronecker, que vale 1 quando \(i=j\) e 0 quando \(i\neq j\). O vetor de tensões no estado desviador (\(\mathbf{T_{d}}\))​ é responsável pelas deformações distorcidas e pode ser expresso por:  
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[\mathbf{T_d} = \sigma' \mathbf{n}\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(5)</p></td>    </tr>
</table>

<p align="justify">
    O estado de tensão em um ponto pode ser decomposto na soma de um estado hidrostático e um estado desviador, conforme a equação:  
</p>

<table style = "width:100%">
    <tr>
        <td style="width: 90%;">\[\mathbf{T} = \mathbf{T_h} + \mathbf{T_d}\]</td>
        <td style="width: 10%;"><p align = "right" id = "eq1">(6)</p></td>    </tr>
</table>

<p align="justify">
    Essa decomposição é útil porque o estado hidrostático está associado a mudanças de volume, enquanto o estado desviador está relacionado a mudanças de forma. Em termos de falha de materiais, muitos critérios, como o critério de von Mises, baseiam-se no estado desviador, pois é este que causa a maioria das deformações permanentes ou plásticas.
    <br><br>
    A decomposição do estado de tensão em suas componentes hidrostática e desviadora é essencial para entender o comportamento de materiais submetidos a diferentes tipos de carregamento. Enquanto o estado hidrostático está associado a compressões ou expansões uniformes, o estado desviador é o principal responsável pelas deformações cisalhantes que podem levar à falha do material. Essa abordagem é amplamente aplicada na teoria da elasticidade, na plasticidade, e em teorias de falha.  
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
        <tr>
            <td><p align = "center" id = "ref3">[3]</p></td>
            <td><p align = "left">Malvern, L. E. (1969). Introduction to the Mechanics of a Continuous Medium. Prentice Hall.</p></td>
        </tr> 
        <tr>
            <td><p align = "center" id = "ref3">[3]</p></td>
            <td><p align = "left">Love, A. E. H. (1927). A Treatise on the Mathematical Theory of Elasticity. Cambridge University Press.</p></td>
        </tr> 
    </tbody>
</table>

