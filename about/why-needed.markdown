---
layout: page
title: Why the Tools Ecosystem is needed
permalink: /about/why-needed
---
<head>
  <style>
  #particles-js {
   position: absolute;
   z-index: -1;
}
  .row {
    --bs-gutter-x: 1.5rem;
    --bs-gutter-y: 0;
    display: flex;
    flex-wrap: wrap;
    margin-top: 5rem;
    margin-right: 5rem;
    margin-left: 0rem;
}
  p { font-size: 17px; }
  </style>
</head>


<body>
<div id="particles-js" style="height: 100%; width: 100%; background-color: white;"></div>
<script src="//cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
<script>particlesJS.load('particles-js', '{{ baseurl }}/assets/js/particles2.json', function() {
   console.log('callback - particles.js config loaded');
 });</script>
<div class="container">
  <div class="row">
    <div class="col"><h5 class="text-end"><strong>Metadata: data about data</strong></h5></div>
    <div class="col"><p>In order to understand our efforts, we need to discuss about metadata. Metadata are data about data. They add context to the data and allow for complete and meaningful analysis.</p></div>
    <div class="w-100"></div>
    <div class="col"><h5 class="text-end"><strong>Rich metadata render science more complete.</strong></h5></div>
    <div class="col"><p>Most people would be familiar with this traditional concept:  in a clinical experiment where the concentration of a molecule is measured in patients, metadata would be the gender, the age, the physical activity, the weight of the patient and so forth.These metadata describe the initial dataset more completely.</p></div>
    <div class="w-100"></div>
    <div class="col"><h5 class="text-end"><strong>Metadata have grown to encapsulate the software the analyses the data.</strong></h5> </div>
    <div class="col"><p>However, nowadays metadata have been evolved to larger proportions. Metadata can be information about the dataset but also information about the tools that analyse the dataset or even about the training material that trains people to use the tools to analyse the dataset. It is an ever expanding domain. And this is great. The more rich are the metadata that describe all peripheral relations of a dataset, the more complete and open science becomes. Moreover, metadata for someone could be data for another. Nothing goes to waste, similar to an ecosystem...</p></div>
    <div class="w-100"></div>
    <div class="col"><h5 class="text-end"><strong>Metadata for one are data for another...similar to an ecosystem</strong></h5></div>
    <div class="col"><p>Today there are a lot of services that try to tackle the challenge of both raising the analysis standards but also turning research open to everyone. For example, there are services that find and catalogue all bioinformatic software available. There are services that test all the bioinformatic tools available online in an effort to rank their performance. There are services that allow the user to run their bioinformatic analysis by skipping entirely the command line through a graphical interface. And all these services generate their own set of metadata.</p></div>
    <div class="w-100"></div>
    <div class="col"><h5 class="text-end"><strong>Need to coordinate metadata and link all these services so that people will have access to all information readily</strong></h5></div>
    <div class="col"><p>This create a challenge for the user, to be able to navigate and to know about all these services. This need created the Tools Ecosystem. We are a service running on the background that pulls metadata from all these services, enriches them, syncs them and links them. That way the user will be able to have ALL relevant information about the tools they use to analyse their datasets.</p></div>
    <div class="w-100"></div>
    <div class="col"><h3 class="text-center"><strong>Science becomes more complete, more open and more FAIR for everyone.</strong></h3></div>
  </div>
</div>
</body>

