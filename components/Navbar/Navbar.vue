<template>
    <div>
        <nav class="navbar is-transparent is-fixed-top" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="/">
      <img src="../../assets/images/rLogo.png">
    </a>

    <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" @click="enlarge()">
      <span aria-hidden="true" class="line-one"></span>
      <span aria-hidden="true" class="line-two"></span>
      <span aria-hidden="true" class="line-three"></span>
    </a>
  </div>

  <div class="navbar-menu expand">
    <div class="navbar-end navbar-mobile">
      <a href="#home" class="navbar-item navbar-mobile-item ">
       Home
      </a>

      <a href="#about" class="navbar-item navbar-mobile-item">
        About
      </a>

      <a href="#services" class="navbar-item navbar-mobile-item">
        
         Services 
        </a>

      <a href="#projects" class="navbar-item navbar-mobile-item">
          Projects
      </a>

       <a href="#contact" class="navbar-item navbar-mobile-item">
          Contact
      </a>

    </div>
  </div>
</nav>
    </div>

</template>

<script>
export default {
    methods: {
      enlarge() {
        var expand = document.getElementsByClassName('expand')[0];
        if(expand.style.display === 'none'){
           expand.style.display = 'block';
          
        } else {
          expand.style.display = 'none'
        }
        
      },
    }
}
</script>

<style scoped>
.is-active {
  color:var(--light-purple-hex) !important;
}
.active {
  color:red;
}
.navbar-item img {
    max-height: 4.75rem !important;
    height: 3rem;
}
.navbar-mobile-item:hover {
     color: var(--light-purple-hex);
}
.line-one {
  width: 23px;
  height: 2px;
  background: linear-gradient(45deg, var(--light-purple-hex), var(--bluish-hex));
  border-radius: 50px;
  z-index: 1;
}
.line-two {
  width: 19px;
  height: 2px;
  background: linear-gradient(45deg,  var(--light-purple-hex), var(--bluish-hex));
   border-radius: 50px;
   z-index: 1;
}
.line-three {
  height: 2px;
  background: linear-gradient(45deg, var(--light-purple-hex), var(--bluish-hex));
   border-radius: 50px;
   z-index: 1;
}
/* .is-gradiant {
  background: linear-gradient(45deg, #5009FF, #4A40FF);
} */
.is-transparent {
  background-color: #f9f9f9 !important;
}
@media screen and (max-width: 1023px) {
.navbar-menu {
    background-color: white;
    box-shadow: 0 8px 16px rgba(10, 10, 10, 0.1);
    padding: 0.5rem 0;
    width: 50%;
    position: fixed;
    height: 100vh;
    right: 0;
    border-top-left-radius: 1rem;
    background: linear-gradient(45deg, var( --tint-bluish-hex), var(--light-purple-hex), #363636);
}
.navbar-mobile {
    top: 2rem;
    position: relative;
    text-align: center;
}
.navbar-mobile-item {
    padding: 1.2rem;
    color: white;
}
.navbar-mobile-item:hover {
    background: transparent;
    color:black;
}
}
</style>



