<template>
<div class="home">
    <div class="logo">
      <a href="https://www.484.life/#/resume/cool" target="_blank"><img style="position: center; top: 0; right: 0; border: 0; width: 10%; " src="https://cdn-icons-png.flaticon.com/512/282/282100.png"></a>
  </div>
  <h3 class="title">my resume</h3>
  <div class="previews">
  </div>
</div>
</template>

<script>
import Vue from 'vue';
export default Vue.component('resume', {
    name: 'app'
});
</script>

<style scoped>
.home {
  font-family: 'Roboto' !important;
}

.logo {
  text-align: center;
}

.logo img {
  height: 100%;
  margin-top: 40px;
}

.title {
  font-weight: normal;
  text-align: center;
  width: 100%;
  color: black;
  font-weight: 300;
  font-size: 30px;
  line-height: 110%;
  margin: 1.78rem 0 1.424rem 0;
  margin-top: 0px;
  margin-bottom: 40px;
}

.previews {
  width: 90%;
  margin-right: auto;
  margin-left: auto;
}

.preview {
  width: 180px;
  float: left;
  margin-left: 1.5%;
  margin-right: 1.5%;
  margin-bottom: 1.5%;
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 1px 5px 0 rgba(0, 0, 0, 0.12), 0 3px 1px -2px rgba(0, 0, 0, 0.2);
  height: 252px;
  overflow: hidden;
}

.preview-wrapper {
  position: relative;
  background: white;
}

.preview img {
  width: 100%;
  opacity: 0.5;
  filter: blur(1px);
}

.preview span {
  position: absolute;
  max-width: 100%;
  font-size: 24px;
  font-weight: 300;
  color: rgba(0, 0, 0, 0.75);
  width: 100%;
  text-align: center;
  display: inline-block;
  top: 50%;
  transform: translateY(-50%);
}
</style>
