<template>
  <div class="header">
    <div class="row">
      <div class="col-md-4">
        
      </div>
      <nav class="navbar is-fixed-top is-transparent" style="box-shadow: 0 5px 20px 0 rgba(0,0,0,0.2);" >
      <div class="navbar-brand">
        <a class="navbar-item" href="#header">
          <img id="logo" alt="Vue logo" src="../assets/logo.png" data-target="navbarExampleTransparentExample">
        </a>
        <span></span>
        <span></span>
        <span></span>
        
        
      </div>
      <div id="navbarExampleTransparentExample" class="navbar-menu">
        <div class="navbar-end">
        <div class="navbar-item">
            <a class="navbar-item underline"  href="#about">About</a>
            <a class="navbar-item underline"  href="#skills">Skills</a>
            <a class="navbar-item underline"  href="#competitions">Competitions</a>
            <a class="navbar-item underline"  href="#projects">Projects</a>
            <a class="navbar-item underline"  href="#contact">Contact</a>
        </div>
        </div>
        </div>
      
     
    
      <!-- <div class="navbar-brand">
        
        <div class="navbar-burger burger" onclick="document.querySelector('.navbar-menu').classList.toggle('is-active');" data-target="navbarExampleTransparentExample">
        
        </div>
    </div> -->
    <!-- <div id="navbarExampleTransparentExample" class="navbar-menu">
        <div class="navbar-end">
        <div class="navbar-item">
            <a class="navbar-item underline" v-smooth-scroll="{duration: 1000}" href="#about">About</a>
            <a class="navbar-item underline" v-smooth-scroll="{duration: 1000}" href="#skills">Skills</a>
            <a class="navbar-item underline" v-smooth-scroll="{duration: 1000}" href="#competitions">Competitions</a>
            <a class="navbar-item underline" v-smooth-scroll="{duration: 1000}" href="#projects">Projects</a>
            <a class="navbar-item underline" v-smooth-scroll="{duration: 1000}" href="#contact">Contact</a>
        </div>
        </div>
    </div> -->
    </nav>
    </div>
    


  </div>
</template>
<script>
export default {
  name:'Header',
}
</script>
<style scoped>
#header {
  display: inline-block; 
}
#logo{
      margin-left: 100px;
    margin-top: 15px;

}
.row {
  display: inline-block;
  justify-content:space-between;
}

.padding-lr {
    padding: 10px 30px 10px 30px;
    background: #F3F3F3;
}

.has-bg-img {
    background: url("../assets/logo.png")center center;
    background-size:cover;
}

.overlay {
    background-color: rgba(0, 0, 0, 0.699);
}

h1 {
    color: white;
}

.underline {
  display: inline;
  position: relative;
  overflow: hidden;
}
.underline:after {
  content: "";
  position: absolute;
  z-index: -1;
  right: 0;
  left: 150px;
  width: 0;
  bottom: -5px;
  height: 7px;
  transition-property: width;
  transition-duration: 0.3s;
  transition-timing-function: ease-out;
}
.underline:hover:after,
.underline:focus:after,
.underline:active:after {
  left: 0px;
  right: auto;
  width: 100%;
}

#nav-toggle-state {
  display: none;
}

#nav-toggle-state:checked ~ .nav-menu {
  display: block;
}

.download-button{
    font-size: 1em;
    line-height: 0.8em;
    background: #04C8E1;
    width: 180px;
    border-radius: 2px;
    color: white;
}

.download-button:hover{
    background: #03A9BE;
    transition: 0.5s ease;    
    box-shadow: 0 1px 2px 0 rgba(0,0,0,0.2);
    color: white;
}

</style>

<style scoped>
#header {
  margin-top: 0px;

}
body {
  background: linear-gradient(70deg, #e6e6e6, #f7f7f7);
  color: #514B64;
  min-height: 100vh;
}

code {
  background: #fff;
  padding: 0.2rem;
  border-radius: 0.2rem;
  margin: 0 0.3rem;
}
 
.image {
  position: absolute;
  left: 5.64%;
  right: 6.94%;
  top: 8%;

}

</style>