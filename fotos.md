---
layout: default
title: Fotos
description: Registro de fotografias, eventos, performances e outros
---

<!-- 
Em href="" colocar dentro das aspas o link 
do caminho do arquivo fotos.md do respectivo ano
-->

# Descubra as fotos ao longo dos anos
* <a href="\dados\2020\fotos">2020</a>
* <a href="\dados\2019\fotos">2019</a>
* <a href="\dados\2018\fotos">2018</a>
* <a href="\dados\2017\fotos">2017</a>

## CRUSP BLOCO F
<ul>
  {% for imagem in site.fotos.2020.blocoF %}
    <li>
      <img src="{{ imagem.url }}">
	  <p>{{ imagem.url }}</p>
    </li>
  {% endfor %}
</ul>