<template>
  <div class="about container">
    <h1 class="page-header">
      <router-link to="/" class="btn btn-default">返回</router-link>
    </h1>
    <p class="jumbotron"><img src="static/bcg.jpg" alt=""></p>
  </div>
</template>

<script>
export default {
  name: "about",
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img{
  width: 100%;
}
</style>
