---
layout: page
title: Portfolio
permalink: /portfolio/
sortname: portfolio
---

<h3><ol style="padding:0;list-style-type:none;">
  <li><a href="./#Math">Mathematics</a>
  <ol style="list-style-type:none;margin-left:-1em;">
    <li><a href="./#PhD">Doctoral dissertation</a> | <a href="./#MSc">Master's thesis</a> | <a href="./#AB">Bachelor's thesis</a></li>
  </ol></li>
  <li><a href="./#Art">Art</a>
  <ol style="list-style-type:none;margin-left:-1em;">
    <li>Vienna
    <ol style="list-style-type:none;margin-left:-1em;">
    <li><a href="./#sketching_Vienna">Sketching</a> | <a href="./#drawing_TU">Drawing/Painting</a> | <a href="./#sculpture_TU">Sculpture</a></li>
    </ol></li>
    <li>Bonn
    <ol style="list-style-type:none;margin-left:-1em;">
    <li><a href="./#drawing_Bonn">Drawing</a></li>
    </ol></li>
    <li>Princeton
    <ol style="list-style-type:none;margin-left:-1em;">
    <li><a href="./#sculpture_Princeton">Sculpture</a> | <a href="./#video_Princeton">Video</a></li>
    </ol></li>
  </ol></li>
</ol></h3>

<hr>

<h2><a class="anchor" id="Math"></a>Mathematics <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h2>

<h3><a class="anchor" id="PhD"></a>Doctoral dissertation <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h3>

<p>
  This is to-be-determined.  A current description is on the <a href="/#phd">main page</a>.
</p>
<br>

<h3><a class="anchor" id="MSc"></a>Master’s thesis <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h3>

<p>
  This was completed in July 2015.
  <table style="width:100%;border-collapse:collapse;">
    <tr>
      <td><u>Title</u>:</td> <td><i>From Green's Functions to Chord Spaces, for the \(2\)-Disk</i></td>
    </tr>
    <tr>
      <td><u>Adviser</u>:</td> <td>Prof. C. F. Bödigheimer</td>
    </tr>
    <tr>
      <td><u>School</u>:</td> <td>Universität Bonn, Germany</td>
    </tr>
    <tr>
      <td style="width:75px;text-align:left;vertical-align:top;"><u>Synopsis</u>:</td> <td>Let \(\mathbf{D}^{2}\) be the \(2\)-disk, as it sits in the standard \(\mathbf{R}^{2} \cong \mathbf{C}\), and let \(\mathcal{Z} = \{\zeta_{j}\}_{j=1}^{n} \subset \mathbf{D}^{2}\).  On \(\mathbf{D}^{2} \smallsetminus \{\zeta_{j}\}_{j}\), there is a harmonic function with singularities at \(\mathcal{Z}\):
        \[g_{\mathcal{Z}} \left(z\right) := \sum_{j=1}^{n} \ln \left|\frac{\zeta_{j} - z}{1 - \overline{\zeta_{j}} z}\right| .\]
        It can be shown that this function has, with multiplicities, \(n-1\) critical points in \(\mathbf{D}^{2} \smallsetminus \{\zeta_{j}\}_{j=1}^{n}\).  Looking at the flow lines of the gradient of \(g_{\mathcal{Z}}\) around a critical point \(\rho\), there are certain flow lines that approach \(\rho\) from \(\partial \mathbf{D}^{2}\), the boundary of \(\mathbf{D}^{2}\), and certain flow lines that recede from \(\rho\) toward some singularity or another critical point.  The main task was to understand the relationship between those singular points \(\mathcal{Z}\) and the points of \(\partial\mathbf{D}^{2}\) which flow approaching some critical point.
      </td>
    </tr>
  </table>
</p>
<br>

<h3><a class="anchor" id="AB"></a>Bachelor’s thesis <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h3>

<p>
Starting from near foundations, the theory of the calculus of variations was developed in the semi-Riemannian
setting. Using appropriate results from the theory and contextual material, two main theorems were proven regarding
(in)completeness based on curvature bounds: the Bonnet-Myers (completeness) theorem in the Riemannian context,
and one of Hawking’s singularity (incompleteness) theorems in the Lorentzian context.
</p>
<br>

<hr>

<h2><a class="anchor" id="Art"></a>Art <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h2>

<h3><a class="anchor" id="sketching_Vienna"></a>Sketching in Vienna <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h3>
<p>
  While living in Vienna, I sketch regularly around the City: at museums, and recently, also outside.  The drawings are done in pencil, while the paintings are done with various watercolors.
  <table style="width:100%;">
    <tr>
    {% for j in (0..1) %}
      <td style="width:25%"><a href="/Kunst/Wien/Skizze/Zeichnen/resized/02{{ 1 | minus: j }}.jpg"><img src="/Kunst/Wien/Skizze/Zeichnen/thumbs/02{{ 1 | minus: j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 0 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    {% for j in (0..4) %}
      <td style="width:25%"><a href="/Kunst/Wien/Skizze/Zeichnen/resized/01{{ 9 | minus: j }}.jpg"><img src="/Kunst/Wien/Skizze/Zeichnen/thumbs/01{{ 9 | minus: j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 2 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    </tr>
    <tr>
    {% for j in (0..7) %}
      <td style="width:25%"><a href="/Kunst/Wien/Skizze/Aquarell/resized/00{{ 8 | minus: j }}.jpg"><img src="/Kunst/Wien/Skizze/Aquarell/thumbs/00{{ 8 | minus: j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 0 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    </tr>
  </table>
