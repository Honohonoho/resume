<template>
  <div class="left">
    <div class="logo">
      <div class="avator">
        <img src="../assets/logo-2.jpg" alt="">
      </div>
      <div class="name">
        <p>李祺</p>
        <p class="position">求职意向：前端开发岗位</p>
      </div>
    </div>
    <div class="info">
      <p class="title-top">
        <span class="title-cn">基本信息</span>
      </p>
      <p>
        <span class="icon">&#xe62b;</span>
        <span class="title">个人信息：</span>
        <span class="text">男 / 24岁</span>
      </p>
      <p>
        <span class="icon">&#xe68d;</span>
        <span class="title">学历：</span>
        <span class="text">陕西理工大学 / 电子信息工程</span>
      </p>
      <p>
        <span class="icon">&#xe67b;</span>
        <span class="title">毕业时间：</span>
        <span class="text">2015年</span>
      </p>
    </div>
    <div class="contact">
      <p class="title-top">
        <span class="title-cn">联系方式</span>
      </p>
      <p>
        <span class="icon">&#xe6c8;</span>
        <span class="title">电话：</span>
        <span class="text">18629202817</span>
      </p>
      <p>
        <span class="icon">&#xe61d;</span>
        <span class="title">邮箱：</span>
        <span class="text">751718620@qq.com</span>
      </p>
      <p>
        <span class="icon">&#xe6ab;</span>
        <span class="title">微信：</span>
        <span class="text">lq751718620</span>
      </p>
    </div>
    <div class="link">
      <p class="title-top">
        <span class="title-cn">相关链接</span>
      </p>
      <p>
        <a href="https://github.com/Honohonoho" target="_blank" class="icon">&#xe69f;</a>
        <a href="https://github.com/Honohonoho" target="_blank"  class="title">GitHub</a>
      </p>
      <p>
        <a href="http://www.jianshu.com/u/81b2c77216d9" target="_blank"  class="icon">&#xe66a;</a>
        <a href="http://www.jianshu.com/u/81b2c77216d9" target="_blank"  class="title">个人简书博客</a>
      </p>
    </div>
    <div class="hobby">
      <p class="title-top">
        <span class="title-cn">关于我</span>
      </p>
      <p>
        1.致力于无分号编程，2空格缩进党
      </p>
      <p>
        2.关注前端技术的更新，乐于学习新技术
      </p>
      <p>
        3.轻微强迫症，注意代码书写的规范
      </p>
      <p>
        4.较强的自学能力，上进心强
      </p>
    </div>
    <div class="code">
      <p>有意欢迎加微信</p>
      <img src="../assets/weixin.png">
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.left{
  width: 320px;
  padding-top: 30px;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  .logo{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    .avator{
      width: 170px;
      height: 170px;
      overflow: hidden;
      border-radius: 50%;
      border: 2px solid #fff;
      img{
        width: 166px;
        height: 220px;
        margin-top: -10px;
      }
    }
    .name{
      margin-top: 10px; 
      text-align: center;
      p:nth-child(1){
        font-size: 32px;
        letter-spacing: 10px;
        font-weight: 500;
      }
    }
    .position{
      font-size: 20px;
      letter-spacing: 2px;
    }
  }
  .info,.contact,.link,.hobby{
    width: 100%;
    text-align: left;
    margin-top: 30px;
    p{
      margin-bottom: 5px;
      letter-spacing: 1px;
      .title{
        font-weight: 700;
        letter-spacing: 1px;
      }
      .icon{
        font-size: 20px;
      }
    }
    .title-top{
      letter-spacing: 1px;
      margin-bottom: 10px;
      .title-cn{
        font-size: 24px;
      }
    }
  }
  .link{
    p{
      display: flex;
      align-items: center;
      margin: 0;
      .icon{
        font-size: 24px;
        margin-right: 5px;
      }
    }
  }
  .code{
    margin-top: 30px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    p{
      font-size: 18px;
      font-weight: 600;
      margin-bottom: 10px;
    }
    img{
      width: 150px;
      height: 150px;
    }
  }
}
</style>