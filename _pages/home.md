---
title: "SSLab - Home"
layout: default
excerpt: "System Security Lab at Sunkyunkwan University."
sitemap: false
permalink: /
---

# Welcome to SSLab!

---

<!-- divider -->
<div class="row">
<!-- Description -->
  <div id="homeid" class="col-golden-lg" style="padding-right:0px;">

  <!-- Carousel code -->
  <div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="5000" data-pause="hover" >
          <!-- Menu -->
        <ol class="carousel-indicators">
            <li data-target="#carousel" data-slide-to="0" class="active"></li>
            <li data-target="#carousel" data-slide-to="1"></li>
            <li data-target="#carousel" data-slide-to="2"></li>
            <li data-target="#carousel" data-slide-to="3"></li>
            <li data-target="#carousel" data-slide-to="4"></li>
            <li data-target="#carousel" data-slide-to="5"></li>
        </ol>  
        <!-- Items -->
        <div class="carousel-inner" role="listbox" markdown="0">
            <div class="item active">
                <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/hackathon.jpg" alt="Slide 1" />
            </div>
            <div class="item">
                <img  src="{{ site.url }}{{ site.baseurl }}/images/carousel/lab-space.jpg" alt="Slide 2" />
            </div>
            <div class="item">
                <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/namespace.jpg" alt="Slide 2" />
            </div>
        </div>

    <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>

  </div>

---

<div class="content-block">
시스템 보안 연구실 (SSLab)은 열정 있는 학생들을 기다리고 있습니다. 저희 연구실은 뭔가를 만들고, 고장내고, 고치는 걸 좋아하는 자신도 모르게 해커 기질을 가진 여러분들을 찾고 있습니다. SSLab은 소프트웨어 및 시스템 보안 분야 연구를 중점적으로 연구하지만, 학생 개인의 연구 분야 선택에 최대한 자유를 보장하고 있기도 합니다. 또한, 체계적인 신입생 교육 프로그램을 통해 자신의 연구 주제를 만들어 갈 수 있도록 지원합니다. SSLab의 철학은 구성원 개개인이 연구를 하는 가장 큰 동기부여가 재미가 되도록 하는 것입니다. 현재 저희 연구실은 아래와 같은 포지션을 모집하고 있습니다:

We are looking for passionate students who would be interested in doing research at SSLab. The most important qualification that we want from you is that you inherently enjoy hacking and fixing stuff. While SSLab focuses on software and systems security, the most important criteria in choosing a student research topic is that you have fun exploring the topic. So, do not hesitate to talk to us if you are interested:) Currently, I have the following positions open:

- Undergraduate Research Internship (학부연구생)
- Masters Students
- Doctoral Students
- Post-Doctoral Researchers
</div>
</div>
<div id="newsid" class="col-golden-sm">
{% include news.html %}
</div>
</div>

<!-- Remaining sections -->
<!-- Research -->

{% include_relative research.md %}

<!-- Members -->

{% include_relative team.md %}

<!-- Publications -->

{% include_relative publications.md %}

<!-- Courses -->

{% include_relative courses.md %}

<!-- Courses -->

{% include_relative ctf.md %}
