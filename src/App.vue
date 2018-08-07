<template>
  <div id="app">
    {{msg}}
    <br />
    <button class="btn btn-default">按钮</button>
    <br />
    <button class="btn btn-danger">按钮</button>

    <div class="row">
      <div class="col-sm-8 my-border">
        8
      </div>
      <div class="col-sm-4 my-border">
        4
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<style>
.my-border{
  border: 1px solid #ccc;
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1,
h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
