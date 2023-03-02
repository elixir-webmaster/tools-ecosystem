---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<head>
    <style>
        
        #particles-js {
   position: absolute;
   z-index: 0;
}
    .row {
    --bs-gutter-x: 1.5rem;
    --bs-gutter-y: 0;
    display: flex;
    flex-wrap: wrap;
    /* margin-top: calc(-1 * var(--bs-gutter-y)); */
    /* margin-right: calc(-.5 * var(--bs-gutter-x)); */
    /* margin-left: calc(-.5 * var(--bs-gutter-x)); */
    margin-top: 10rem;
}
    .card {
    height: 100% !important;
    }
    
      /* Style for the alert box */
      .alert {
        padding: 20px;
        background-color: #f44336;
        color: white;
        text-align: center;
        font-size: 20px;
        font-family: Arial, sans-serif;
        position: relative;
        border-radius: 10px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
        max-width: 400px;
        margin: 0 auto;
        line-height: 1.5;
      }

      /* Style for the close button */
      .closebtn {
        position: absolute;
        top: 10px;
        right: 10px;
        color: white;
        font-size: 30px;
        cursor: pointer;
        transition: color 0.2s ease-in-out;
      }

      /* Style for the x symbol */
      .closebtn:hover {
        color: #ccc;
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

<div class="text-center">
<img src="assets/image/tec1.png" class="rounded" alt="...">
</div>

<!--Adding an alert button. To be removed once site is more concrete--> 
<div class="alert">
      <span class="closebtn" onclick="this.parentElement.style.display='none';">
        &times;
      </span>
      Page is under construction! Click the X button if you want to navigate the webpage regardless! Thank you :) 
    </div>

<div class="row">
  <div class="col-sm-6">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">I am a researcher and want to find research tools!<br> I am a developer and want to connect my tool!<br> I am a service provider and want to link my service!</h5>
        <p class="card-text">Learn more about the tools ecosystem</p>
        <a href="about" class="btn btn-primary">About</a>
      </div>
    </div>
  </div>
  <div class="col-sm-6">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Join a group striving for open science for everyone</h5>
        <a href="join" class="btn btn-primary">Join us</a>
      </div>
    </div>
  </div>
</div>




</body>
