---
layout: page
title: Praxis
permalink: /praxis/
sortname: praxis
---

<h2><ol style="padding:0;list-style-type:none;">
  <li><a href="./#Math">Mathematics</a>
    <ol style="list-style-type:none;margin-left:-1em;">
      <li><a href="./#PhD">Doctoral dissertation</a></li>
    </ol>
  </li>
  <li><a href="./#Art">Art</a>
    <ol style="list-style-type:none;margin-left:-1em;">
      <li><a href="./#photography">Photography</a></li>
      <li>Vienna
        <ol style="list-style-type:none;margin-left:-1em;">
          <li><a href="./#Angewandte">Angewandte (Transdisciplinary Arts)</a>
            <ol style="list-style-type:none;margin-left:-1em;">
              <li><a href="./#Angewandte_Festival22">Angewandte Festival 2022 (28.6. – 1.7.22)</a></li>
              <li><a href="./#Angewandte_Festival21">Angewandte Festival 2021 (29.6. – 2.7.21)</a></li>
            </ol>
          </li>
          <li><a href="./#sketching_Vienna">Sketching</a></li>
          <li><a href="./#portraiture">Portraiture</a></li>
          <li>TU Wien
            <ol style="list-style-type:none;margin-left:-1em;">
              <li><a href="./#drawing_TU">Drawing/Painting</a> | <a href="./#sculpture_TU">Sculpture</a></li>
            </ol>
          </li>
        </ol>
      </li>
      <li>Bonn
        <ol style="list-style-type:none;margin-left:-1em;">
          <li><a href="./#drawing_Bonn">Drawing</a></li>
        </ol>
      </li>
      <li>Princeton
        <ol style="list-style-type:none;margin-left:-1em;">
          <li><a href="./#sculpture_Princeton">Sculpture</a> | <a href="./#video_Princeton">Video</a></li>
        </ol>
      </li>
    </ol>
  </li>
</ol></h2>

<hr>

<h2 style="font-size: 1.75em"><a class="anchor" id="Math"></a>Mathematics <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h2>

<h2><a class="anchor" id="PhD"></a>Doctoral dissertation <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h2>

<p>
  This is to-be-determined; currently looking for a supervisor.
</p>
<br>

<hr>

<h2 style="font-size: 1.75em"><a class="anchor" id="Art"></a>Art <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h2>
More-current ponderings are on <a href="https://www.instagram.com/mchl_rj/">my Instagram</a>.

<h2><a class="anchor" id="photography"></a>Photography<sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h2>
<p>
  In April 2023, I came into the possession of a Rollei 35S.  Here are some photos that represent some of the visual themes I am interested in exploring as part of my overall artistic praxis: spatial renditions cast with the ether of light.
  <table style="width:100%;">
    <tr>
    {% assign row = 0 %}
    {% assign col = 0 %}
    {% for image in site.static_files %}
      {% if image.path contains 'art/photos/thumbs' %}
        <td style="width:25%"><a href="{{ image.path | replace:'thumbs','resized'}}"><img src="{{ image.path }}" style="width:100%;"></a></td>
        {% assign col = col | plus:1 %}
        {% if col == 4 %}
          {% assign row = row | plus:1 %}
          {% assign col = col | modulo:4 %}
        {% endif %}
      {% endif %}
      {% if col == 0 and row >= 1 and row <= 2 %}
        </tr>
        <tr>
      {% endif %}
    {% endfor %}
    </tr>
  </table>
</p>
<br>

