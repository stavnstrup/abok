---
title: Glossary
docid: "glossary"
fullpath: "/naf/glossaryy/"
layout: "specification"
---

{%for glossentry in site.data.glossary %}
<div class="glossentry">
  <h3>{{glossentry.term}}</h3>
  {%if glossentry.def %}
  <p>{{glossentry.def}}</p>
  {%endif%}
  {%if glossentry.alternatives %}
  <ol>
  {%for entry in glossentry.alternatives%}
  <li>{{entry.def}}</li>
  {%endfor%}
  </ol>
  {%endif%}
  {%if glossentry.list %}
  <ul>
  {%for entry in glossentry.list%}
  <li>{{entry.def}}</li>
  {%endfor%}
  </ul>
  {%endif%}
  {%if glossentry.note %}
  <p>{{glossentry.note}}</p>
  {%endif%}
  <p class="source">{{glossentry.source}}</p>
</div>
{%endfor%}
