<template>
  <div id="app">
    
    <full-page>
    <div class="section">
      <home/>
    </div>
    <div class="section">
      Second section ...
    </div>
  </full-page>
  </div>
</template>

<script>
import home from "@/components/Home.vue";

export default {
  components: {
    home
  }
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Prompt:200,200i,400,700");

* {
  margin: 0;
  padding: 0;
  border: 0;
  color: white;
  font-family: 'Prompt', sans-serif;
}

body {
  background-color: #0a0505;
}

.font-extra-light { font-weight: 200; }
.font-extra-light-italic { font-weight: 200i; }
.font-extra-regular { font-weight: 400; }
.font-extra-bold { font-weight: 700; }

.left { float: left; }
.right { float: right; }
</style>
