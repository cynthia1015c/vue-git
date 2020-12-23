<template>
  <div id="app" role="heading">
    <div>
      <h1>國立清華大學</h1>
      <h2>藝術學院</h2>
      <div class="bt">
        <div class="bt1">關於學院</div>
        <div class="bt2">學院師資</div>
        <div class="bt3">學院規章</div>
        <div class="bt4">招生訊息</div>
        <div class="bt5">榮譽榜</div>
        <div class="bt6">活動花絮</div>
        <div class="bt7">藝院影音</div>
        <div class="bt8">藝術學報</div>
        <div class="bt9">聯絡資訊</div>
      </div>
    </div>
    
    
    
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
    
      <div class="a7">
        <img src="./assets/10.jpg">
      </div>
      <div class="a8" role="heading">
        <h7>藝術與創新科技碩士學程</h7>
      </div>
      <div class="a9">
        <img src="./assets/11.jpg">
      </div>
      <div class="a10" role="heading">
        <h8>春之藝術專題講座</h8>
      </div>
      <div class="a11">
        <img src="./assets/12.jpg">
      </div>
      <div class="a12" role="heading">
        <h9>科技藝術研究中心</h9>
      </div>
      <div class=hh role="heading">
        <h10>近期活動</h10>
        <div class="line2"></div>
        
      </div>
      
    </div>
    <div class="news">
      <div class="n1">
        <div class="w1">Posted on 12 月 - 8 - 2020</div>
        <div class="w2">藝設系學生獲獎－109年林務局「國產材料設計商品比賽」決選</div>
        <div class="rm1">Read More</div>
      </div>
      <div class="n2">
        <div class="w1">Posted on 12 月 - 1 - 2020</div>
        <div class="w2">2021 年藝術學院教育發展基金</div>
        <div class="rm2">Read More</div>
      </div>
      <div class="n3">
        <div class="w1">Posted on 12 月 - 1 - 2020</div>
        <div class="w2">【開放報名】2020國立清華大學藝術與設計學系研究生論文研討會</div>
        <div class="rm1">Read More</div>
      </div>
      <div class="n4">
        <div class="w1">Posted on 12 月 - 8 - 2020</div>
        <div class="w2">清華大學藝設系研究生論文研討會徵稿</div>
        <div class="rm2">Read More</div>
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
  font-family: 微軟正黑體; 
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
.bt{
  left: 46px;
  top: 20px;
  padding-left: 400px;
  padding-top: 120px;
}

.bt1{
  left: 46px;
  top: 20px;
  float: left;
  display: inline-block;
  font-size: 20px;
  color: #7C60A3;
  
}
.bt2{
  left: 46px;
  top: 20px;
  float: left;
  display: inline-block;
  font-size: 20px;
  color: #7C60A3;
  padding-left: 30px;
}
.bt3{
  left: 46px;
  top: 20px;
  float: left;
  display: inline-block;
  font-size: 20px;
  color: #7C60A3;
  padding-left: 30px;
}
.bt4{
  left: 46px;
  top: 20px;
  float: left;
  display: inline-block;
  font-size: 20px;
  color: #7C60A3;
  padding-left: 30px;
}
.bt5{
  left: 46px;
  top: 20px;
  float: left;
  display: inline-block;
  font-size: 20px;
  color: #7C60A3;
  padding-left: 30px;
}
.bt6{
  left: 46px;
  top: 20px;
  float: left;
  display: inline-block;
  font-size: 20px;
  color: #7C60A3;
  padding-left: 30px;
}
.bt7{
  left: 46px;
  top: 20px;
  float: left;
  display: inline-block;
  font-size: 20px;
  color: #7C60A3;
  padding-left: 30px;
}
.bt8{
  left: 46px;
  top: 20px;
  float: left;
  display: inline-block;
  font-size: 20px;
  color: #7C60A3;
  padding-left: 30px;
}
.bt9{
  left: 46px;
  top: 20px;
  float: left;
  display: inline-block;
  font-size: 20px;
  color: #7C60A3;
  padding-left: 30px;
}
  .el-menu-demo{
    width: 1015px;
    left: 375px;
    top: 85px;
    font-size: 24px;
    font: bold;
  }
  .block{
    padding-top: 50px;
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
    width: 224px;
    height: 224px;
    display: inline-block;
    float: left;
  }
  .a1:hover .a22{
    display: block;
  }
  .a1:hover .a2{
    display: none;
  }
  .a22{
    width: 224px;
    height: 224px;
    display: none;
    float: left;
    background-color: #E0B1CB;
  }
  .a3{
    
    width: 224px;
    height: 224px;
    background-color: #9F86C0;
    text-align:center;
    line-height: 170px;
    font-size: 24px;
    display: inline-block;
    float: left;
  }
  .a4{
    width: 224px;
    height: 224px;
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
    width: 224px;
    height: 224px;
    display: inline-block;
    float: left;
  }
  .a7{
    width: 224px;
    height: 224px;
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
    width: 224px;
    height: 224px;
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
    width: 224px;
    height: 224px;
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
    color: black;
    
  }
  
  .hh{
    width: 200px;
    height: 38px;
    text-align:left;
    font-size: 36px;
    display: inline-block;
    float: left;
    color:  #341553;
    padding-top: 30px;
  }
  .line2{
    width: 74px;
    height: 10px;
    background-color: #5E548E;
    
  }
  .news{
    display: inline-block;
    float: left;
    padding-top: 40px;
  }
  
  .n1{
    width: 600px;
    height: 254px;
    display: inline-block;
    float: left;
    padding-left: 46px;
    
  }
  .w1{
    font-size: 20px;
    color: black;
  }
  .w2{
    padding-top: 10px;
    font-size: 28px;
    color: black;
  }
  .rm1{
    width: 107px;
    height: 28px;
    font-size: 14px;
    background-color: #9F86C0;
    color: #ffffff;
    text-align:center;
    line-height: 28px;
    margin-left: 500px;
    margin-top: 100px;
  }
  .rm2{
    width: 107px;
    height: 28px;
    font-size: 14px;
    background-color: #9F86C0;
    color: #ffffff;
    text-align:center;
    line-height: 28px;
    margin-left: 500px;
    margin-top: 141px;
  }
  .rm2:hover{
    background-color: #C26197;
    color: #ffffff;
  }
  .rm1:hover{
    background-color: #C26197;
    color: #ffffff;
  }
  
  .n2{
    width: 600px;
    height: 254px;
    display: inline-block;
    float: left;
    padding-left: 135px;
  }
  .n3{
    width: 600px;
    height: 254px;
    padding-top: 40px;
    display: inline-block;
    float: left;
    padding-left: 46px;
  }
  .n4{
    width: 600px;
    height: 254px;
    padding-top: 40px;
    display: inline-block;
    float: left;
    padding-left: 135px;
  }
</style>
