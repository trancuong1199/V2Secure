<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header class="header" :class="{ sticky: isSticky }">
    <div @click="scrollToElement(0)">
      <img :src="currentImage" class="header-logo" />
    </div>
    <ul class="header-navbar">
      <li @click="scrollToElement(560)">
        <span
          class="header-navbar-text"
          :class="{ 'header-navbar-text--scroll': isSticky }"
          >V2-SIEM</span
        >
      </li>
      <li @click="scrollToElement(3603)">
        <span
          class="header-navbar-text"
          :class="{ 'header-navbar-text--scroll': isSticky }"
          >V2-WAF</span
        >
      </li>
      <li @click="scrollToElement(6782)">
        <span
          class="header-navbar-text"
          :class="{ 'header-navbar-text--scroll': isSticky }"
          >V2-NIPS</span
        >
      </li>
      <li @click="scrollToElement(9417)">
        <span
          class="header-navbar-text"
          :class="{ 'header-navbar-text--scroll': isSticky }"
          >V2-EDR</span
        >
      </li>
      <li @click="scrollToElement(12147)">
        <span
          class="header-navbar-text"
          :class="{ 'header-navbar-text--scroll': isSticky }"
          >V2-NAC</span
        >
      </li>
      <li @click="scrollToElement(15373)">
        <span
          class="header-navbar-text"
          :class="{ 'header-navbar-text--scroll': isSticky }"
          >LIÊN HỆ</span
        >
      </li>
      <li>
        <span
          class="header-navbar-text"
          :class="{ 'header-navbar-text--scroll': isSticky }"
          >NGÔN NGỮ: VI</span
        >
      </li>
    </ul>
  </header>
  <div class="back-none" :class="{'back-top' : isSticky}" @click="scrollToTop">
    <font-awesome-icon icon="fa-solid fa-arrow-up" :class="{'back-top-icon' : isSticky}" />
  </div>
  <RouterView />
</template>

<script>
export default {
  data() {
    return {
      isSticky: false,
      currentImage: "src/assets/images/image-slider.png",
    };
  },
  created() {
    window.addEventListener("scroll", this.handleScroll);
  },
  destroyed() {
    window.removeEventListener("scroll", this.handleScroll);
  },
  methods: {
    handleScroll() {
      const scrollY = window.scrollY;
      if (scrollY > 100) {
        this.isSticky = true;
        this.currentImage = "src/assets/images/logoHeader.png";
      } else {
        this.isSticky = false;
        this.currentImage = "src/assets/images/image-slider.png";
      }
    },

    scrollToTop() {
      let currentScroll = document.documentElement.scrollTop 
      let int = setInterval(frame, 30)

      function frame(){
        if(0 > currentScroll){
          clearInterval(int)
        } else {
          currentScroll = currentScroll - 460
          document.documentElement.scrollTop = currentScroll
        }
      }
      let current = document.documentElement.scrollTop  
      console.log(current)
    },
    
    scrollToElement(number) {
      window.scrollTo({
        top: number,
        behavior: 'smooth',
      });
    }
  }
};
</script>

<style scoped>
@import "./assets/header.css";
</style>
