<!--  -->
<template>
  <div class="homeView">
    <span>haha</span>
    <div class="noneBgImgeView" v-show="!bgImg"></div>
    <img class="individualityBgView" v-show="bgImg" :src="idImg">
  </div>
</template>

<script>
export default {
  data () {
    return {
      bgImg: false,
      idImg: ''
    }
  }
}
</script>

<style >
.homeView{
  position: relative;
  height: 100%;
  width: 100%;
  overflow: hidden
}
.noneBgImgeView{
  width: 100%;
  height: 100%;
  background: #40a7e7
}

.individualityBgView{
  width: 100%;
  height: 100%
}
</style>
