## People

---


### Leader
---

<div id="gridid" class="col-sm-12">

{% for member in site.data.team_leaders %}
<div class="row">

<div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/profile-pic/{{ member.photo }}" class="img-responsive" width="180px" style="float: left" />
</div>

<div class="col-sm-9 clearfix">
  <h4><b>{{member.name }}</b></h4>
  <h4>{{member.job}}</h4>
{%- if member.email-pic -%}
  <img src="{{ site.url }}{{ site.baseurl }}/images/emails/{{member.email-pic}}" style="width: 150px; height: auto; margin-top: 0px;  box-shadow: None;"><br/>
{%- endif -%}

<!--   <i>{{ member.info }}<br>email: <{{ member.email }}></i>
 -->
{%- if member.page -%}
<a href="{{member.page}}" >
<b>Personal Page</b>
</a>
{%- endif -%}

{%- if member.cv -%}
&nbsp;
<a href="{{member.cv}}">
<b>CV</b>
</a>
{%- endif -%}
<br>

<div class="member-description">
{{member.description}}
</div>
</div>
</div>

{% endfor %}
</div>

### PhD/MSc Students

---

<div id="gridid" class="col-sm-12">

{% assign number_printed = 0 %}
{%- for member in site.data.team_phd -%}
{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/profile-pic/{{ member.photo }}" onerror="this.src='{{ site.url }}{{ site.baseurl }}/images/profile-pic/bio-photo.jpg'" class="img-responsive" width="150px" style="float: left" />
  <h4><b>{{member.name }}</b></h4>
  <h4>{{member.job}}</h4>
  
{%- if member.email-pic -%}
  <img src="{{ site.url }}{{ site.baseurl }}/images/emails/{{member.email-pic}}" style="width: 140px; height: auto; margin-top: 0px; margin-bottom: 0px; box-shadow: None;"><br/>
{%- endif -%}

<!--   <i>{{ member.info }}<br>email: <{{ member.email }}></i>
 -->

{%- if member.page -%}
<a href="{{member.page}}" >
<b>Personal Page</b>
</a>
{%- endif -%}

{%- if member.cv -%}
&nbsp;
<a href="{{member.cv}}">
<b>CV</b>
</a>
{%- endif -%}
<br>

<div class="member-description">
{{member.description}}
</div>
</div>
{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}

</div>
{% endif %}

{%- endfor -%}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}

</div>
{% endif %}
</div> 

### Undergraduate Interns

---

<div id="gridid" class="col-sm-12 clearfix">

{% assign number_printed = 0 %}
{%- for member in site.data.team_interns -%}
{% assign even_odd = number_printed | modulo: 2 %}

{%- if even_odd == 0 -%}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/profile-pic/{{ member.photo }}" class="img-responsive" width="150px" style="float: left" />
  <h4><b>{{member.name }}</b></h4>
  <h4>{{member.job}}</h4>
  
{%- if member.email-pic -%}
  <img src="{{ site.url }}{{ site.baseurl }}/images/emails/{{member.email-pic}}" style="width: 150px; height: auto; margin-top: 0px; box-shadow: None;"><br/>
{%- endif -%}

<!--   <i>{{ member.info }}<br>email: <{{ member.email }}></i>
 -->

{%- if member.page -%}
<a href="{{member.page}}" >
<b>Personal Page</b>
</a>
{%- endif -%}

{%- if member.cv -%}
&nbsp;
<a href="{{member.cv}}">
<b>CV</b>
</a>
{%- endif -%}
<br>

<div class="member-description">
{{member.description}}
</div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}

</div>
{% endif %}

{%- endfor -%}
</div>

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}

</div>


{%- endif -%}
<!-- empty space -->
  
<!--  -->
