<template>
  <div class="root">
    <div class="vidContainer">
        <video class="vid" src="../vedio/headbanner.webm"></video>
        <!-- 导航部分 -->
        <div class="navContainer">

          <div class="first-nav">
            <ul class="f-n">
              <li>首页</li>
              <li>番剧</li>
              <li>直播</li>
              <li>游戏中心</li>
              <li>会员购</li>
              <li>漫画</li>
              <li>赛事</li>
              <li>去巴黎</li>
              <li style="font-size: 16px">下载客户端</li>
            </ul>
          </div>

          <!-- 搜索框 -->
          <div class="searchInput">
            <input type="text"  placeholder="搜索" />
            <button>搜索</button>
          </div>
          <!-- 用户栏 -->
          <div class="userSection">
            <div class="user-left">
              <!-- 头像 -->
              <div class="carmer">
                <img
                  src="../img/QQ图片20240730115129.jpg"
                  width="36px"
                  height="36px"
                  alt=""
                />
              </div>
              <a href="">大会员</a>
              <a href="">消息</a>
              <a href="">动态</a>
              <a href="">大会员</a>
              <a href="">历史</a>
              <a href="">创作中心</a>
            </div>

            <div class="user-right">
              <div class="userDetail">
                <a href="" style="color: white">投稿</a>
              </div>
            </div>
          </div>
        </div>

        <div class="biliLogo">
          <img src="../img/c8fd97a40bf79f03e7b76cbc87236f612caef7b2.png" width="168px" alt="" />
        </div>
    </div>
    
    <div class="menu-Container">
        <div class="m-1">
          <div class="tubiao" alt="">
            <img src="../img/book.jpg" height="50px" >
            <p>动态</p>
          </div> 
          <div class="tubiao" alt="">
            <img src="../img/fire.jpg" height="50px" >
            <p>热门</p>
          </div> 
        </div>
        <div class="m-2">
            <span>番剧</span>
            <span>国创</span>
            <span>综艺</span>
            <span>动画</span>
            <span>鬼畜</span>
            <span>舞蹈</span>
            <span>娱乐</span>
            <span>科技</span>
            <span>美食</span>
            <span>汽车</span>
            <span>运动</span>
            <span>电影</span>
            <span>电视剧</span>
            <span>纪录片</span>
            <span>游戏</span>
            <span>音乐</span>
            <span>影视</span>
            <span>知识</span>
            <span>资讯</span>
            <span>生活</span>
            <span>时尚</span>
            <span>更多</span>
      </div>
      <div class="m-3">
       
        <span><img src="../img/book.jpg">专栏</span>
        <span><img src="../img/notes.png">活动</span>
        <span><img src="../img/videocamera.png">直播</span>
        <span><img src="../img/mark.png">课堂</span>
        <span><img src="../img/building-three.png" >社区中心</span>
        <span><img src="../img/music-cd.png">新歌热榜</span>
     
      </div>
    </div>
    <!-- 第二部分 -->
    <div class="second-section">
      <!-- 轮播部分 -->
       <div class="autoshow">
      <div class="show">
          <div class="item"><img src="../img/v008endr.png" /></div>
          <div class="item"><img src="../img/QQ图片20240730115129.jpg" /></div>
          <div class="item"><img src="../img/v008endr.png" /></div>
          <div class="item"><img src="../img/v008endr.png" /></div>
          <div class="item"><img src="../img/v008endr.png" /></div>  
      </div>    
      <div class="button">
        <span class="active"></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div> 
    
    </div>
    
      
   <button @click="run()">检测</button>
  </div>
</template>
<script>
let left = 0;
let timer;
function run(){
a = document.getElementsByClassName('show')
a.style.marginLeft + 'px';
left -= 10;
timer = setTimeout(run,10);
}



import "@/css/daohang.css"
export default{
data(){
    return{
        
    }
},
methods:{
move(){
// let a = document.getElementById('show')
// console.log(a);
// let b = a.style.transform
// b = 'translateX(-100%)'
// console.log(b);

}
   
}
}
</script>

