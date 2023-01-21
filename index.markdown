---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
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
<div id="particles-js" style="height: 100%; width: 100%; background-color: 00FFFFFF;"></div>
<script src="//cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
<script>particlesJS.load('particles-js', '{{ baseurl }}/assets/js/particles.json', function() {
   console.log('callback - particles.js config loaded');
 });</script>
<h1 class="d-none">Home page</h1>
<div class="row row-cols-1 row-cols-md-2 g-5 mt-4 mb-5">
    <div class="col">
        <div class="card h-100 rounded-0 hover-shadow" style="background-color: #055472">
            <div class="card-body text-center p-4 pb-5">
                <h2 class="card-title mb-3" style="color: #f47d21;"><a href="about" class="stretched-link text-decoration-none text-reset">About</a></h2>
                <p class="card-text" style="color: white;">We help <strong>life scientists</strong> find complete information about the software they need. We help <strong>developers</strong>
                link their software to other life science services. </p>
            </div>
        </div>
    </div>
    <div class="col">
        <div class="card h-100 rounded-0 hover-shadow" style="background-color: #055472">
            <div class="card-body text-center p-4 pb-5">
                <h2 class="card-title mb-3" style="color: #f47d21"><a href="join" class="stretched-link text-decoration-none text-reset">Join us</a></h2>
                <p class="card-text" style="color: white;">Join a group striving for open science for everyone. We nurture your work through exciting opportunities.</p>
            </div>
        </div>
    </div>
</div>
</body>
