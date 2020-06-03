<template>
  <div id="app">
    <header>
      <h1> Matching Game</h1>
      <nav  class="nav-tabs" id="nav" ref="nav">
        <router-link to="/">Home</router-link>

      </nav>
    </header>
  </div>
</template>

<script>
export default {
  name: "home"
}
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.title {
  margin: 2em auto 0.5em;
}

.nav-tabs {
  a {
    font-weight: bold;
    color: #2c3e50;
    text-decoration: none;

    &.router-link-active {
      text-decoration: none;
      color: #0b5891;
      border-bottom: 2px solid #0b5891;
    }
  }
}

html {
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: inherit;
}

html,
body {
  width: 100%;
  height: 100%;
  margin: 0;
  padding: 0;
}


</style>