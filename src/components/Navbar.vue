<template>
   <div id="menu" class="header__menu">
    <!-- Navigation Start -->
    <nav class="menu__container">
      <ul class="navigation">
        <li>
          <a id="about-trigger" class="btn btn-default btn-navigation hover-anim hover-secondary" href="#0">
            <em></em>
            <span class="btn-caption">About Me</span>
          </a>
        </li>
        <li>
          <a id="works-trigger" class="btn btn-default btn-navigation hover-anim hover-secondary" href="#0">
            <em></em>
            <span class="btn-caption">Portfolio</span>
          </a>
        </li>
        <li>
          <a id="contact-trigger" class="btn btn-default btn-navigation hover-anim hover-secondary" href="#0">
            <em></em>
            <span class="btn-caption">Contact</span>
          </a>
        </li>
      </ul>
    </nav>
    <!-- Navigation End -->
   </div>
  </template>
  
  <script>
  export default {
   name: 'Navbar',
  }
  </script>
  
  <style scoped>
  /* Add your CSS styles here */
  </style>
  