<h2><a class="anchor" id="Angewandte"></a>Angewandte, Transdisciplinary Arts <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h2>
<p>
  In October 2020, I started a Masters in the Transdisciplinary Arts (<a href="https://www.transarts.at/">TransArts</a>) Class at the University of Applied Arts (Angewandte) in Vienna.<br>
  <p>
    <a class="anchor" id="Angewandte_Festival22"></a><b>Angewandte Festival 2022</b> (28.6. – 1.7.22)<br>
    <div style="padding-left: 5%">
      <b>»becoming a pillar«</b><br>
      <i>5-meter U-profile steel, wax, weight</i><br>
      Becoming in the static relationship of weight, a meditation on structures of support.
      <table style="width:100%;">
        <tr>
          <td style="width:33%"><a href="/art/Wien/Angewandte/Festival22/resized/becoming-a-pillar.jpg"><img src="/art/Wien/Angewandte/Festival22/thumbs/becoming-a-pillar.jpg" style="width:100%;"></a></td>
          <td style="width:33%"><a href="/art/Wien/Angewandte/Festival22/resized/becoming-a-pillar_close.jpg"><img src="/art/Wien/Angewandte/Festival22/thumbs/becoming-a-pillar_close.jpg" style="width:100%;"></a></td>
          <td style="width:33%"><a href="/art/Wien/Angewandte/Festival22/resized/becoming-a-pillar_back.jpg"><img src="/art/Wien/Angewandte/Festival22/thumbs/becoming-a-pillar_back.jpg" style="width:100%;"></a></td>
        </tr>
      </table>
    </div>
  </p>
  <p>
    <a class="anchor" id="Angewandte_Festival21"></a><b>Angewandte Festival 2021</b> (29.6. – 2.7.21)<br>
    <div style="padding-left: 5%">
      <b>»Stühle mit Abstand«</b><br>
      <i>chairs, 2 meters of steel, Abstand</i><br>
      What does it mean to find intimacy, when familiarity is obscured?  Two chairs are placed in an intimate acrobatic pose, a physical conversation mediated by 2 meters of steel.
      <table style="width:100%;">
        <tr>
          <td style="width:50%"><a href="/art/Wien/Angewandte/Festival21/chairs_front.gif"><img src="/art/Wien/Angewandte/Festival21/chairs_front.gif" style="width:100%;"></a></td>
          <td style="width:50%"><a href="/art/Wien/Angewandte/Festival21/chairs_side.gif"><img src="/art/Wien/Angewandte/Festival21/chairs_side_.gif" style="width:100%;"></a></td>
        </tr>
      </table>
    </div>
    <div style="padding-left: 5%">
      <b>»Stunted Objects«</b><br>
      <i>plaster, wood, steel, rust, friction</i><br>
      <table style="width:100%;">
        <tr>
          <td style="width:50%"><a href="/art/Wien/Angewandte/Festival21/object1.gif"><img src="/art/Wien/Angewandte/Festival21/object1.gif" style="width:100%"></a></td>
          <td style="width:50%"><a href="/art/Wien/Angewandte/Festival21/object2_tog.jpg"><img src="/art/Wien/Angewandte/Festival21/thumbs/object2_front_.jpg" onmouseover="this.src='/art/Wien/Angewandte/Festival21/thumbs/object2_side_.jpg'" onmouseout="this.src='/art/Wien/Angewandte/Festival21/thumbs/object2_front_.jpg'" style="width:100%;"></a></td>
        </tr>
      </table>
    </div>
  </p>
</p>
<br>

<h2><a class="anchor" id="sketching_Vienna"></a>Sketching in Vienna <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h2>
<p>
  While living in Vienna, I sketch regularly around the City: at museums, and recently, also outside.  The drawings are done in pencil, while the paintings are done with various watercolors.
  <table style="width:100%;">
    <tr>
    {% for j in (0..6) %}
      <td style="width:25%"><a href="/art/Wien/sketches/drawing/resized/02{{ 6 | minus: j }}.jpg"><img src="/art/Wien/sketches/drawing/thumbs/02{{ 6 | minus: j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 0 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    {% for j in (0..9) %}
      <td style="width:25%"><a href="/art/Wien/sketches/drawing/resized/01{{ 9 | minus: j }}.jpg"><img src="/art/Wien/sketches/drawing/thumbs/01{{ 9 | minus: j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 1 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    {% for j in (0..8) %}
      <td style="width:25%"><a href="/art/Wien/sketches/drawing/resized/00{{ 9 | minus: j }}.jpg"><img src="/art/Wien/sketches/drawing/thumbs/00{{ 9 | minus: j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 3 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    </tr>
    <tr>
    {% for j in (0..8) %}
      <td style="width:25%"><a href="/art/Wien/sketches/watercolor/resized/00{{ 9 | minus: j }}.jpg"><img src="/art/Wien/sketches/watercolor/thumbs/00{{ 9 | minus: j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 0 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    </tr>
  </table>
</p>

<h2><a class="anchor" id="portraiture"></a>Portraiture<sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h2>
<p>
  Here I have some attempts at portraiture.
  <table style="width:100%;">
    <tr>
      <td style="width:25%"><a href="/art/portraits/resized/001.jpg"><img src="/art/portraits/thumbs/001.jpg" style="width:100%;"></a></td>
      <td style="width:25%"><a href="/art/portraits/resized/002.jpg"><img src="/art/portraits/thumbs/002.jpg" style="width:100%;"></a></td>
      <td style="width:25%"><a href="/art/portraits/resized/003.jpg"><img src="/art/portraits/thumbs/003.jpg" style="width:100%;"></a></td>
      <td style="width:25%"><a href="/art/portraits/resized/004.jpg"><img src="/art/portraits/thumbs/004.jpg" style="width:100%;"></a></td>
    </tr>
  </table>
</p>
<br>

