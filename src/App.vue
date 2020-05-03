<template>
  <div id="app">
    <div id="nav">
      <router-link to="/"><img   class="gh" src="http://opgg-static.akamaized.net/images/lol/champion/Azir.png?image=q_auto,w_140&v=1586932751" alt=""></router-link> |
      <router-link to="/about"><img   class="gh" src="http://opgg-static.akamaized.net/images/lol/champion/Akali.png?image=q_auto,w_140&v=1586932751" alt=""></router-link> |
      <router-link to="/drug"><img   class="gh" src="http://opgg-static.akamaized.net/images/lol/champion/Teemo.png?image=q_auto,w_140&v=1586932751" alt=""></router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
