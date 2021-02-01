---
layout: archive
title: "Pattern formation in the Bénard-Marangoni convection"
permalink: /topicos/
<!-- author_profile: true -->
<!-- redirect_from:
  - /resume -->
---

Uma parte do conteúdo está em vídeo e outra foi passada durante as aulas remotas (Google Meet). O material utilizado durante o curso e os códigos em *Python* (implementação dos métodos utilizados para os exercícios) também estão disponíveis para download.

As principais informações acerca da disciplina estão na seguinte 
<a href="{{ base_path }}/files/Proposta_disciplina_eletiva_MECAN.pdf" target="_blank">ementa</a>. 
Contatos: danielcoelho.uerj@gmail.com, lh.carnevale@gmail.com e pontes.jose@gmail.com.


### Apresentação da disciplina

|PDF|YouTube|Atualizado|Conteúdo|
|------|------|-----------|---------|
| <a href="{{ base_path }}/files/aula00DanielLC.pdf" download="aula00DanielLC.pdf" target="_blank">aula00 </a> |  <a href="https://youtu.be/VtnqctMGg1A" target="_blank">vídeo</a>     | 15/09/2020 | Apresentação da disciplina, avaliação e materiais adotados (D. L. Coelho e L. Carnevale)|

### Material extra

|PDF|YouTube|Atualizado|Conteúdo|
|------|------|-----------|---------|
| - | <a href="https://youtu.be/yV3Xx0IhCEg" target="_blank">vídeo</a> | 03/11/2020 | Ambientes para Programação em Python 3 no Windows 10 (D. L. Coelho)|
| <a href="http://devfuria.com.br/python/sintaxe-basica/" target="_blank">site</a> | <a href="https://www.youtube.com/watch?v=WqZP7atO3SE" target="_blank">vídeo</a> | 11/11/2020 | Um guia rápido e básico da linguagem Python (DevFuria)|


### Parte I -- Método de Diferenças Finitas (D. L. Coelho)

|PDF|Códigos|Atualizado|Conteúdo|
|------|------|-----------|---------|
| <a href="{{ base_path }}/files/aula01DanielLC.pdf" download="aula01DanielLC.pdf" target="_blank">aula01</a> | <a href="{{ base_path }}/files/aula01-codigos.zip" download="aula01-codigos.zip" target="_blank">aula01-codigos</a> | 03/11/2020 | Introdução ao método de diferenças finitas|
| <a href="{{ base_path }}/files/aula02DanielLC.pdf" download="aula02DanielLC.pdf" target="_blank">aula02</a> | <a href="{{ base_path }}/files/aula02-codigos.zip" download="aula02-codigos.zip" target="_blank">aula02-codigos</a> | 21/11/2020 | Método de diferenças finitas|
| - | -          | -          | Aplicações do Método de diferenças finitas|
| - | -          | -          | |
| <a href="{{ base_path }}/files/P1.pdf" download="P1.pdf" target="_blank">P1</a> | <a href="{{ base_path }}/files/P1-Gabarito.zip" download="P1-Gabarito.zip" target="_blank">P1-Gabarito.zip</a> | 26/11/2020 | Gabarito da P1|

### Parte II -- Método de Elementos Finitos (L. H. Carnevale)

|PDF|YouTube|Disponível|Conteúdo|
|------|------|-----------|---------|
| - | -          | -          | Introdução ao método de elementos finitos|


<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<br><br>
<div style="text-align: justify">
Numerical results obtained for the equation derived by E. Knobloch used to study long wavelength pattern formation in the Bénard-Marangoni convection:
</div>

\[
	\dfrac{\partial u}{\partial t}=\alpha u-\mu \nabla^2u-\nabla^4u+
	k\nabla \cdot |\nabla u|^2\nabla u+
	\beta\nabla\cdot \left(\nabla^2 u \nabla u \right) - \gamma\nabla\cdot u \nabla u +
	\delta \nabla^2|\nabla u|^2 \nonumber
\]
<div style="text-align: justify">
Generalized Dirichlet boundary conditions (\(u={\partial u}/{\partial n}=0\)) were assumed for the numerical integration of the governing equation. The numerical scheme consisted of the classical operator splitting scheme of <i>stabilizing correction</i> [4], presenting fourth-order diffusion operators. The \(L_1\) norm was used to measure the rate of change of the distance between two successive states of the system, therefore, it is sensitive to the evolution of both the amplitude and the phase. Steady states assumed for \(L_1 \leq 1 \times 10^{-6}\).
</div>
<br>

<figure>
	<center>
		<img src="{{ base_path }}/images/KN/KN1-evo.png" style="width:80%;height:auto;">
		<figcaption style="text-align: justify;width:80%">
			FIG. \(1\):
			Pattern evolution and its \(L_1\) norm. The simulation departed from random initial conditions around the solution \(u=0\). It is expected that the structure evolves into a stationary single-cell state, filling the whole bounding box.
		</figcaption>
	</center>
</figure>

<figure>
	<center>
		<img src="{{ base_path }}/images/KN/KN2-evo.png" style="width:80%;height:auto;">
		<figcaption style="text-align: justify;width:80%">
			FIG. \(2\):
			Pattern evolution and its \(L_1\) norm. The simulation departed from random initial conditions around the solution \(u=0\). It is expected that the structure evolves into a stationary square pattern for this range of parameters.
		</figcaption>
	</center>
</figure>
<div style="text-align: justify">
FIG. 1 shows results obtained for: \(\alpha=0.0\), \(\mu=2.0\), \(k=1\), \(\beta=-0.125\sqrt{7}\), \(\gamma=0.0\) and \(\delta=0.75\sqrt{7}\). FIG. 2 shows results obtained for: \(\alpha=-0.8\), \(\mu=2.7\), \(k=1\), \(\beta=-0.125\sqrt{7}\), \(\gamma=0.0\) and \(\delta=-0.75\sqrt{7}\). The grid is uniform, structured and staggered with a resolution of \(8\) points per wavelength. This corresponds to a square domain of \(10 \times 10\) wavelengths per side length.
</div>
<br><br><br>

<h2>References</h2>

[1] L. Shtilman, and G. Sivashinsky,
<a href="https://www.sciencedirect.com/science/article/abs/pii/0167278991901405" target="_blank">
Physica D, 52(2-3), 477-488 (1991)</a>.
<br>
[2] M. Bestehorn,
<a href="https://journals.aps.org/pre/abstract/10.1103/PhysRevE.48.3622" target="_blank">
 Physical Review E, 48(5), 3622 (1993)</a>.
<br>
[3] C.I. Christov, J. Pontes, D. Walgraef, and M.G. Velarde,
<a href="https://www.sciencedirect.com/science/article/pii/S0045782596011760" target="_blank">
CMAME, 148(3-4), 209-224 (1997)</a>.
<br>
[4] Yanenko, N. N., 
<a href="https://link.springer.com/book/10.1007%2F978-3-642-65108-3" target="_blank">
The Method of Fractional Steps</a>, New York: Springer, (1971).

<!-- \[x = {-b \pm \sqrt{b^2-4ac} \over 2a}.\]

When \(a \ne 0\), there are two solutions to \(ax^2 + bx + c = 0\) and they are
  \[x = {-b \pm \sqrt{b^2-4ac} \over 2a}.\] -->