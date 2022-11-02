<template>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link href='https://fonts.googleapis.com/css?family=Poppins' rel='stylesheet'>
  <link href='https://fonts.googleapis.com/css?family=Montserrat' rel='stylesheet'>

  <nav>
    <img id="logoFood" alt="Vue logo" src="../src/assets/foodLogo.png">
    <div class="navItems">
      <a>
        <router-link to="/">Home</router-link>
      </a>
      <a>
        <router-link to="/about">about</router-link>
      </a>
      <a>
        <router-link to="/Faq">Faq</router-link>
      </a>
      <a>
        <router-link to="/Contact">Contact</router-link>
      </a>
    </div>
  </nav>
  <router-view />
</template>

<style lang="scss" >

@import url("https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css");
@import url(https://fonts.googleapis.com/css?family=Open+Sans);

body{
  margin: 0;
  padding: 0;
}
#app {

  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

nav {
  width: 100%;
  height: 80px;
  align-self: stretch;
  position: fixed;
  background: #ffffff;
  padding: 20px;
  top:0;
  z-index: 100000000;
}

.navItems {
  padding: 30px;
  text-align: right;

}

nav a {
  position: relative;
  font-weight: bold;
  color: #252B42;
  align-items: stretch;
  text-decoration: none;
  margin: 0 30px;
  text-transform: uppercase;
  transition: all 0.3s ease-in-out;

  &:hover{
    color:#0083E7;
    text-decoration: underline;
  }
}

#logoFood {
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: stretch;
  position: absolute;
  width: 140px;
  height: 60px;
}

nav a.router-link-exact-active {
  color: #0083E7;  
  text-decoration: dotted;

}
</style>
