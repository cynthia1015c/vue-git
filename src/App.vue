<template>
  <div id="app">
    <div>
      <p>
        <h1>國立清華大學</h1>
        <h2>藝術學院</h2>
      </p>
      
    </div>
    
    <el-menu :default-active="activeIndex" class="el-menu-demo" mode="horizontal" @select="handleSelect" text-color="#7C60A3" active-text-color="#C26197">
      <el-submenu index="1">
        <template slot="title">關於學院</template>
        <el-menu-item index="1-1">學校簡介</el-menu-item>
        <el-menu-item index="1-2">未來展望</el-menu-item>
        <el-menu-item index="1-3">姊妹學校</el-menu-item>
      </el-submenu>
      <el-submenu index="2">
        <template slot="title">學院師資</template>
        <el-menu-item index="2-1">【藝術學院】 榮譽院長</el-menu-item>
        <el-menu-item index="2-2">【藝術學院】 歷任院長</el-menu-item>
        <el-menu-item index="2-3">【藝術學院】 現任院長</el-menu-item>
        <el-menu-item index="2-4">【音樂系】 專兼任師資</el-menu-item>
        <el-menu-item index="2-5">【藝設系】 專兼任師資</el-menu-item>
        <el-menu-item index="2-6">【學士班】 專兼任師資</el-menu-item>
      </el-submenu>
      <el-submenu index="3">
        <template slot="title">學院規章</template>
        <el-menu-item index="3-1">規章辦法</el-menu-item>
        <el-menu-item index="3-2">教師評鑑</el-menu-item>
        <el-menu-item index="3-3">會議紀錄</el-menu-item>
        <el-menu-item index="3-4">院評鑑</el-menu-item>
      </el-submenu>
      <el-submenu index="4">
        <template slot="title">招生訊息</template>
        <el-menu-item index="4-1">院學士班IPTA招生</el-menu-item>
        <el-menu-item index="4-2">音樂系Music招生</el-menu-item>
        <el-menu-item index="4-3">藝設系Art&Design招生</el-menu-item>
        <el-menu-item index="4-4">跨院碩AET招生</el-menu-item>
        <el-menu-item index="4-5">國際交換</el-menu-item>
      </el-submenu>
      <el-submenu index="5">
        <template slot="title">榮譽榜</template>
        <el-menu-item index="5-1">藝術學院教師獲獎</el-menu-item>
        <el-menu-item index="5-2">春之獎學金</el-menu-item>
        <el-menu-item index="5-3">春之卓越獎</el-menu-item>
        <el-menu-item index="5-4">藝設系學生獲獎</el-menu-item>
        <el-menu-item index="5-5">音樂系學生獲獎</el-menu-item>
      </el-submenu>
      <el-submenu index="6">
        <template slot="title">活動花絮</template>
        <el-menu-item index="6-1">藝院藝術季</el-menu-item>
        <el-menu-item index="6-2">國際交流</el-menu-item>
      </el-submenu>
      <el-submenu index="7">
        <template slot="title">藝院影音</template>
        <el-menu-item index="7-1">學院影音</el-menu-item>
        <el-menu-item index="7-2">藝設系影音</el-menu-item>
        <el-menu-item index="7-3">音樂系影音</el-menu-item>
      </el-submenu>
      <el-submenu index="8">
        <template slot="title">藝術學報</template>
        <el-menu-item index="8-1">學報簡介</el-menu-item>
        <el-menu-item index="8-2">編輯陣容</el-menu-item>
        <el-menu-item index="8-3">徵稿須知</el-menu-item>
        <el-menu-item index="8-4">文件下載</el-menu-item>
      </el-submenu>
      <el-menu-item index="9">聯絡資訊</el-menu-item>
    </el-menu>
    
    <div class="block">
      <el-carousel trigger="click" height="464px">
        <el-carousel-item class="p">
          <img src="./assets/1.png">
        </el-carousel-item>
        <el-carousel-item class="p">
          <img src="./assets/22.jpg">
        </el-carousel-item>
        <el-carousel-item class="p">
          <img src="./assets/3.jpg">
        </el-carousel-item>
        <el-carousel-item class="p">
          <img src="./assets/4.jpg">
        </el-carousel-item>
        <el-carousel-item class="p">
          <img src="./assets/5.jpg">
        </el-carousel-item>
        <el-carousel-item class="p">
          <img src="./assets/6.png">
        </el-carousel-item>
      </el-carousel>
    </div>
    <div>
      <h3>學院相關網站</h3>
    </div>
    <div class="line1"></div>
    <div class="whole">
      <div class="a1">
        <h4>藝術與設計學系</h4>
      </div>
      <div class="a2">
        <img src="./assets/7.jpg">
      </div>
      <div class="a3">
        <h5>音樂系</h5>
      </div>
      <div class="a4">
        <img src="./assets/8.jpg">
      </div>
      <div class="a5">
        <h6>藝術學院學士班</h6>
      </div>
      <div class="a6">
        <img src="./assets/9.jpg">
      </div>
    </div>
    <div class="whole2">
      <div class="a7">
        <img src="./assets/10.jpg">
      </div>
      <div class="a8">
        <h7>藝術與創新科技碩士學程</h7>
      </div>
      <div class="a9">
        <img src="./assets/11.jpg">
      </div>
      <div class="a10">
        <h8>春之藝術專題講座</h8>
      </div>
      <div class="a11">
        <img src="./assets/12.jpg">
      </div>
      <div class="a12">
        <h9>科技藝術研究中心</h9>
      </div>
    </div>
      
    
  </div>
