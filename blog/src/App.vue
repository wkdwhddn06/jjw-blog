<template>
  <div id="app">
    <nav id="nav">
      <ul class="nav-container">
        <li class="nav-item"><router-link to="/" class="menu">Profile</router-link></li>
        <li class="nav-item"><router-link to="/blog" class="menu">Blog</router-link></li>
      </ul>
    </nav>
    <router-view/>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=Noto+Sans+KR:100,400,700&display=swap&subset=korean');

*{margin: 0; padding: 0}

#app {
  font-family: 'Noto Sans KR', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  height: 50px;
  width: 850px;
}

#nav a {
  font-weight: 700;
  color: #2c3e50;
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: #E81A50;
}

.nav-container{
  display: flex;
  flex-direction: row;
  width: 100%;
  list-style: none;
  text-align: right;
  z-index: 999;
  position: fixed;
}

.nav-item{
  padding: 20px;
  cursor: pointer;
}

.big {
  font-size: 42px;
  font-weight: bold;
}

.accent {
  font-weight: bold;
  color: #E81A50;
}

.light {
  font-weight: 100;
  color: #595959;
  font-size: 18px;
}

</style>
