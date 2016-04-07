<template lang="ejs">

  <%
    var pageType = 'ejs';
  %>


  <div id="app">
    <img class="logo" src="./assets/logo.png">
    <hello></hello>
    <ul class="fetures">
      <li>Use ES6 & Less for js & css</li>
      <li>Use ejs for render template</li>
      <li>More infomation visit <a href="https://github.com/super-seed-studio/vuejs-template">here</a></li>
    </ul>
    </p>
    <p>
      For advanced configurations, checkout the docs for
      <a href="http://webpack.github.io/" target="_blank">Webpack</a> and
      <a href="http://vuejs.github.io/vue-loader/" target="_blank">vue-loader</a>.
    </p>
    <p>
      You may also want to checkout
      <a href="https://github.com/vuejs/vue-router/" target="_blank">vue-router</a> for routing and
      <a href="https://github.com/vuejs/vuex/" target="_blank">vuex</a> for state management.
    </p>
  </div>
</template>

<script>
import Hello from './components/Hello'

export default {
  components: {
    Hello
  }
}
</script>

<style lang="less" scoped>
.logo {
  width: 100px;
  height: 100px
}
#app {
  margin-top: -100px;
  max-width: 600px;
  font-family: Helvetica, sans-serif;
  text-align: center;
}
.ejs {
  color: green;
}
.fetures {
  width: 210px;
  margin: 0 auto;
  text-align: left;
}
</style>


<style lang="less">
@bg-color: white;
html {
  height: 100%;
  background-color: @bg-color;
}

body {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}
</style>