</p>
<br>

<h3><a class="anchor" id="drawing_TU"></a>Drawing/Painting at the TU <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h3>
<p>
  During my Doctoral studies (2016&ndash;), I am regularly participated in <i>Beobachtendes Zeichnen I/II</i> offered by the TU Wien.  The paintings are done in watercolors, while the drawings are done in pencil, and the duration of the poses varied, from about 5&ndash;15 minutes each.
  <table style="width:100%;">
    <tr>
    {% for j in (0..2) %}
      <td style="width:25%"><a href="/Kunst/Wien/Akt/Aquarell/resized/01{{ 2 | minus: j }}.jpg"><img src="/Kunst/Wien/Akt/Aquarell/thumbs/01{{ 2 | minus: j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 0 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    {% for j in (0..8) %}
      <td style="width:25%"><a href="/Kunst/Wien/Akt/Aquarell/resized/00{{ 9 | minus: j }}.jpg"><img src="/Kunst/Wien/Akt/Aquarell/thumbs/00{{ 9 | minus: j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 1 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    </tr>
    <tr>
    {% for j in (0..4) %}
      <td style="width:25%"><a href="/Kunst/Wien/Akt/Zeichnen/resized/00{{ 5 | minus: j }}.jpg"><img src="/Kunst/Wien/Akt/Zeichnen/thumbs/00{{ 5 | minus: j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 0 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    </tr>
  </table>
</p>
<br>

<h3><a class="anchor" id="sculpture_TU"></a>Sculpture at the TU <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h3>
<p>
  So far during Doctoral studies (2016&ndash;), I participated in two Art/Design course at the TU Wien: the first, <i>Dreidimensionales Gestalten</i> (WS2018-19), was about "3-dimensional tilings", and the second, <i>Künstlerisches Projekt X</i> (SS2019), was aimed at developing art pieces, around the theme of "pairs/couples".
  <table style="width:100%;">
    <tr>
      <td style="width:25%"><a href="/Kunst/Wien/Bildhauerei/3DG/Objekt.jpg"><img src="/Kunst/Wien/Bildhauerei/3DG/thumbs/Objekt.jpg" style="width:100%;"></a></td>
      <td style="width:25%"><a href="/Kunst/Wien/Bildhauerei/paar/Stunted-Ephemera.jpg"><img src="/Kunst/Wien/Bildhauerei/paar/thumbs/Stunted-Ephemera.jpg" style="width:100%;"></a></td>
    {% for j in (1..9) %}
      <td style="width:25%"><a href="/Kunst/Wien/Bildhauerei/paar/00{{ j }}.jpg"><img src="/Kunst/Wien/Bildhauerei/paar/thumbs/00{{ j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 2 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    {% for j in (0..9) %}
      <td style="width:25%"><a href="/Kunst/Wien/Bildhauerei/paar/01{{ j }}.jpg"><img src="/Kunst/Wien/Bildhauerei/paar/thumbs/01{{ j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 1 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    {% for j in (0..2) %}
      <td style="width:25%"><a href="/Kunst/Wien/Bildhauerei/paar/02{{ j }}.jpg"><img src="/Kunst/Wien/Bildhauerei/paar/thumbs/02{{ j }}.jpg" style="width:100%;"></a></td>
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

<h3><a class="anchor" id="drawing_Bonn"></a>Drawing in Bonn <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h3>
<p>
  During my Master’s studies (2012&ndash;2015), I participated in <i>Aktzeichnen: Zeichnen nach Modell II</i> offered by the Atelier für Bildende Kunst of Universität Bonn.  The drawings are mostly charcoal, some with Conté, and the poses varied in length, from about 15&ndash;20 minutes each.
  <table style="width:100%;">
    <tr>
    {% for j in (1..9) %}
      <td style="width:25%"><a href="/Kunst/Bonn/Akt/assorted/00{{ j }}.jpg"><img src="/Kunst/Bonn/Akt/assorted/thumbs/00{{ j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 0 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    {% for j in (0..6) %}
      <td style="width:25%"><a href="/Kunst/Bonn/Akt/assorted/01{{ j }}.jpg"><img src="/Kunst/Bonn/Akt/assorted/thumbs/01{{ j }}.jpg" style="width:100%;"></a></td>
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

<h3><a class="anchor" id="sculpture_Princeton"></a>Sculpture at Princeton <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h3>
<p>
  During my undergraduate studies, I participated in a few studio Art courses (2010&ndash;2012), mainly doing sculptural work.  Below is a selection of my work from those courses; they are mixed-media, with predominant use of steel, wood, and twine.  A recurrent theme is exploring space through promoted negative space and constructed tension.
  <table style="width:100%;">
    <tr>
    {% for j in (1..9) %}
      <td style="width:25%"><a href="/Kunst/Princeton/sculpture/small/00{{ j }}.jpg"><img src="/Kunst/Princeton/sculpture/thumbs/00{{ j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 0 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    {% for j in (0..6) %}
      <td style="width:25%"><a href="/Kunst/Princeton/sculpture/small/01{{ j }}.jpg"><img src="/Kunst/Princeton/sculpture/thumbs/01{{ j }}.jpg" style="width:100%;"></a></td>
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

<h3><a class="anchor" id="video_Princeton"></a>Video at Princeton <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h3>
<p>
  A piece (December, 2011) from a course during my undergraduate studies, entitled <i>Painting without Canvas</i>.
  <br><br>
  <img src="/Kunst/Princeton/video/Draenge-titel-small.png" style="width:50%">
</p>
