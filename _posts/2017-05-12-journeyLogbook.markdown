---
layout:     post
title:      "Journey Logbook"
subtitle:   ""
date:       2017-05-12 12:00:00
author:     "Jakab Bence and Martinák Zalán"
header-img: "img/projektek/plane-1031681__340.jpg"
categories: projektek
---

<h2 class="section-heading">Cél</h2>

<p>Az ember a kezdetektől fogva vándorolt és gyűjtögetett. A modern kori ember is szeret vándorolni, azaz a mai értelemben utazni, és továbbra is megmaradt a gyűjtögetés, mint szenvedély, ami a leutazott kilométerek gyűjtését jelenti ma már. Mivel az ember hiú is, így szereti megmutatni embertársainak „gyűjtögetése” eredményét. Ezt az igényt hivatott kiszolgálni a Journey Logbook (Útinapló) weboldalunk, melyre az utazók feltölthetik repülős utazásaik alapadatait melyből az oldal egy színes, informatív, személyre szabott Útinaplót készít.</p>

<h2 class="section-heading">Működés</h2>

<p>A repülős utazások alapadatait (Honnan, Hová, Mikor) egy egyszerű szerkezetű MS Excel táblázatban kell első körben az utazónak rögzítenie.</p>

<!--kép tábla-->	
<a href="#">
    <img src="{{ site.baseurl }}/img/projektek/journeyLogbook_excel.png" class="img-responsive" alt="Post Sample Image">
</a>

<p>Az Excel fájl feltöltését követően egy informatív, dashboard jellegű összefoglaló kerül előállításra:</p>

<!--kép logbook-->	
<a href="#">
    <img src="{{ site.baseurl }}/img/projektek/journeyLogbook_page_top.jpg" class="img-responsive" alt="Post Sample Image">
</a>

<p>Itt térképes formában, ill. különböző grafikonokon keresztül kerülnek megjelenítésre az utazások:</p>

<!--kép charts-->	
<a href="#">
    <img src="{{ site.baseurl }}/img/projektek/journeyLogbook_page_charts.jpg" class="img-responsive" alt="Post Sample Image">
</a>	


<h2 class="section-heading">Megvalósítás</h2>

<p>Az oldal alapfunkciói Javascript-ben lettek megírva. A térképes megjelenítéshez a <a href="https://developers.google.com/maps/">Google Maps API</a>-jai, a grafikonok elkészítéséhez a <a href="https://developers.google.com/chart/">Google Charts</a> szolgáltatása lett használva.</p>

<!--<blockquote>The dreams of yesterday are the hopes of today and the reality of tomorrow. Science has not yet mastered prophecy. We predict too much for the next year and yet far too little for the next ten.</blockquote>

<a href="#">
    <img src="{{ site.baseurl }}/img/post-sample-image.jpg" class="img-responsive" alt="Post Sample Image">
</a>
<span class="caption text-muted">To go places and do things that have never been done before – that’s what living is all about.</span>

<p>Placeholder text by <a href="http://spaceipsum.com/">Space Ipsum</a>. Photographs by <a href="https://www.flickr.com/photos/nasacommons/">NASA on The Commons</a>.</p>
-->