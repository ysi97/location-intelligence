+++
title = "My presentation"
outputs = ["Reveal"]

[reveal_hugo]
theme = "blood"
+++

<style>
    .reveal section p {
    display: inline-block;
    font-size: 0.5em;
    line-height: 1.2em;
    vertical-align: top; 
    text-align: left;
  }
</style>



<h3 class="r-fit-text">Do cuisine types reflect</h3>
<h2 class="r-fit-text" style="color: tomato">Demographis</h2>
<h3 class="r-fit-text">of surrounding neighborhoods?</h4>

<h6 style="color: tomato">(a stack of images / media)</h6>

Yuhui SI, Viz Tech 2021Spring, Instructed by Carlo Bailey

---
{{< slide background-image="base1.png" >}}


<h6 style="color: white"> "The paradigmatic identification of black folks with soul food reflects the historical formation of urban ghettos by migration, racial segregation, and economic inequality".</h6>

Harris, 2011

https://bucketlisters.com/blog/267-70-black-owned-businesses-and-restaurants-in-nyc

---

{{< slide background-image="base2.png" >}}


<h6 style="color: white"> "Are new restaurants in some ways “post-racial” spaces? In city after city, demographic changes, including the growing presence and diversity of immigrants, intersect with the media discourse ... "</h6>

Sharon Zukin. Restaurants as “Post Racial” Spaces, Soul Food and Symbolic Eviction in Bedford‑Stuyvesant (Brooklyn). Dans Ethnologie française 2014/1 (Vol. 44), pages 135 à 147

A collection of podcasts

https://www.nycfoodpolicy.org/a-collection-of-podcasts-on-race-and-food/

---


### Methods: 
<h6 style="color: tomato">Parsing, Clustering and Correlation</h6>



step 1. Collect the NYC restaurants point dataset from google map parsing.

step 2. Group the restaurant data by cuisine frequency at the level of NYC zipcode. 

step 3. Correlation analysis between the retaurant clustering result and demographic attributes of the zipcode level (race, income, health, education).

---

##### Ranking of cuisines in the New York City

<img data-src="bar2.png" width="700">


---

{{< slide background-image="fig1_dot2-01.png" >}}

<h3 style="color: white"> Clustering Analysis: </h3>

<h5 style="color: white"> Do types of cuisine aggregate in certain neighborhoods?: </h5>


---

##### K-means clustering, distance = 5

<img data-src="fig_cluster5.png" width="500">

---
##### K-means clustering, distance = 10

<img data-src="fig_cluster10.png" width="500">

---

### Correlation Analysis

The correlation charts between cuisine types and other socioeconomic features: 

<h5 style="color: tomato">race & income</h5>

<img src="fig_race.png" width="450">

<img src="fig_inc.png" width="450">


---

### Roaming in the food space


The interconnections between cuisines and other socio-economic patterns of surrounding communities can shed light on community-scale equity pratices. 

While the complex system is is still to be explored, this project reveals a stand point for systematic research in the future. 

###### More Links:

https://ny.eater.com/2020/9/11/21432343/auxilio-space-culinary-center-brooklyn

https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0217341

https://news.cornell.edu/stories/2021/04/seminar-explore-racial-and-food-justice-movements-new-york


