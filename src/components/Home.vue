<template>
    <div class="home">
      <div class="container rel">
        <div class="banner flex">
          <img src="../assets/name.svg" class="name-img">
          <img src="../assets/banner1.png" class="section-img"/>

        </div>
      </div>
     
    </div>
    <div class="service">
      <div class="container rel">
        <div class="banner">
    
          <div class="about-content">
            <h1 class="my-title">My Services</h1>
            <div class="flex">
              <div class="col-33">
                <div class="card">
                  <img src="../assets/service-icon-2.webp"/>
                  <h1>Development</h1>
                
                    <ul class="list-item">
                      <li>HTML/CSS</li>
                      <li>JavaScript</li>
                      <li>Animation</li>
                      <li>WordPress</li>
                      <li>React</li>
                  </ul>
                  
                </div>
              </div>
              <div class="col-33">
                <div class="card">
                  <img src="../assets/service-icon-1.webp"/>
                  <h1>UI/UX Design</h1>
                  <ul class="list-item">
                    <li>Landing Pages</li>
                    <li>User Flow</li>
                    <li>Wireframing</li>
                    <li>Prototyping</li>
                    <li>Mobile App Design</li>
                </ul>
                </div>
              </div>
              <div class="col-33">
                <div class="card">
                  <img src="../assets/service-icon-6.webp"/>
                  <h1>Brand Identity</h1>
                  <ul class="list-item">
                    <li>Brand Architecture</li>
                    <li> Brand Authenticity</li>
                    <li>Brand Awareness</li>
                    <li>Brand Management</li>
                    <li>Brand Metrics</li>
                </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
     
    </div>
    <div class="skills">
      <div class="flex">
        <div class="w-60">
          <img src="../assets/skills.svg"/>
        </div>
        <div class="w-20">
          <h1>Hard skills</h1>
          <ul class="list-item">
             <li> UI/UX design</li>
              <li>Front-end web development </li>
              <li>Graphic design</li>
              <li>Brand development </li>
              <li>Video editing Photography</li>
              <li>Document design</li>
              <li>Content management systems</li>
          </ul></div>
          <div class="w-20">
          <h1>soft skills</h1>
         <ul class="list-item">
          <li>  Team building</li>
            <li>Clear communication </li>
            <li>Prioritization</li>
            <li>Time management </li>
            <li>Adaptability</li>
            <li>Goal oriented </li>
            <li>Duty ownership </li>
            <li>Flexibility</li>
         </ul>
        

        </div>
      </div>
    </div>
    <div class="service">
      <div class="container rel">
        <div class="banner">
    
          <div class="about-content">
            <h1 class="my-title">My Complete Projects</h1>
            <div class="flex">
              <div class="col-33">
                <div class="card projects-card">
                  <img src="../assets/en-place.png"/>
                  <h1>En Place</h1>
                
                 <p>Discover an elevated curation of global & sustainable artisan goods inspired by luxury boutique hotels - textiles, tabletop, objects, lighting</p>
                  <a href="https://www.en-place.co/" target="_blank" class="visit"><div>Visit Now</div></a>
                </div>
              </div>
              <div class="col-33">
                <div class="card projects-card">
                  <img src="../assets/danielleidd.png"/>
                  <h1>DANIELLE INTERIORS</h1>
                 <p>Danielle Interiors is a full-service interior design firm whose design thinking is focused on enriching the family experience through space.</p>
                 <a href="https://danielleidd.com/" target="_blank" class="visit"><div>Visit Now</div></a>
                </div>
              </div>
              <div class="col-33">
                <div class="card projects-card">
                  <img src="../assets/aynola.png"/>
                  <h1>TGC</h1>
                 <p>TGC is a lifestyle and beauty company that has launched two brands Aleena and Rawash among other products and services.</p>
                 <a href="https://tgc-ksa.com/" target="_blank" class="visit"><div>Visit Now</div></a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
     
    </div>
  </template>
  
  <script>
  import About from './About.vue';
  export default {
    name: 'Home',
    components: {
    About
  }
  };
  </script>
  
  <style scoped>
  /* Add your styles here */
  </style>
  