<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="learnpage">learnpage</router-link>
    
  </nav>
  <router-view/>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
.sec1{
  padding-left: 500px;
  margin-top: -25px
}
.sec2{
  padding-left: 700PX;
  margin-top: -25px;
}
.sec3{
  padding-left: 890px;
  margin-top: -25px;
}
.sec4{
  padding-left: 1090px;
  margin-top: -25px;
}



</style>
