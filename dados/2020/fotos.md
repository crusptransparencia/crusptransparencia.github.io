---
layout: default
title: Fotos 2020
description: Registro de fotografias, eventos, performances e outro
---

<!-- 
Em href="" colocar dentro das aspas o link 
do arquivo seja no drive ou no próprio github
LEMBRE-SE SEMPRE DE TORNÁ-LO PÚBLICO
-->

## CRUSP BLOCO F
<ul>
  {% for imagem in site.fotos.2020.blocoF %}
    <li>
      <img src="{{ imagem.url }}">
    </li>
  {% endfor %}
</ul>