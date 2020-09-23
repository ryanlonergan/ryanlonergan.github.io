---
layout: page
title: Mini-Projects
description: >
  This page contains some projects of mine that cover a variety of topics, but are smaller in scale
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

.button {
  display: block;
  margin-left: auto;
  margin-right: auto;
  center;
  width: 175px;
}

.button:hover{
  position: relative;
  top: -1px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.15), 0 6px 10px 0 rgba(0, 0, 0, 0.15);
}


</style>

[&bull; Rock Paper Scissors Image Classification](#rps)<br>
[&bull; Iris Classification](#Iris)<br>
[&bull; Customer Clustering](#customer)<br>
{:.note title="Table of Contents"}
{:toc}

<br><br>

The pages for these projects are not fully finished and are under construction. I am just linking them now in case someone is curious about my work. Check back later if you would like to see the completed versions.
{:.note}

<br>


<img src="/assets/img/miniprojects/miniprojects_cover.jpg"  alt="Mini-Projects" class="banner">




<br>

<a class="anchor" id="rps"></a>
<p style="display: inline;">
  <b>
  <a href="/portfolio/miniprojects/rps_classification/">Rock Paper Scissors Image Classification</a>
  </b> &nbsp;&nbsp;&nbsp;
  <img src="/assets/icons/python.png" width="75">
  <ul><li style="list-style-type: none;">
  This project took images of rock paper scissors gestures and created image classification models  through Keras with TensorFlow. It developed convolutional and full connected neural networks to compare performance against the different methods.
  <div class="row">
    <div class="column50">
      <a href="/portfolio/miniprojects/rps_classification/">
        <img src="/assets/img/project_button.png" alt="View Project" class="button">
      </a>
    </div>
    <div class="column50">
      <a href="https://github.com/ryanlonergan/portfolio_repo/tree/master/rps_classification" target="_blank">
        <img src="/assets/img/github_button.png" class="button" alt="View on GitHub">
      </a>
    </div>
  </div>
</li></ul></p>

<br>

<p style="display: inline;">
  <b>
  <a href="/portfolio/miniprojects/iris_classification/">Iris Classification</a>
  &nbsp;&nbsp;&nbsp;
  <img src="/assets/icons/python.png" width="75">
  </b>
  <ul><li style="list-style-type: none;">
    This project examined the iris dataset and explored different methods for classification, including: a basic decision tree classifier, Random Forest, AdaBoost and Gradient Boosting. It also examined different hyper-parameters to find the best model through GridSearchCV.
  <div class="row">
    <div class="column50">
      <a href="/portfolio/miniprojects/iris_classification/">
        <img src="/assets/img/project_button.png" alt="View Project" class="button">
      </a>
    </div>
    <div class="column50">
      <a href="https://github.com/ryanlonergan/portfolio_repo/tree/master/iris_classification" target="_blank">
        <img src="/assets/img/github_button.png" class="button" alt="View on GitHub">
      </a>
    </div>
  </div>
</li></ul></p>

<br>

<p style="display: inline;">
  <b>
  <a href="/portfolio/miniprojects/customer_clustering/">Customer Clustering</a>
  </b> &nbsp;&nbsp;&nbsp;
  <img src="/assets/icons/python.png" width="75">
  <ul><li style="list-style-type: none;">
  This project took a customer dataset and explored how the number of clusters affected its results. It used dendograms and SSE curve charts to determine the optimal number of clusters for a 2-D subset of the data.
  <div class="row">
    <div class="column50">
      <a href="/portfolio/miniprojects/customer_classification/">
        <img src="/assets/img/project_button.png" alt="View Project" class="button">
      </a>
    </div>
    <div class="column50">
      <a href="https://github.com/ryanlonergan/portfolio_repo/tree/master/customer_clustering" target="_blank">
        <img src="/assets/img/github_button.png" width="200" class="button" alt="View on GitHub">
      </a>
   </div>
  </div>