</template>

<script>


export default {
  name: 'app',
  data() {
      return {
        activeIndex: '1',
      };
    },
    methods: {
      handleSelect(key, keyPath) {
        console.log(key, keyPath);
      }
    }
}

</script>

<style>
#app {
  font-family: Hiragino Sans GB; 
  font: bolder;
  
}
h1{
  position: absolute;
  width: 408px;
  height: 41px;
  left: 46px;
  top: 20px;
  font-size: 32px;
  letter-spacing: 0.05em;

  color: #341553;
}
h2{
  position: absolute;
  width: 350px;
  height: 73px;
  left: 46px;
  top: 20px;
  font-size: 70px;

  letter-spacing: 0.05em;

  color: #5E548E;
}
/*.el-row {
    margin-bottom: 90px;
    left: 380px;
    top: 115px;
}
.el-col {
    border-radius: 4px;
    left: 380px;
    top: 115px;
}
  .bg-purple-dark {
    background: #99a9bf;
  }
  .bg-purple {
    background: #d3dce6;
  }
  .bg-purple-light {
    background: #e5e9f2;
  }
  .grid-content {
    border-radius: 4px;
    min-height: 24px;
  }
  .row-bg {
    padding: 10px 0;
    background-color: #f9fafc;
  }
  .d1{
    font-size: 24px;
  }*/
  .el-menu-demo{
    width: 1015px;
    left: 375px;
    top: 85px;
    font-size: 24px;
    font: bold;
  }
  .block{
    padding-top: 100px;
  }
  

  .el-carousel__item:nth-child(2n) {
    background-color: #99a9bf;
    
  }
  
  .el-carousel__item:nth-child(2n+1) {
    background-color: #d3dce6;
    
  }
  
  .p{
    width: 100vw;
  }
  
  h3{
    color: #341553;
    font-size: 36px;
    padding-top: 30px;
    margin: 0px;
    padding-left: 46px;
  }
  .line1{
    width: 74px;
    height: 10px;
    background-color: #5E548E;
    
    margin-left: 46px;
  }
  .whole{
    padding-top: 30px;
    padding-left: 46px;
    padding-bottom: 0px;
    margin-bottom: 0px;
    border-bottom: 0px;
  }
  .whole2{
    padding-top: 0px;
    padding-left: 46px;
    margin-top: 0px;
    border-top: 0px;
  }
  .a1{
    
    width: 224px;
    height: 224px;
    background-color: #E0B1CB;
    text-align:center;
    line-height: 170px;
    font-size: 20px;
    display: inline-block;
    float: left;
  }
  .a2{
    display: inline-block;
    float: left;
  }
  .a3{
    
    width: 224px;
    height: 224px;
    background-color: #9F86C0;
    text-align:center;
    line-height: 160px;
    font-size: 24px;
    display: inline-block;
    float: left;
  }
  .a4{
    display: inline-block;
    float: left;
  }
  .a5{
    
    width: 224px;
    height: 224px;
    background-color: #ffffff;
    text-align:center;
    line-height: 160px;
    font-size: 27px;
    display: inline-block;
    float: left;
  }
  .a6{
    display: inline-block;
    float: left;
  }
  .a7{
    display: inline-block;
    float: left;
  }
  .a8{
    
    width: 224px;
    height: 224px;
    background-color: #ffffff;
    text-align:center;
    line-height: 240px;
    font-size: 16px;
    display: inline-block;
    float: left;
    color: black;
  }
  .a9{
    display: inline-block;
    float: left;
  }
  .a10{
    width: 224px;
    height: 224px;
    background-color:#5E548E;
    text-align:center;
    line-height: 240px;
    font-size: 20px;
    display: inline-block;
    float: left;
    color: #ffffff;
  }
  .a11{
    display: inline-block;
    float: left;
  }
  .a12{
    width: 224px;
    height: 224px;
    background-color: #E0B1CB;
    text-align:center;
    line-height: 240px;
    font-size: 20px;
    display: inline-block;
    float: left;
    
  }
</style>
