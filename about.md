---
layout: default
title: About
---
<script>
  var descriptors = ['UX specialist', 'front-end dev', 'creative', 'manager', 'problem solver'];

  textSequence(0);
  function textSequence(i) {

      if (descriptors.length > i) {
          setTimeout(function() {
              document.getElementById("sequence").innerHTML = descriptors[i];
              textSequence(++i);
          }, 1000); // 1 seconds (in milliseconds)

      }

  }
</script>
<div class="jumbotron jumbotron-fluid">
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-lg-8">
        <p class="lead">Your friendly neighbourhood <strong id="sequence">designer</strong>.</p>
      </div>
    </div>
  </div>
</div>

<div class="container">
  <div class="row">
    <div class="col-sm">
      <!-- <h2>Meet Vanessa</h2> -->
      <p class="lead sm"><strong>Hi, I'm Vanessa</strong>&mdash;a problem solver, designer and user-experience enthusiast with over 15 years of experience engaging with stakeholders, and developing and championing digital (web) solutions. Based in Edmonton, Canada, I am excited by <strong>challenging problems</strong> and opportunities to <strong>grow and build our communities</strong>.</p>
      <hr>
      <h2>Fuelled by <strong>coffee</strong> and <strong>curiosity</strong></h2>
      <p>I earned my Bachelor of Design in Visual Communication (with a specialization in Computing Science) from the University of Alberta. Although I didn't pursue graduate studies, I am constantly in pursuit of knowledge and have taken courses of all kinds over the years&mdash;from photography to data science to <a href="https://www.edmonton.ca/programs_services/landscaping_gardening/compost-education.aspx">composting</a>. My current interests include a mix of data visualization, sustainability and diversity.</p>

      <!-- <h2>Challenge <strong>accepted</strong>!</h2>
      <p>As fate would have it, I have spent most of my career in the digital space&mdash;a field that is ever evolving. Though digging into user research or analyzing data may not be very glamourous, gleaning insight to inform design that solves problems for people makes it all worthwhile!</p> -->

      <h2>The little (<strong>big</strong>) things</h2>
      <p>When I'm not working, you can find me on the <a href="https://eupa.ca/">ultimate frisbee field</a>, baking things with lots of butter, puttering around in the garden or wrangling kiddos.</p>
      <a href="/contact" class="btn btn-primary">Let's build stuff!</a>
    </div>
    <!-- Sidebar -->
    <div class="col-md-3 order-last sidebar">
      <h3>Strengths</h3>

      <h4>Professional</h4>
      <ul>
        <li>Project and team management</li>
        <li>Interpersonal / client relations</li>
        <li>Design systems</li>
        <li>User interface design (UI)</li>
        <li>User experience (UX)</li>
        <li>Personas / storyboarding</li>
        <li>Wireframing / prototyping</li>
        <li>Illustration</li>
      </ul>
      <h4>Personal</h4>
      <ul>
        <li>Excellent communicator</li>
        <li>Critical thinker</li>
        <li>Collaborative</li>
        <li>Adaptable</li>
        <li>Growth mindset</li>
      </ul>
      <h4>Technical</h4>
      <ul>
        <li>Adobe Creative Suite</li>
        <li>HTML / CSS</li>
        <li>Javascript</li>
        <li>Google Suite</li>
        <li>Microsoft Office Suite</li>
        <li>Content Management Systems (WordPress, Sitecore, Drupal)</li>
      </ul>
    </div>
  </div>
</div>
