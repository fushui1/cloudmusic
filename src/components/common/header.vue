<template>
  <div class="header">
    <div class="first">
      <svg class="icon" aria-hidden="true">
        <use xlink:href="#icon-wangyiyunyinleclick"></use>
      </svg>
      <span class="firstSpan">网易云音乐</span>
    </div>
    <div class="second">
      <div class="div">
        <div class="div1">
          <!-- <svg class="icon" aria-hidden="true">
            <use xlink:href="#icon-fanhui"></use>
          </svg> -->
          <i class="el-icon-arrow-left"></i>
        </div>
        <div class="div2">
         <!--  <svg class="icon" aria-hidden="true">
            <use xlink:href="#icon-qianjin"></use>
          </svg> -->
          <i class="el-icon-arrow-right"></i>
        </div>
      </div>
    </div>
    <div class="third">
      <div class="inputDiv">
        <input type="text" placeholder="搜索音乐，视频，歌词，电台">
        <i class="el-icon-search"></i>
      </div>
    </div>
    <div class="fourth">
      <div class="div1">
        <!-- <i class="iconfont icon-morentouxiang"></i> -->
        <svg class="icon" aria-hidden="true">
          <use xlink:href="#icon-morentouxiang2"></use>
        </svg>
        <span>未登录</span>
        <i class="iconfont icon-arrLeft-fill"></i>
      </div>
    </div>
    <div class="fifth">
      <div class="div1">
        <i class="iconfont icon-pifu"></i>
      </div>
      <div class="div2">
         <i class="iconfont icon-xiaoxixinfengnews"></i>
      </div>
      <div class="div3">
        <i class="iconfont icon-shezhi"></i>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'header',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped="" type="text/css">
$bgc : #C62F2F;
.header{
  background-color: $bgc;
  width: 110%;
  height: 50px;
  position: fixed;
  top: 0px;
  margin-left: -10%;
  .first {
    height: 20px;
    position: fixed;
    top: -50px;
    left: -130px;
    span {
      font-size: 20px;
      color: #fff;
      position: relative;
      left: -140px;
      top: -67px;
    
    }
  }
  .second {
    .div {
      // background-color: black;
      height: 20px;
      width: 60px;
      // opacity:1;
      position: relative;
      left: 350px;
      top: 16px;
      border-radius: 3px;
      border: 1px solid #804040;
        .div1 {
          height: 20px;
          // display:inline;
          width: 30px; 
          border-right : 1px solid #804040;;
        }
        .div2 {
          position: relative;
          top: -22px;
          left: 30px;
          height: 20px;
          width: 30px;
        }
      i {
        color: #FFF;
        margin-top: 3px;
      }
    }
  }
  .third {
    width: 250px;
    border-radius: 10px;
    height: 25px;
    position: relative;
    left: 450px;
    top: -8px;
    background-color: #A82828;
      input {
        height: 20px;
        width: 200px;
        // margin-top: 3px;
        // opacity: 0.5;
        background-color: #A82828;
        border: 0;
        outline:none;
        color: #fff;      
      }
      i {
        margin-top: 5px;
      }
  }
  .fourth{
    position: fixed;
    right: 50px;
    top: 10px;
    width: 60px;
    height: 30px;
      .div1 {
        position: fixed;
        right: 100px;
        top: -50px;
        span {
          position: fixed;
          right: 195px;
          top: 18px;
          color: #fff;
          font-size: 12px;
          opacity: 0.6;
        }
        .iconfont {
          position: fixed;
          right: 175px;
          top: 18px;
          color: #fff;
        }
      }
  }
  .fifth {
    position: fixed;
    right: -50px;
    top: 10px;
    width: 200px;
    height: 30px;
      .div1 {
        color: #fff;
        width: 50px;
        margin-top: 8px;
        i {
          opacity: 0.6;
        }
      }
      .div2 {
        margin-left: 40px;
        color: #fff;
        margin-top: -18px;
        width: 50px;
        i {
          opacity: 0.6;
        }
      }
      .div3 {
       margin-left: 80px;
        color: #fff;
        margin-top: -18px;
        width: 50px;
        i {
          opacity: 0.6;
        }
      }
  }
}
</style>
