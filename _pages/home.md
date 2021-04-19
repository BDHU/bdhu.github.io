---
title: "Bodun Hu"
layout: homelay
excerpt: "Bodun Hu's website"
sitemap: false
permalink: /
---

<!-- [<img src="images/bsd.PNG" class="headerimagebox" alt="Github repo">](https://github.com/yihui/hugo-xmin) -->

<img src="images/me.jpg" style="margin-left:25px;max-width:210px;min-width:20%;float:right;" alt="Github repo" />

Department of Computer Science  
University of Texas at Austin  
2317 Speedway  
Austin, TX 78712-1757  

**Email**: bodunhu@utexas.edu  
**Twitter**: [@BodunHu](https://twitter.com/BodunHu)  
**Github**: [BDHU](https://github.com/BDHU)  
**Phone**: (512) 517-0598  
**CV**: [[pdf]]({{ site.url }}/cv.pdf )

Interests: Operating systems, architecture, heterogeneity, virtualization, accelerators, networks, machine learning systems, and distributed systems

---

My name is Edward and I am a Computer Science student in the [SCEA](https://github.com/utcs-scea) group at [University of Texas at Austin](https://www.utexas.edu/). I will be joining [WISR](https://wisr.cs.wisc.edu/) lab under the supervision of professor [Aditya Akella](http://pages.cs.wisc.edu/~akella/) for my PhD this following Fall.
I'm fortunate to work with professor [Chris Rossbach](http://www.cs.utexas.edu/~rossbach/) on modern GPU benchmarking and virtualization for OS kernels.
I also worked with professor [Simon Peter](https://www.cs.utexas.edu/~simon/) on programmable switches.
Occasionally I would write [blogs](https://bdhu.github.io/blog/) to share topics I find interesting.
Recently, I'm trying to pick up my workout routine. If you want to hit the gym or need a spotter, hit me up:)

---

### Papers

{% for publi in site.data.publist limit:8%}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

[Complete Publications](/publications/)

---

### Teaching Experience

Spring 2020: [Multicore Operating System Implementation (378)](https://www.cs.utexas.edu/~simon/378/)

---

### Awards

2020 ISPASS Student Travel Award  
Research Distinction by the College of Natural Sciences.

---

<img style="max-width:70%;min-width:65%" src="https://raw.githubusercontent.com/BDHU/Page_pics/master/wordcloud.png"/>
<!-- ![iage](/wordcloud.svg#left) -->

<!-- <div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="5000" data-pause="hover" >
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li>
        <li data-target="#carousel" data-slide-to="2"></li>
        <li data-target="#carousel" data-slide-to="3"></li>
        <li data-target="#carousel" data-slide-to="4"></li>
        <li data-target="#carousel" data-slide-to="5"></li>
        <li data-target="#carousel" data-slide-to="6"></li>
    </ol>

    <div class="carousel-inner" markdown="0">

        <div class="item active">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/Fig_Science_Web.jpg" alt="Slide 1" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/QPI_Rh.jpg" alt="Slide 2" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/NoiseCover2.jpg" alt="Slide 3" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SaphireSTM2.jpg" alt="Slide 4" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/lab.jpg" alt="Slide 5" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/SmartTipSide.jpg" alt="Slide 6" />
        </div>       
         <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/cake_web.jpg" alt="Slide 7" />
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
</div> -->



<!-- <figure class="fourth">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/Logo_Leiden.jpg" style="width: 210px">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/Logo_Nanofront.jpg" style="width: 110px">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/Logo_NWO.jpg" style="width: 120px">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/Logo_ERC.jpg" style="width: 110px">
</figure> -->
