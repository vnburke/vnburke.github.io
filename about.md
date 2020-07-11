---
layout: default
title: About
---
<script>
  var descriptors = ['UX enthusiast', 'front-end dev', 'creative', 'problem solver'];

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
        <p class="lead">Your friendly neighbourhood<br /><strong id="sequence">designer</strong>.</p>
      </div>
    </div>
  </div>
</div>

<div class="container">
  <div class="row">
    <div class="col-sm">
      <h2>Fuelled by <strong>coffee</strong> and <strong>curiosity</strong></h2>
      <p><strong>Hi, I'm Vanessa</strong>&mdash;a problem solver, designer and user-experience enthusiast excited by <strong>challenging problems</strong> and opportunities to <strong>grow and build our communities</strong>. Based in Edmonton, Canada, I have over 15 years of experience engaging with stakeholders, and developing and championing digital (web) solutions.</p>

      <p>I earned my Bachelor of Design in Visual Communication (with a specialization in Computing Science) from the University of Alberta. I have been learning ever since, taking courses of all kinds over the years&mdash;from <a href="https://xpro.mit.edu/certificate/067ceb2c-b369-45a1-a790-fed1ac6c3da5/">data science</a> to <a href="https://www.edmonton.ca/programs_services/landscaping_gardening/compost-education.aspx">composting</a>. My current interests include a mix of data visualization, sustainability, leadership, and diversity and inclusion.</p>

      <!-- <h2>Challenge <strong>accepted</strong>!</h2>
      <p>As fate would have it, I have spent most of my career in the digital space&mdash;a field that is ever evolving. Though digging into user research or analyzing data may not be very glamourous, gleaning insight to inform design that solves problems for people makes it all worthwhile!</p> -->
      <h2>Strengths</h2>
      <div class="container callout">
        <div class="row">
          <div class="col-md-4">
            <h4>Professional</h4>
            <ul class="list-unstyled">
              <li>Project and team management</li>
              <li>Interpersonal / client relations</li>
              <li>Design systems</li>
              <li>User interface design (UI)</li>
              <li>User experience (UX)</li>
              <li>Personas / storyboarding</li>
              <li>Wireframing / prototyping</li>
              <li>Illustration</li>
            </ul>
          </div>
          <div class="col-md-4">
            <h4>Technical</h4>
            <ul class="list-unstyled">
              <li>Adobe Creative Suite</li>
              <li>HTML / CSS</li>
              <li>Javascript</li>
              <li>Google Suite</li>
              <li>Microsoft Office Suite</li>
              <li>Content Management Systems (WordPress, Sitecore, Drupal)</li>
            </ul>
          </div>
          <div class="col-md-4">
            <h4>Personal</h4>
            <ul class="list-unstyled">
              <li>Excellent communicator</li>
              <li>Critical thinker</li>
              <li>Collaborative</li>
              <li>Adaptable</li>
              <li>Growth mindset</li>
            </ul>
          </div>
        </div>
      </div>

      <br />
      <a href="mailto:vanessanburke@gmail.com" class="btn btn-primary">Let's build stuff!</a>
    </div>
    <!-- Sidebar -->
    <div class="col-md-3 order-last sidebar">
      <h3>Fun facts of <strong>2020</strong></h3>
      <table class="table callout">
        <tbody>
          <tr>
            <td scope="row" class="display-4">2</td>
            <td class="desc">Children being wrangled</td>
          </tr>
          <tr>
            <td scope="row" class="display-4">12</td>
            <td class="desc">Different fruits and veges being grown in our garden</td>
          </tr>
          <tr>
            <td scope="row" class="display-4">{{ "today" | date: "%d" | plus: 182 | times: 1.75 | round }}</td>
            <td class="desc">Cups of coffee consumed</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