<h2><a class="anchor" id="drawing_TU"></a>Drawing/Painting at the TU <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h2>
<p>
  During my Doctoral studies (2016&ndash;), I am regularly participated in <i>Beobachtendes Zeichnen I/II</i> offered by the TU Wien.  The paintings are done in watercolors, while the drawings are done in pencil, and the duration of the poses varied, from about 5&ndash;15 minutes each.
  <table style="width:100%;">
    <tr>
    {% for j in (0..2) %}
      <td style="width:25%"><a href="/art/Wien/Akt/watercolor/resized/01{{ 2 | minus: j }}.jpg"><img src="/art/Wien/Akt/watercolor/thumbs/01{{ 2 | minus: j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 0 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    {% for j in (0..8) %}
      <td style="width:25%"><a href="/art/Wien/Akt/watercolor/resized/00{{ 9 | minus: j }}.jpg"><img src="/art/Wien/Akt/watercolor/thumbs/00{{ 9 | minus: j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 1 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    </tr>
    <tr>
    {% for j in (0..4) %}
      <td style="width:25%"><a href="/art/Wien/Akt/drawing/resized/00{{ 5 | minus: j }}.jpg"><img src="/art/Wien/Akt/drawing/thumbs/00{{ 5 | minus: j }}.jpg" style="width:100%;"></a></td>
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

<h2><a class="anchor" id="sculpture_TU"></a>Sculpture at the TU <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h2>
<p>
  So far during Doctoral studies (2016&ndash;), I participated in two Art/Design course at the TU Wien: the first, <i>Dreidimensionales Gestalten</i> (WS2018-19), was about "3-dimensional tilings", and the second, <i>Künstlerisches Projekt X</i> (SS2019), was aimed at developing art pieces, around the theme of "pairs/couples".
  <table style="width:100%;">
    <tr>
      <td style="width:25%"><a href="/art/Wien/sculpture/Paar/resized/Stunted-Ephemera.jpg"><img src="/art/Wien/sculpture/Paar/thumbs/Stunted-Ephemera.jpg" style="width:100%;"></a></td>
    {% for j in (1..9) %}
      <td style="width:25%"><a href="/art/Wien/sculpture/Paar/resized/00{{ j }}.jpg"><img src="/art/Wien/sculpture/Paar/thumbs/00{{ j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 3 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    {% for j in (0..9) %}
      <td style="width:25%"><a href="/art/Wien/sculpture/Paar/resized/01{{ j }}.jpg"><img src="/art/Wien/sculpture/Paar/thumbs/01{{ j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 2 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    {% for j in (0..2) %}
      <td style="width:25%"><a href="/art/Wien/sculpture/Paar/resized/02{{ j }}.jpg"><img src="/art/Wien/sculpture/Paar/thumbs/02{{ j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 0 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
     <td style="width:25%"><a href="/art/Wien/sculpture/3DG/Objekt.jpg"><img src="/art/Wien/sculpture/3DG/thumbs/Objekt.jpg" style="width:100%;"></a></td>
    </tr>
  </table>
</p>
<br>

<h2><a class="anchor" id="drawing_Bonn"></a>Drawing in Bonn <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h2>
<p>
  During my Master’s studies (2012&ndash;2015), I participated in <i>Aktzeichnen: Zeichnen nach Modell II</i> offered by the Atelier für Bildende Kunst of Universität Bonn.  The drawings are mostly charcoal, some with Conté, and the poses varied in length, from about 15&ndash;20 minutes each.
  <table style="width:100%;">
    <tr>
    {% for j in (1..9) %}
      <td style="width:25%"><a href="/art/Bonn/Akt/assorted/00{{ j }}.jpg"><img src="/art/Bonn/Akt/assorted/thumbs/00{{ j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 0 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    {% for j in (0..6) %}
      <td style="width:25%"><a href="/art/Bonn/Akt/assorted/01{{ j }}.jpg"><img src="/art/Bonn/Akt/assorted/thumbs/01{{ j }}.jpg" style="width:100%;"></a></td>
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

<h2><a class="anchor" id="sculpture_Princeton"></a>Sculpture at Princeton <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h2>
<p>
  During my undergraduate studies, I participated in a few studio Art courses (2010&ndash;2012), mainly doing sculptural work.  Below is a selection of my work from those courses; they are mixed-media, with predominant use of steel, wood, and twine.  A recurrent theme is exploring space through promoted negative space and constructed tension.
  <table style="width:100%;">
    <tr>
    {% for j in (1..9) %}
      <td style="width:25%"><a href="/art/Princeton/sculpture/resized/00{{ j }}.jpg"><img src="/art/Princeton/sculpture/thumbs/00{{ j }}.jpg" style="width:100%;"></a></td>
    {% assign row = forloop.index | modulo:4 %}
    {% if row == 0 %}
    </tr>
    <tr>
    {% endif %}
    {% endfor %}
    {% for j in (0..6) %}
      <td style="width:25%"><a href="/art/Princeton/sculpture/resized/01{{ j }}.jpg"><img src="/art/Princeton/sculpture/thumbs/01{{ j }}.jpg" style="width:100%;"></a></td>
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

<h2><a class="anchor" id="video_Princeton"></a>Video at Princeton <sup><a href="./#" style="font-size: 0.75em;">top</a></sup></h2>
<p>
  A piece (December, 2011) from a course during my undergraduate studies, entitled <i>Painting without Canvas</i>.
  <br><br>
  <img src="/art/Princeton/video/Draenge-titel-small.png" style="width:50%">
</p>
