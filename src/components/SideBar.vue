<template>
<aside class="sidebar" data-sidebar>

<div class="sidebar-info">

  <figure class="avatar-box">
    <img src="../assets/image/pro.png" alt="Kibrom Hailu" width="80">
  </figure>

  <div class="info-content">
    <h1 class="name" title="kibrom Hailu">Kibrom Hailu</h1>

    <p class="title">Web developer</p>
  </div>

  <button class="info_more-btn" data-sidebar-btn>
    <span>Show Contacts</span>

    <IonIcon name="chevron-down"></IonIcon>
  </button>

</div>

<div class="sidebar-info_more">

  <div class="separator"></div>

  <ul class="contacts-list">

    <li class="contact-item">

      <div class="icon-box">
        <ion-icon name="mail-outline"></ion-icon>
      </div>

      <div class="contact-info">
        <p class="contact-title">Email</p>

        <a href="mailto:kibromhailu.5513@gmail.com" class="contact-link">kibromhailu.5513@gmail.com</a>
      </div>

    </li>

    <li class="contact-item">

      <div class="icon-box">
        <ion-icon name="phone-portrait-outline"></ion-icon>
      </div>

      <div class="contact-info">
        <p class="contact-title">Phone</p>

        <a href="tel:+251979100065" class="contact-link">+251979100065</a>
      </div>

    </li>

    <li class="contact-item">

      <div class="icon-box">
        <ion-icon name="calendar-outline"></ion-icon>
      </div>

      <div class="contact-info">
        <p class="contact-title">Birthday</p>

        <time datetime="1982-06-23">March 05, 2000</time>
      </div>

    </li>

    <li class="contact-item">

      <div class="icon-box">
        <ion-icon name="location-outline"></ion-icon>
      </div>

      <div class="contact-info">
        <p class="contact-title">Location</p>

        <address>Addis Ababa, Ethiopia</address>
      </div>

    </li>

  </ul>

  <div class="separator"></div>

  <ul class="social-list">

    <li class="social-item">
      <a href="#" class="social-link">
        <ion-icon name="logo-facebook"></ion-icon>
      </a>
    </li>

    <li class="social-item">
      <a href="#" class="social-link">
        <ion-icon name="logo-twitter"></ion-icon>
      </a>
    </li>

    <li class="social-item">
      <a href="#" class="social-link">
        <ion-icon name="logo-instagram"></ion-icon>
      </a>
    </li>

  </ul>

</div>

</aside>

</template>

