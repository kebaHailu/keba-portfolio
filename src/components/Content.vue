<template>
       <div class="main-content">
        <nav class="navbar">

<ul class="navbar-list">

  <li class="navbar-item">
    <button class="navbar-link  active" data-nav-link>About</button>
  </li>

  <li class="navbar-item">
    <button class="navbar-link" data-nav-link>Resume</button>
  </li>

  <li class="navbar-item">
    <button class="navbar-link" data-nav-link>Portfolio</button>
  </li>

  <li class="navbar-item">
    <button class="navbar-link" data-nav-link>Blog</button>
  </li>

  <li class="navbar-item">
    <button class="navbar-link" data-nav-link>certificate</button>
  </li>
  <li class="navbar-item">
    <button class="navbar-link" data-nav-link>Achievement</button>
  </li>
  <li class="navbar-item">
    <button class="navbar-link" data-nav-link>Contact</button>
  </li>

</ul>
</nav>
<div style="padding-top: 4.5%; position: fixed:  !important;"></div>
<AboutMain/>

</div>
</template>

<script>

import AboutMain from '../components/About/Main.vue'
export default{
    components:{
        AboutMain,

    }
}
</script>