<template>
<header class="my-header container">
    <div class="flex">
        <div class="logo w-10">
            <img src="../assets/logo.png"/>
        </div>
        <nav class="w-80 txt-center">
            <ul>
                <li><router-link to="/">Home</router-link></li>
                <li><router-link to="/about">About</router-link></li>
                <li><router-link to="/portfolio">Portfolio</router-link></li>
                <li><router-link to="/contact">Contact</router-link></li>
            </ul>
        </nav>
        <div class="resume-btn w-10 txt-right">
            <div class="egg-btn egg-0">
                <img src="../assets/egg-0.svg"/>
                <a href="https://drive.google.com/file/d/1zG8RKCK2uVpYibuuqf9XrH3zy_yTroBq/view?usp=sharing" target="_blank" class="btn-txt">Resume</a>
            </div>
            
            
        </div>
        <!-- <div class="menu">
            <img src="../assets/menu.svg">
        </div> -->
    </div>
    <div class="line"></div>
</header>
</template>
<script>
  export default {
    name: 'Header',
  };
  </script>