---
layout: page
title: 
permalink: /about/
---
<head>
    <style>
        img {
            border: none !important;
            width: 600px;
            height: 400px;
            align: center;
        }
                #particles-js {
   position: absolute;
   z-index: -1;
}
    </style>

</head>

<body>
<div id="particles-js" style="height: 100%; width: 100%; background-color: white;"></div>
<script src="//cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
<script>particlesJS.load('particles-js', '{{ baseurl }}/assets/js/particles.json', function() {
   console.log('callback - particles.js config loaded');
 });</script>
<div class="row row-cols-1 row-cols-md-3 g-5 mb-5 justify-content-center">
    <div class="col">
        <div class="card h-100 rounded-0 hover-shadow" style="background-color: #055472">
            <div class="card-body text-center p-4 pb-5">
                <h2 class="card-title mb-3" style="color: #f47d21;"><a href="who-we-are" class="stretched-link text-decoration-none text-reset">Who we are</a></h2>
                <p class="card-text" style="color: white;">Learn more about members of the Tools Ecosystem.</p>
            </div>
        </div>
    </div>
    <div class="col">
        <div class="card h-100 rounded-0 hover-shadow" style="background-color: #055472">
            <div class="card-body text-center p-4 pb-5">
                <h2 class="card-title mb-3" style="color: #f47d21;"><a href="why-needed" class="stretched-link text-decoration-none text-reset">Why?</a></h2>
                <p class="card-text" style="color: white;">Why the Tools Ecosystem is needed and what need is fulfils.</p>
            </div>
        </div>
    </div>
    <div class="col">
        <div class="card h-100 rounded-0 hover-shadow" style="background-color: #055472">
            <div class="card-body text-center p-4 pb-5">
                <h2 class="card-title mb-3" style="color: #f47d21;"><a href="linked-services" class="stretched-link text-decoration-none text-reset">Linked services</a></h2>
                <p class="card-text" style="color: white;">The services that form part of the Ecosystem.</p>
            </div>
        </div>
    </div>
    <div class="col">
        <div class="card h-100 rounded-0 hover-shadow" style="background-color: #055472">
            <div class="card-body text-center p-4 pb-5">
                <h2 class="card-title mb-3" style="color: #f47d21;"><a href="governance" class="stretched-link text-decoration-none text-reset">Governance</a></h2>
                <p class="card-text" style="color: white;">We work on an open, community-centred model, where it is easy to connect with others.</p>
            </div>
        </div>
    </div>
    <div class="col">
        <div class="card h-100 rounded-0 hover-shadow" style="background-color: #055472">
            <div class="card-body text-center p-4 pb-5">
                <h2 class="card-title mb-3" style="color: #f47d21;"><a href="https://elixir-europe.org" class="stretched-link text-decoration-none text-reset">ELIXIR</a></h2>
                <p class="card-text" style="color: white;">The Tools Ecosystem is part of ELIXIR, a European life science research infrastructure. </p>
            </div>
        </div>
    </div>
</div>
</body>