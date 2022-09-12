## Publications 

---

<div class="content-block">

{% for publi in site.data.publist %}
  **{{ publi.title }}** <br>
  *{{ publi.authors }}*<br>
  **{{ publi.conference }}**
{%- if publi.info -%}
  , {{ publi.info }}
{%- endif -%}
  &nbsp;

{%- if publi.paper -%}
  [**Full Paper**]({{ publi.paper }}) &nbsp;
{%- endif -%}
{%- if publi.talk -%}
  [**Talk**]({{ publi.talk }})
{%- endif -%}

<br><br>

{% endfor %}

</div>
