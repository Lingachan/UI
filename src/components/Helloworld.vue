<template>
<div>
<div id="header">
</div>
<div class="smoke_img">
<h1>Tasty Smokes</h1>
</div>
<div id="carousel">
  <el-carousel :interval="4000" type="card" height="300px">
    <el-carousel-item>
      <div>
          <iframe src="https://www.youtube.com/embed/B1-_He4U_lM"
        width="100%" height="300" frameborder="0" allowfullscreen></iframe>
      </div>
    </el-carousel-item>
    <el-carousel-item>
      <div>
          <iframe src="https://www.youtube.com/embed/HygsZIbOdEA"
        width="100%" height="300" frameborder="0" allowfullscreen></iframe>
      </div>
    </el-carousel-item>
     <el-carousel-item>
      <div>
          <iframe src="https://www.youtube.com/embed/SYt2y5TBHqI"
        width="100%" height="300" frameborder="0" allowfullscreen></iframe>
      </div>
    </el-carousel-item>
     <el-carousel-item>
      <div>
          <iframe src="https://www.youtube.com/embed/1jBYUU3nCMs"
        width="100%" height="300" frameborder="0" allowfullscreen></iframe>
      </div>
    </el-carousel-item>
     <el-carousel-item>
      <div>
      <iframe src="https://www.youtube.com/embed/iKirT4rGI64"
        width="100%" height="300" frameborder="0" allowfullscreen></iframe>
      </div>
    </el-carousel-item>
  </el-carousel>
  </div>
  <div id="footer">
    <div id="social" class="pull-right">
    <img src="../assets/facebook.svg" class="media-icons">
    <img src="../assets/instagram.png" class="media-icons">
    <img src="../assets/youtube.png" class="media-icons">
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
    }
  }
}
</script>
<style>
  .el-carousel__item h3 {
    color: #475669;
    font-size: 14px;
    opacity: 0.75;
    line-height: 200px;
    margin: 0;
  }

  .el-carousel__item:nth-child(2n) {
    background-color: #99a9bf;
  }

  .el-carousel__item:nth-child(2n+1) {
    background-color: #d3dce6;
  }
  #footer {
   bottom:0;
   width:100%;
   height:60px;   /* Height of the footer */
   background:#C5E1A5;
}
  #header {
   position:absolute;
   Top:0;
   width:100%;
   height:60px;
   background:#F1F8E9;
}
#carousel {
  margin:15px;
}
#social {
padding-right:15px;
}
.pull-right {
  float:right;
}
.media-icons {
height: 25px;
width:25px;
}
.smoke_img {
  padding:25px;
  background:url(../assets/tasty.gif);
  background-attachment:fixed;
  opacity:0.5;
  background-size:100%;
  height:100vh;
}
.img_opacity {
  opacity:0.5;
  width:100%;
  height:85vh;
}
.h1 {
  font-size:50px;
  color:#fff;
  z-index:1;
}
</style>

