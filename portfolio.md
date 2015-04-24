---
layout: post
title: Portfolio
permalink: /portfolio/
---

<h2>Mathematics</h2>

<h3>Bachelors thesis</h3>

<p>
Starting from near foundations, the theory of the calculus of variations was developed in the semi-Riemannian
setting. Using appropriate results from the theory and contextual material, two main theorems were proven regarding
(in)completeness based on curvature bounds: the Bonnet-Myers (completeness) theorem in the Riemannian context,
and one of Hawking’s singularity (incompleteness) theorems in the Lorentzian context.
</p>

<!-- <p>
There is a link for it 
</p> -->

<h3>Masters thesis</h3>

<p>
This is a work in progress, and is described on the <a href="../index.html">main page</a>.
</p>
<br>

<h2>Art</h2>

<h3>Drawing</h3>
<p>
During my Masters studies, I participated in drawings courses offered by the Atelier für Bildende Kunst.  The drawings are mostly with charcoal, with some Conté.
<table style="width:100%;">
  <tr>
  {% for j in (1..9) %}
    <td><a href="/drawings/assorted/thumbs/00{{ j }}.jpg"><img src="/drawings/assorted/thumbs/00{{ j }}.jpg" style="width:100%;"></a></td>
  {% assign row = forloop.index | modulo:4 %}
  {% if row == 0 %}
  </tr>
  <tr>
  {% endif %}
  {% endfor %}
  {% for j in (0..9) %}
    <td><a href="/drawings/assorted/thumbs/01{{ j }}.jpg"><img src="/drawings/assorted/thumbs/01{{ j }}.jpg" style="width:100%;"></a></td>
  {% assign row = forloop.index | modulo:4 %}
  {% if row == 3 %}
  </tr>
  <tr>
  {% endif %}
  {% endfor %}
  </tr>
</table>
</p>
<br>

<h3>Sculpture</h3>
<p>
During my undergraduate studies, I participated in a few studio Art courses, mainly doing sculptural work.
<table style="width:100%;">
  <tr>
  {% for j in (1..9) %}
    <td><a href="/sculptures/small/0{{ j }}.jpg"><img src="/sculptures/thumbs/0{{ j }}.jpg" style="width:100%;"></a></td>
  {% assign row = forloop.index | modulo:4 %}
  {% if row == 0 %}
  </tr>
  <tr>
  {% endif %}
  {% endfor %}
  {% for j in (0..6) %}
    <td><a href="/sculptures/small/1{{ j }}.jpg"><img src="/sculptures/thumbs/1{{ j }}.jpg" style="width:100%;"></a></td>
  {% assign row = forloop.index | modulo:4 %}
  {% if row == 3 and j != 6 %}
  </tr>
  <tr>
  {% endif %}
  {% endfor %}
  </tr>
</table>
</p>
