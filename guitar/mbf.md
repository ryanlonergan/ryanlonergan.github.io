---
layout: page
title: Modified Bazz Fuss
description: >
  Building a Modified Bazz Fuss
hide_description: true
sitemap: false
---

<style>

.banner {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  center;
}

.justify {
  text-align: justify;
}

.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}

* {
  box-sizing: border-box;
}

.column25 {
  float: left;
  width: 25%;
  padding: 10px;
}

.column30 {
  float: left;
  width: 30%;
  padding: 10px;
}

.column40 {
  float: left;
  width: 40%;
  padding: 10px;
}

.column50 {
  float: left;
  width: 50%;
  padding: 10px;
}

.column60 {
  float: left;
  width: 60%;
  padding: 10px;
}

.column70 {
  float: left;
  width: 70%;
  padding: 10px;
}

.column75 {
  float: left;
  width: 75%;
  padding: 10px;
}

.row:after {
  content: "";
  display: table;
  clear: both;
}

@media screen and (max-width: 600px) {
  .column25 {
    width: 100%;
  }
  .column30 {
    width: 100%;
  }
  .column40 {
    width: 100%;
  }
  .column50 {
    width: 100%;
  }
  .column60 {
    width: 100%;
  }
  .column70 {
    width: 100%;
  }
  .column75 {
    width: 100%;
  }
}

</style>


* This unordered list will be replaced by the table of contents
{:toc}

This page is still a work in progress and still is missing sections. Check back later for more details!
{:.note}

<div style="text-align: center;">
  <img src="/assets/guitar/mbf/mbf_front_side.jpg"  alt="Modified Bazz Fuss" class="banner">
</div>



### Overview

(mention Big Muff Pi (BMP) somewhere)

<p class="justify">
  This pedal was my first design that I modified
</p>


### Etching

first time

designed and etched the board

etched the artwork




### Next Iteration

As this project was the first non-kit build I ever made, I learnt so much during the process. While I already made some changes and am happy with them, there are many more areas to further improve it.

<ul>
<b>Different Tone Control</b> - While the BMP has a great tone control, it does has some drawbacks. First, it is entirely passive which results in a volume loss. As this pedal can be quite loud, it is not a huge issue, but should still be noted. Secondly and more importantly, the BMP is known for scooped mids which may or may not work well for the desired sound. Some people love it and others hate it, so it just comes down to the player and the type of music they play. Some ideas include using a tone stack from a different pedal (like the ProCo Rat), switching the values for a mid-hump instead (possibly on a toggle switch) or bypassing the tone stack entirely (definitely on a toggle switch).
</ul>


<ul>
<b>Second Gain Stage</b> - As noted in the tone control section above, there is some volume loss from including it. In the BMP circuit that it comes from, there is a final gain section after it to make up for the loss, which can be replicated here. This idea can either be implemented as an "always on" solution or can be switched on or off with a footswitch. It does not even have to be the same circuit too as a boost could be a great addition. While the pedal is definitely not lacking in volume, playing around with other pedals before and after this one to experiment with different options would provide a good idea of what would sound best.
</ul>


<ul>
<b>Different Transistors</b> - The simplest, but most effective change is changing the transistor to a different type. In this pedal, I used a 2n5088, but there are many different options to explore. Some great candidates are the 2n3904 and the mpsa13, but many other options are viable, so socketing the transistor is a great idea. Just be careful of the individual pinouts.  
</ul>


### External Resources

Here are some resources I found useful during this project:

<ul>
<a href="https://home-wrecker.com/bazz.html" target="_blank">Home-Wrecker's, aka runoffgroove, article on the Bazz Fuss</a>
</ul>

<ul>
<a href="https://beavisaudio.com/techpages/bigmufftonecontrol/" target="_blank">Beavis Audio's article on the Big Muff Pi tone control</a>
</ul>

<ul>
<a href="https://www.electrosmash.com/big-muff-pi-analysis#link4" target="_blank">Electrosmash's tone control section of their article about the Big Muff Pi</a>
</ul>

<ul>
<a href="https://www.youtube.com/watch?v=HZAuhjt75X4" target="_blank">Brian Wampler's video on tone controls</a>
</ul>

<ul>
<a href="https://diy-guitar-effects.tumblr.com/etching
" target="_blank">DIY Guitar Effects' article on acid etching enclosures</a>
</ul>


____

### Supporting Figures

<figure>
  <img src="/assets/guitar/mbf/mbf_guts.JPG"  alt="MBF Guts">
  <figcaption>Internal PCB of pedal</figcaption>
</figure>
