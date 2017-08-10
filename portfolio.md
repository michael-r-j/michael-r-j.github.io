---
layout: page
title: Portfolio
permalink: /portfolio/
sortname: portfolio
---

<h2>Mathematics</h2>

<h3>Doctoral dissertation</h3>

This is to-be-determined.  A current description is on the <a href="/index.html#phd">main page</a>.

<h3>Master’s thesis</h3>

<p>
This was completed in July 2015, and is described on the <a href="/index.html#masters">main page</a>.
</p>


<h3>Bachelor’s thesis</h3>

<p>
Starting from near foundations, the theory of the calculus of variations was developed in the semi-Riemannian
setting. Using appropriate results from the theory and contextual material, two main theorems were proven regarding
(in)completeness based on curvature bounds: the Bonnet-Myers (completeness) theorem in the Riemannian context,
and one of Hawking’s singularity (incompleteness) theorems in the Lorentzian context.
</p>

<br>

<h2>Art</h2>

<h3><a class="anchor" id="drawing">Drawing</h3>
<p>
During my Master’s studies (2012-2015), I participated in drawing courses offered by the Atelier für Bildende Kunst of Universität Bonn.  The drawings are mostly charcoal, some with Conté, and the poses were about 15&ndash;20 minutes.
<table style="width:100%;">
  <tr>
  {% for j in (1..9) %}
    <td><a href="/drawings/assorted/00{{ j }}.jpg"><img src="/drawings/assorted/thumbs/00{{ j }}.jpg" style="width:100%;"></a></td>
  {% assign row = forloop.index | modulo:4 %}
  {% if row == 0 %}
  </tr>
  <tr>
  {% endif %}
  {% endfor %}
  {% for j in (0..6) %}
    <td><a href="/drawings/assorted/01{{ j }}.jpg"><img src="/drawings/assorted/thumbs/01{{ j }}.jpg" style="width:100%;"></a></td>
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
During my undergraduate studies, I participated in a few studio Art courses (2010-2012), mainly doing sculptural work.  Below is a selection of my work from those courses; they are mixed-media, with predominant use of steel, wood, and twine.  A recurrent theme is exploring space through promoted negative space and constructed tension.
<table style="width:100%;">
  <tr>
  {% for j in (1..9) %}
    <td><a href="/sculptures/small/00{{ j }}.jpg"><img src="/sculptures/thumbs/00{{ j }}.jpg" style="width:100%;"></a></td>
  {% assign row = forloop.index | modulo:4 %}
  {% if row == 0 %}
  </tr>
  <tr>
  {% endif %}
  {% endfor %}
  {% for j in (0..6) %}
    <td><a href="/sculptures/small/01{{ j }}.jpg"><img src="/sculptures/thumbs/01{{ j }}.jpg" style="width:100%;"></a></td>
  {% assign row = forloop.index | modulo:4 %}
  {% if row == 3 and j != 6 %}
  </tr>
  <tr>
  {% endif %}
  {% endfor %}
  </tr>
</table>
</p>
<br>

<h3>Video</h3>
<p>
A piece (December, 2011) from a course during my undergraduate studies, entitled <i>Painting without Canvas</i>.
<br><br>
<img src="/files/video/Draenge-titel-small.png" style="width:50%">
