<template>
    <div class="header">
      <div class="row">
        <div class="image">
          <a class="navbar-brand" href="/">
            <div class="logo-image">

                  <img alt="Vue logo" src="./assets/logo.png">
            </div>
          </a>
        </div>
      </div>
      <div class="nav">
    
      <nav>
        <ul>
          <li>Our Services</li>
          <li>Portfolio</li>
          <li>About us</li>
          <li>
            <button type="button">
              Contact us
            </button>
          </li>
        </ul>
      </nav>
    </div>

    
    </div>
    <div class="services">
      <div class="service-module">
        
        <svg width="5" height="35" viewBox="0 0 5 35" fill="none" xmlns="http://www.w3.org/2000/svg">
        <rect y="35" width="35" height="5" transform="rotate(-90 0 35)" fill="#1A42BD"/>
        </svg>
        <span>
          Our Services
        </span>
        <div class="service-module-box">
          <div class="containers">
            <svg width="280" height="201" viewBox="0 0 280 201" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect x="0.25" y="0.25" width="279.5" height="200.5" rx="9.75" fill="white" stroke="#B3C0E9" stroke-width="0.5"/>
          
            </svg>

          </div>
          <div class="containers">
            <svg width="280" height="201" viewBox="0 0 280 201" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect x="0.25" y="0.25" width="279.5" height="200.5" rx="9.75" fill="white" stroke="#B3C0E9" stroke-width="0.5"/>
          
            </svg>
          </div>
        </div>
        
      </div>

    </div>
  

</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
#app {
  height: 100%;
  width: 1440px;
  overflow: flex;
  font-family: 'Inter';
  display: inline-block;

  color: #2c3e50;
  margin-top: 10px;
}
nav{float:right;
margin-right: 300px;}
.header {
  width: 1440px;
  height: 71px;
  position: absolute;
left: 0%;
right: 0%;
top: 0%;
bottom: 0%;
background: #FFFFFF;
display: inline-block;
}
.services{
  position: absolute;
width: 1440px;
height: 791.5px;
left: 0px;
top: 525.5px;
background: #FFFFFF;


}
.service-module{
  margin-left:99px;

}
.service-module-box{
  margin-left:99px;
  display: flex;
    flex-direction: row; 
    margin-left: 50px;

}
.container{
  margin-left:19px
}



/* Contruction Website/White */

.logo-image{
    width: 110px;
    height: 76.75px;
    top: -8.89px;
    overflow: hidden;
    margin-top: -6px;
}
.image {
  position: absolute;
  left: 5.64%;
  right: 6.94%;
  top: 8%;

}
ul li{
  display: inline-block; padding:10px;
  height: 25px;
  width:89px;top: 10px;
  margin-left: 50px;
  
  font-size:16px; font-family:'Inter';
}

ul li:hover{
  color:orange;
  
}
button{
  width:135px;
  height:45px;
  background: #1A42BD;
  color: white;
  font-size:18px;
border-radius: 10px;
transition-duration: 0.4s;
}
button:hover{
  background-color: #354E9E;
  font-weight: bold;
  font-size:20px;
border-radius: 10px;
}


#app {
  height: 100%;
  width: 100%;
  overflow: hidden;
  font-family: 'Lato', sans-serif;
}
.w100 {
  font-family: 'Lato', sans-serif;
  font-weight: 100;
}

.w300 {
  font-family: 'Lato', sans-serif;
  font-weight: 300;
}

.w400 {
  font-family: 'Lato', sans-serif;
  font-weight: 400;
}

.bold-tag {
  font-weight: 600;
}

.underline:after {
    content:' ';
    display:block;
    width: 60px;
    margin: auto;
    margin-top: 0px;
    background: #04C8E1;
    height: 4px;
}

/* footer */
.footer {
  position: absolute;
left: 0%;
right: 0%;
top: 0%;
bottom: 0%;

/* Contruction Website/Blue 80 */

background: #283457;
}
</style>
