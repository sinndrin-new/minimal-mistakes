---
layout: single
title: "Kontakt"
excerpt: "Kontaktieren Sie uns. Wir freuen uns."
slug: kontakt
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/ueber-uns/kontakt/2016-07-Fairphone_Inge_696-copy_WEB.jpg
  caption: "Foto: [**Fairphone**](https://www.fairphone.com)"
# feature rows
intro:
  - excerpt: 'Wir sind die sinndrin genossenschaft.'
fr_kontakt:
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
---

<!-- BEGIN script loading -->
<!-- BEGIN facebook -->
<div id="fb-root"></div>
<script>(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "//connect.facebook.net/de_DE/sdk.js#xfbml=1&version=v2.0";
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>
<!-- END facebook -->
<!-- END script loading -->

<!-- BEGIN Team -->
{% include feature_row id="intro" type="center" %}

<div class="float-group">
{% for author_hash in site.data.authors %}
{% assign author = author_hash[1] %}
{% if author.avatar %}
  <div class="float-left round-img mw-110">
    {% if author.avatar contains "://" %}
      {% assign author_src = author.avatar %}
    {% else %}
      {% assign author_src = author.avatar | relative_url %}
    {% endif %}

    {% if author.home %}
      {% if author.home contains "://" %}
        {% assign author_link = author.home %}
      {% else %}
        {% assign author_link = author.home | relative_url %}
      {% endif %}
      <a href="{{ author_link }}">
        <img src="{{ author_src }}" alt="{{ author.name }}" itemprop="image">
      </a>
    {% else %}
      <img src="{{ author_src }}" alt="{{ author.name }}" itemprop="image">
    {% endif %}
  </div>
{% endif %}
{% endfor %}
</div>

<hr>
<!-- END Team -->

<!-- {% include feature_row id="fr_kontakt" %} -->


<!-- BEGIN Kontakt -->
## Kontaktdaten
{:#kontaktdaten}

**sinndrin genossenschaft**<br/>
[Zunstrasse 11][gmaps-zunstrasse]{:target="_blank"}<br/>
[CH-8152 Glattbrugg][gmaps-zunstrasse]{:target="_blank"}

<i class='fas fa-fw fa-phone'></i> +41 44 534 64 54<br>
<i class='fas fa-fw fa-at'></i> [info@sinndrin.ch](mailto:info@sinndrin.ch)<br>

<i class='fas fa-fw fa-puzzle-piece '></i> [Persönliches Kennenlernen an einem unserer Spieleabende](/ueber-uns/spieleabend/)

<b>Fairphone Support:</b><br><i class='fas fa-fw fa-file-alt'></i> [Fairphone Support Seite](https://support.sinndrin.org/de)<br>
<i class='fas fa-fw fa-at'></i> [support@sinndrin.ch](mailto:support@sinndrin.ch)

MWST-Nr.: CHE-259.799.074 MWST<br>
<i class="fas fa-fw fa-info"></i> [Handelsregistereintrag](https://zh.chregister.ch/cr-portal/auszug/auszug.xhtml?uid=CHE-259.799.074){:target="_blank"}<br>
<i class='fas fa-fw fa-coins'></i> [Bankverbindung](#bankverbindung)

Wir sind am Montag, Mittwoch und Freitag während den üblichen Büroöffnungszeiten am besten erreichbar.
<!-- END Kontakt -->


<!-- BEGIN Social Profiles -->
## Soziale Netzwerke

<!-- BEGIN Facebook -->
### [<i class='fas fa-fw fa-facebook'></i> Facebook](https://www.facebook.com/sinndrin)
{:style="color:#3b5998;}
{:target="_blank"}
{:rel="sinndrin genossenschaft"}

<div class="fb-like-box" data-href="https://www.facebook.com/sinndrin" data-colorscheme="light" data-show-faces="true" data-header="true" data-stream="false" data-show-border="false"></div>
<!-- END Facebook -->

<!-- BEGIN Google+ -->
<div class="large-6 columns">
<h3><a style="color: red;" href="https://plus.google.com/+sinndringenossenschaftZürich" target="_blank" rel="sinndrin genossenschaft"><i class="fi-social-google-plus"></i> Google+</a></h3>
<!-- BEGIN Google+ Code -->
<script type="text/javascript" src="https://apis.google.com/js/plusone.js"></script>
<g:page href="https://plus.google.com/+sinndringenossenschaftZürich"></g:page>
<!-- END Google+ Code -->
</div>
<!-- END Google+ -->
</div>

<!-- TODO: ugly spacing -->
<br><br>

<div class="row">
<!-- BEGIN Twitter -->
<div class="large-6 columns">
<h3><a style="color:#55acee;" href="https://twitter.com/sinndrin" target="_blank" rel="sinndrin genossenschaft"><i class="fi-social-twitter"></i> Twitter</a></h3>
<!-- BEGIN Twitter Code -->
<a class="twitter-timeline"  href="https://twitter.com/sinndrin"  data-widget-id="502772720589746176">Tweets von @sinndrin</a>
    <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>


<!-- >END Twitter Code -->
</div>
<!-- END Twitter -->

<!-- BEGIN Weitere -->
<div class="large-6 columns">
<h3>Weitere Profile</h3>

<ul>
  <!-- BEGIN XING -->
  <li><h4><a style="color: green;" href="https://www.xing.com/companies/sinndringenossenschaft" target="_blank" rel="sinndrin genossenschaft">Xing</a></h4></li>
  <!-- >END XING -->
  <!-- BEGIN Github -->
  <li><h4><a style="color:#222;" href="https://github.com/sinndrin" target="_blank" rel="sinndrin genossenschaft"><i class="fi-social-github"></i> GitHub</a></h4></li>
   <!-- >END Github -->
  </ul>
</div>
<!-- END Weitere -->
</div>

## <i class='fas fa-fw fa-coins'></i> Bankverbindung
{:#bankverbindung}

IBAN: **CH43 0839 0032 4370 1000 1**

### Daten unserer Bank

* Name: **Alternative Bank Schweiz (ABS)**
* Kontonummer der sinndrin genossenschaft: **324.370.100-01**
* Postkonto: **46-110-7**
* Bankclearing: **8390**
* Swift Code: **ABSOCH22**


<!-- MARKDOWN LINKS -->
[gmaps-zunstrasse]: https://goo.gl/maps/W29ouJoYX8F2
