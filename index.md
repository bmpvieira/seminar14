## Crowdsourcing gene predictions & estimating population sizes

[bmpvieira.com/seminar14](//bmpvieira.com/seminar14)


Bruno Vieira | <i class="fa fa-twitter"></i> [@bmpvieira](//twitter.com/bmpvieira)

<img src="img/Queen_Mary,_University_of_London_logo.svg" alt="QMUL" style="float: left; padding: 1%; max-width: 26%; vertical-align: text-bottom;" />
<img src="img/new-bbsrc-colour-cmyk.svg" alt="BBSRC" style="float: left; padding: 1.5%; max-width: 25%; vertical-align: text-bottom;" />

---
## <span style="font-size: 1.5em;">Bioinformatics & Population Genomics</span>

---

### <span style="font-size: 1.5em;">Initially address two issues</span>

<br>
<span class="fragment" style="font-size: 1.5em;">Scaling up gene prediction</span>

<br>

<span class="fragment" style="font-size: 1.5em; line-height: 1.3em;">Infer the efective population size history in insects with the PSMC method [(Li, 2011)](//dx.doi.org/10.1038/nature10231).</span>


---

## Gene prediction?

---

<section data-background="img/dalliance.png"></section>

---

### Why is this important?

<span class="fragment" style="font-size: 1.5em; line-height: 1.3em;">Genes are the basic building block of organisms</span>

---

### How?

<img class="stretch" style="max-width: 75%;" src="img/gene-prediction-models.png" alt="Gene prediction models" />
<hr>
<small>
Gene prediction models
 [(Sleator, 2010)](//dx.doi.org/10.1016/j.gene.2010.04.008)
</small>

---

<section data-background="img/MAKER.jpg"></section>

---

<section data-background="img/ngs.png"></section>

---

> <span style="font-size: 2em; line-height: 1.2em;">Web application to crowdsource gene prediction </span>

<i class="fa fa-github-alt"></i> [github.com/yeban/afra](//github.com/yeban/afra)

---

## Crowdsource?

---

### Crowd + Outsource

<!-- <img src="img/crowd.jpg" alt="From: http://www.flickr.com/photos/jamescridland/613445810/sizes/z/" style="max-width: 90%;" /> -->


<section data-background="img/crowd-original-background.jpg">
  <img class="stretch" src="img/crowd.jpg" alt="From: http://www.flickr.com/photos/jamescridland/613445810/sizes/z/" style="max-width: 100%;" />
</section>

---

### Citizen Science

<!-- <img src="img/citizen_science-background.jpg" alt="From: http://www.jamesborrell.com/10-lessons-from-a-year-of-citizen-science-my-talk-from-the-citizen-cyberscience-summit" style="max-width: 90%;" /> -->

<section data-background="img/citizen_science-background.jpg">
  <img src="img/citizen_science.jpg" alt="From: http://www.jamesborrell.com/10-lessons-from-a-year-of-citizen-science-my-talk-from-the-citizen-cyberscience-summit/" style="max-width: 75%;" />
  <p>
    <small>
      James Borrell | <i class="fa fa-twitter"></i> [@James_Borrell](//twitter.com/James_Borrell)
      <br>
      Citizen Cyberscience Summit 2014 | <i class="fa fa-twitter"></i> [#ccs14](//twitter.com/#ccs14)
    </small>
  </p>
</section>


---

### Self-reward helping Science

Zooniverse success

<img src="img/zooniverse.png" alt="From: http://infobeautiful2.s3.amazonaws.com/goggle_boxes.png" style="max-width: 90%;" />

---

### Science? I don't care...

<br>
<img class="stretch" src="img/lazy_cat.jpg" alt="From: http://www.jenniferhudson.com/us/photos/my-lazy-cat" style="width: 70%;" />

---


### Cognitive surplus

<img src="img/goggle_boxes.png" alt="From: http://infobeautiful2.s3.amazonaws.com/goggle_boxes.png" style="width: 65%;" />

<small>
[Shirky, 2010](http://www.informationisbeautiful.net/2010/cognitive-surplus-visualized)
</small>

---

## Gamification

---

### Gamification

> <span style="font-size: 1.7em; line-height: 1.1em;"> A way to engage users into solving a problem by adding game mechanics to it</span>

---

### Useless game - Flappy bird

50 milion downloads

<img src="img/flappy.png" alt="Flappy bird screenshot" style="max-width: 60%;" />

<small>
<i class="fa fa-link"></i> [flappybird.io](//http://flappybird.io)
</small>

---

### Useful - Genes In Space

<img src="img/cancerresearchuk-merge.png" alt="Cancer Research UK screenshot" style="width: 100%;" />
<small>
<i class="fa fa-link"></i> [http://www.cancerresearchuk.org](//www.cancerresearchuk.org/support-us/play-to-cure-genes-in-space)
</small>

---

<section data-background="img/afra-demo-tutorial.png"></section>

---

<section data-background="img/afra-demo-editing.mov.gif"></section>

---

<section data-background="img/afra-demo-tutorial-highlight.png"></section>

---

## Previous work

---

### Scale up and Gamify another Open Source project

<i class="fa fa-github-alt"></i> [gmod/apollo](//github.com/gmod/apollo)
→
<i class="fa fa-github-alt"></i> [yeban/afra](//github.com/yeban/afra)

<br>

![Anurag Priyam](img/anurag.jpeg) Anurag Priyam | <i class="fa fa-twitter"></i> [@yeban](//twitter.com/yeban)

---

## Current work

---


### Scale up
<p style="clear: left;">
Move most of the logic to the browser
</p>

<img src="img/stack_gmod.png" alt="BBSRC" style="float: left; padding: 1%; max-width: 45%; vertical-align: text-bottom;" />
<img src="img/stack_afra.png" alt="BBSRC" style="float: left; padding: 1%; max-width: 46%; vertical-align: text-bottom;" />

---

### Scale up
Biology logic on the browser

![bionode](img/bionode.png)

<i class="fa fa-github-alt"></i> [github.com/bionode/bionode](//github.com/bionode/bionode)

---

### Gamification

Dashboad mockup

<img style="max-width: 80%;" src="img/2013-11-12_afra_dashboard_mockup.png" alt="Dashboard mockup" />

---


### Machine Learning

Use data generated by users to improve gene prediction models

<section data-background="img/machine-learning-background.png">
  <a href="//speakerdeck.com/ttfnrob/zooniverse-citizen-cyberscience-summit-2014?slide=36" target="_blank">
  <img src="img/machine-learning.png" alt="From: https://speakerdeck.com/ttfnrob/zooniverse-citizen-cyberscience-summit-2014" style="max-width: 65%;" />
  </a>
  <p>
    <small>
      Robert Simpson | <i class="fa fa-twitter"></i> [@orbitingfrog](//twitter.com/orbitingfrog)
      <br>
      Citizen Cyberscience Summit 2014 | <i class="fa fa-twitter"></i> [#ccs14](//twitter.com/#ccs14)
    </small>
  </p>
</section>


---

## PSMC

---

### Effective population size?

<!-- > "the number of breeding individuals in an idealised population that would show the same amount of dispersion of allele frequencies under random genetic drift or the same amount of inbreeding as the population under consideration" Wright, 1931 -->

> <span style="font-size: 1.4em; line-height: 1.1em;"> Theoretical number of individuals that contribute gametes to the next generation</span>


---

### Why is this important?

<br>
<span class="fragment" style="font-size: 1.5em;">Measure of genetic diversity</span>

<br>

<span class="fragment" style="font-size: 1.5em; line-height: 1.3em;">Affects selection efficiency</span>

---

### Used
<div style="display: block;">
<img style="max-width: 20%; float: left; padding-right: 2%;" src="img/polar-bear.jpg" alt="http://en.wikipedia.org/wiki/File:Polar_Bear_-_Alaska.jpg" />

<p>Effect of historical climate changes <span style="font-size:.5em;">(Miller, 2012)</span></small></p>
</div>

<div style="display: block; clear: left; padding-top: 2%;">
<img style="max-width: 20%; float: left; padding-right: 2%;" src="img/panda.jpg" alt="http://en.wikipedia.org/wiki/File:Grosser_Panda.JPG" />

<p>Measure the impact of anthropogenic activity<span style="font-size:.5em;">(Zhao, 2013)</span></small></p>
</div>

<div style="display: block; clear: left; padding-top: 2%;">
<img style="max-width: 20%; float: left; padding-right: 2%;" src="img/wolf2.jpg" alt="http://upload.wikimedia.org/wikipedia/commons/9/9d/Grauwolf_P1130275.jpg" />

<p>Discover unexpected population bottlenecks <span style="font-size:.5em;">(Freedman, 2014)</span></small></p>
</div>

<div style="display: block; clear: left; padding-top: 2%;">
<img style="max-width: 20%; float: left; padding-right: 2%;" src="img/human2.jpg" alt="http://en.wikipedia.org/wiki/File:Uomo_Vitruviano.jpg" />

<p>Detect the time of divergence between populations <span style="font-size:.5em;">(Li, 2011)</span></small></p>
</div>

---

### How to measure?

<br>
<span class="fragment" style="font-size: 1.5em;">Previously hard to do</span>

<ul>
<li class="fragment">Highly stochastic nature of inbreeding and genetic drift</li>
<li class="fragment">Other confounding factors</li>
<li class="fragment">Needs a lot of specific data</li>
</ul>

<br>

<span class="fragment" style="font-size: 1.5em; line-height: 1.3em;">Now from a diploid genome</span>

---

### PSMC

<img class="stretch" style="max-width: 100%;" src="img/psmc.png" alt="WebApollo" />

[Li, 2011](//dx.doi.org/10.1038/nature10231)

---

## Hasn't been used in insects a lot...<span class="fragment" data-fragment-index="0"> until now!</span>
<img class="fragment" data-fragment-index="0" src="img/ant.jpg" alt="From: http://commons.wikimedia.org/wiki/File:Ant_head_closeup.jpg" style="max-width: 50%" />

---
### Use PSMC to answer some evolutionary questions

---

## Is the effective population size in solitary insects > social?

---

### Experimental design
Run PSMC across a wide range of social insects and their solitary relatives

<img src="img/WeaverAntDefense.JPG" alt="From: http://upload.wikimedia.org/wikipedia/commons/8/85/WeaverAntDefense.JPG" style="max-width: 25%" />
<img src="img/Honeybee_landing_on_milkthistle02.jpg" alt="From: http://upload.wikimedia.org/wikipedia/commons/e/e0/Honeybee_landing_on_milkthistle02.jpg" style="max-width: 23%" />

<img src="img/Coptotermes_formosanus_shiraki_USGov_k8204-7.jpg" alt="From: http://upload.wikimedia.org/wikipedia/commons/d/d3/Coptotermes_formosanus_shiraki_USGov_k8204-7.jpg" style="max-width: 16%" />
<img src="img/Bush_Cockroach.jpg" alt="From: http://upload.wikimedia.org/wikipedia/commons/c/ca/Bush_Cockroach.jpg" style="max-width: 32%" />

---

## Current work

---

### Reproducing published results to master PSMC

<img src="img/human.jpg" alt="https://upload.wikimedia.org/wikipedia/commons/1/11/Uomo_Vitruviano.jpg" style="max-width: 25%" /><img src="img/wolf.jpg" alt="https://upload.wikimedia.org/wikipedia/commons/f/ff/Wolf%2C_voor_de_natuur%2C_Saxifraga_-_Jan_Nijendijk.5097.jpg" style="max-width: 39%" />

* [Li, 2011](//dx.doi.org/10.1038/nature10231)
* [Freedman, 2014](//dx.doi.org/10.1371/journal.pgen.1004016)


---

### Thank you!

<img style="max-width: 15%;" src="img/bmpvieira.png" alt"Bruno Vieira"/>
Bruno Vieira | <i class="fa fa-twitter"></i> [@bmpvieira](//twitter.com/bmpvieira)

<img style="max-width: 15%;" src="img/anurag.jpeg" alt"Anurag Priyam" />
Anurag Priyam | <i class="fa fa-twitter"></i> [@yeban](//twitter.com/yeban)

<img style="max-width: 15%;" src="img/yannick.jpg" alt"Yannick Wurm" />
Yannick Wurm | <i class="fa fa-twitter"></i> [@yannick__](//twitter.com/yannick__)

[bmpvieira.com/seminar14](//bmpvieira.com/seminar14)

<small>
© 2014 [Bruno Vieira](//bmpvieira.com) [CC-BY 4.0](//creativecommons.org/licenses/by/4.0/deed.en_US)
</small>

---

<div style="text-align: left; line-height:2em;">

<span style="font-size: 1.2em;">Crowdsource gene prediction</span>
<ul style="text-align: left; line-height:1.5em;">
<li> Address data "deluge" in gene prediction</li>
<li> Scale up by moving logics to browser</li>
<li> Gamify to tap into Cognitive Surplus</li>
</ul>

<span style="font-size: 1.2em;">Effective pop. size history in insects</span>
<ul style="text-align: left; line-height:1.5em;">
<li> Deploy the PSMC on the servers</li>
<li> Master PSMC by reproducing results</li>
<li> Effective pop. size solitary insects > social?</li>
</ul>


</div>

---
