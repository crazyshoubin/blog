<template>
  <div id="app"  :style="{ width: appW +'px', height: appH +'px',marginLeft: -appW/2 +'px',marginTop: -appH/2 +'px'}" :size="appH">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app',

  data(){
      return{
          appH :'',
          appW :''
      }
  },
  created: function () {
      var width = window.innerWidth;
      var height = window.innerHeight;
      var appW = width*0.9 ;
      var appH = height*0.8;
      var app = document.getElementById("app");
      this.appW = appW;
      this.appH = appH;

  }
}
</script>




