<template>
  <div>
     <div class="topbar bg-black py-2 px-3 d-flex ai-center">
        <img src="../assets/images/logo.png" alt="" height="30">
        <div class="px-2 flex-1">
           <div class="text-white">王者荣耀</div>
           <div class="text-grey-1 fs-xxs">团队成就更多</div>
        </div>
        <button type="button" class="btn bg-primary">立即下载</button>
     </div>

     <div class="bg-primary py-2 pd-2">
         <div class="nav nav-inverse pd-1 jc-around">
            <div class="nav-item active">
               <router-link class="nav-link" tag="div" to="/">首页</router-link>
            </div>
            <div class="nav-item">
               <router-link class="nav-link" tag="div" to="/">攻略中心</router-link>
            </div>
            <div class="nav-item">
               <router-link class="nav-link" tag="div" to="/">赛事中心</router-link>
            </div>
         </div>
     </div>

     <router-view></router-view>
  </div>
</template>

<script type="text/ecmascript-6">
export default {
  name:"Main",
  data() {
    return {

    }
  },
  components: {

  }
}
</script>

<style lang="scss" scoped>
.topbar {
   position: sticky; // 吸顶效果css
   top: 0;
   z-index: 999;
}
</style>
