<template>
        <header>
            <nav>
                <router-link to="/">Home</router-link> |
                <router-link to="/about">About</router-link> |
                <router-link to="/news">news</router-link>|
                <router-link to="/product">product</router-link>
            </nav>
        </header>
        <router-view/>
    <footer>
        <a href="#">頁尾</a>
    </footer>

</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

header {
    background-color: #ccc;
}
footer{
    height: 10rem;
    background-color: #ccc;
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
</style>
