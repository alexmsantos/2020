---
layout: post
title: Observador v2.1 - redesign e refactoring
date: 2019-09-28 18:59:00 +0000
author: Alex Santos
excerpt:
permalink: /observador-v2-1-redesign-e-refactoring
categories:
  - Portefólio
tags:
  - Observador
  - UI design
  - UX design
  - Frontend
---
<p>URL: <a href="http://observador.pt" target="_blank">observador.pt</a> | Ano: 2019<br>
UI/UX design: Alex Santos e Alice Moniz. Frontend: Alex Santos, Alice Fernandes e Alice Moniz. Backend: Alexandre Pinheiro, Eduardo Oliveira e Nuno Gama Freire. Direção geral: Leo Xavier.</p>

![Observador v2]({{ site.baseurl }}/assets/img/04-obs-mockup-v2.jpg)
![Observador v2]({{ site.baseurl }}/assets/img/01-obs-mockup-v2.jpg)
![Observador v2]({{ site.baseurl }}/assets/img/05-obs-mockup-v2.jpg)
![Observador v2]({{ site.baseurl }}/assets/img/03-obs-mockup-v2.jpg)
![Observador v2]({{ site.baseurl }}/assets/img/02-obs-mockup-v2.jpg)

Esta semana foi lançado o projeto no qual a equipa técnica do Observador tem trabalhado nos últimos meses: o redesenho de todas as páginas interiores e o <em>refactoring</em> completo do código do site. Artigos, Opinião, Especiais, Fact Checks, Explicadores, páginas de autores e colunistas, e todas as páginas estáticas estão agora mais funcionais e demoram menos tempo a carregar. Finalmente, as páginas interiores partilham a mesma <em>grid</em> que criámos, há dois anos, para a <em>home page</em> e páginas agregadoras: um sistema de grelha de quatro colunas, baseado na <a href="http://flexboxgrid.com/" target="_blank" rel="noopener">Flexbox Grid</a> de Kristofer Joseph, que o Leo Xavier adaptou.

Também criámos ou refizemos novos blocos — Infobox, Numberbox, Fotogaleria, Leitor Áudio, Imagem (agora com a possibilidade de introduzir até quatro imagens), Vídeo, Índices de coleções, Citações com fotografia — e introduzimos novos formatos — Entrelinhas e História Oral. Todo o site passou também a ser navegável sem que o leitor de áudio pare, uma funcionalidade aguardada desde o lançamento da Rádio Observador, há três meses.

Foi um trabalho complexo, que demorou vários meses, sobretudo porque era imperioso garantir a quase total retrocompatibilidade. Para se ter uma ideia da dimensão do projeto, foram feitas 1.771 submissões individuais de código, totalizando 2.708.261 linhas de código alteradas.

Agora que o trabalho está concluído e lançado, os próximos dias serão passados a estabilizar o site e a corrigir pequenos <em>bugs</em> que vamos encontrando (porque não há código novo sem <em>bugs</em>). Mas o essencial está feito. E não há melhor sensação do que dar por concluído um projeto que, tantas vezes, ao longo do percurso, pareceu não ter fim à vista. <em>Job done</em>.

Mais sobre o lançamento desta nova versão do site, na newsletter semanal <a href="https://mailchi.mp/de7ba39604d3/j-nasceu-a-nova-revista-de-lifestyle-do-observador-534969" target="_blank" rel="noopener">Observador Premium</a>.