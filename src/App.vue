<template>
  <div>
    <router-view/>
    <play-controller></play-controller>
  </div>
</template>
<script>
import playController from '@/components/playController.vue'
export default {
    components: {
      playController,
    },
    // mounted(){
    //   let userData = JSON.parse(localStorage.userData)
    //   // console.log(userData);
    //   this.$store.commit('setUser',userData)
    // }
}
</script>
<style lang="less">
*{
  margin: 0;
  padding-block: 0;
  box-sizing: 0;
  font-family: '微软雅黑';
}
.icon {
  width: 0.30rem;
}
a {
  color: #333;
  text-decoration: none;

}
</style>
