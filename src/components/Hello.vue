<template>
  <div class="hello">
      <div :style="{ width: appW +'px', height: appH +'px'}">
        <h1>17</h1>
        <p>2017.05</p>
        <p>vue的路由功能简介</p>
      </div>
    <div :style="{ width: appW +'px', height: appH +'px'}">
      <h1>17</h1>
      <p>2017.05</p>
      <p>vue的路由功能简介</p>
    </div>
    <div :style="{ width: appW +'px', height: appH +'px'}">
      <h1>17</h1>
      <p>2017.05</p>
      <p>vue的路由功能简介</p>
    </div>
    <div :style="{ width: appW +'px', height: appH +'px'}">
      <h1>17</h1>
      <p>2017.05</p>
      <p>vue的路由功能简介</p>
    </div>
    <div :style="{ width: appW +'px', height: appH +'px'}">
      <h1>17</h1>
      <p>2017.05</p>
      <p>vue的路由功能简介</p>
    </div>
    <div :style="{ width: appW +'px', height: appH +'px'}">
      <h1>17</h1>
      <p>2017.05</p>
      <p>vue的路由功能简介</p>
    </div>
    <div :style="{ width: appW +'px', height: appH +'px'}">
      <h1>17</h1>
      <p>2017.05</p>
      <p>vue的路由功能简介</p>
    </div>
    <div :style="{ width: appW +'px', height: appH +'px'}">
      <h1>17</h1>
      <p>2017.05</p>
      <p>vue的路由功能简介</p>
    </div>
    <div :style="{ width: appW +'px', height: appH +'px'}">
      <h1>17</h1>
      <p>2017.05</p>
      <p>vue的路由功能简介</p>
    </div>
    <div :style="{ width: appW +'px', height: appH +'px'}">
      <h1>17</h1>
      <p>2017.05</p>
      <p>vue的路由功能简介</p>
    </div>
    <div :style="{ width: appW +'px', height: appH +'px'}">
      <h1>17</h1>
      <p>2017.05</p>
      <p>vue的路由功能简介</p>
    </div>
    <div :style="{ width: appW +'px', height: appH +'px'}">
      <h1>17</h1>
      <p>2017.05</p>
      <p>vue的路由功能简介</p>
    </div>
    <div :style="{ width: appW +'px', height: appH +'px'}">
      <h1>17</h1>
      <p>2017.05</p>
      <p>vue的路由功能简介</p>
    </div>
    <div :style="{ width: appW +'px', height: appH +'px'}">
      <h1>17</h1>
      <p>2017.05</p>
      <p>vue的路由功能简介</p>
    </div>
    <div :style="{ width: appW +'px', height: appH +'px'}">
      <h1>17</h1>
      <p>2017.05</p>
      <p>vue的路由功能简介</p>
    </div>


  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
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
        if(appW >= 800){
            this.appW = appW/5;
            this.appH = appH/3;
        }else{
            this.appW = appW/3;
            this.appH = appH/5;
        }

    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .hello{
    width: 100%;
    height: 100%;
    display: flex;
    flex-wrap:wrap;
  }
.hello div{
  box-sizing: border-box;
  text-align: right;
  color: #fff;
  padding-right: 30px;
  border-right: 1px solid #ffffff;
  border-bottom: 1px solid #ffffff;
}
h1{
  font-size: 90px;
  font-weight: normal;
  margin: 10px 0;
}
  p{
    margin: 5px 0;
  }

</style>
