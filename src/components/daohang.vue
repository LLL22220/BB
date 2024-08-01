<template>
  <div class="root">
    <div class="vidContainer">
        <video class="vid" src="../vedio/headbanner.webm"></video>
        <!-- 导航部分 -->
        <div class="navContainer">

          <div class="first-nav">
            <ul class="f-n">
              <li @click="refresh()">首页</li>
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
            <input type="text" v-model="sousuo" placeholder="搜索" />
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
      <div class="lunbo">
			<div class="content">
			<ul id="item">
				<li class="item" >
					<a href="#"><img src="../img/dndxw7tq.png" ></a>
				</li>
				<li class="item">
					<a href="#"><img src="../img/ghj8a1yy.png" ></a>
				</li>
				<li class="item">
					<a href="#"><img src="../img/hd9zgojy.png" ></a>
				</li>
				<li class="item">
					<a href="#"><img src="../img/ke000nxq.png" ></a>
				</li>
				<li class="item">
					<a href="#"><img src="../img/skefd75n.png" ></a>
				</li>
			</ul>
			<div id="btn-left">《</div>
			<div id="btn-right">》</div>
			<ul id="circle">
				
				<li class="circle"></li>
				<li class="circle"></li>
				<li class="circle"></li>
				<li class="circle"></li>
				<li class="circle"></li>
			</ul>
			</div>
		</div>

    <div class="tuijian">
      <div class="item1"><img src="../img/dndxw7tq.png" alt=""/>
        <p>努力的尽头，是躺平！！</p>
        <div class="up">钱包CB·7-30</div>
      </div>
      <div class="item1"><img src="../img/ghj8a1yy.png" alt=""/>
        <p>《崩坏：星穹铁道》走近星穹——「三月七•巡猎：星穹列车第一神剑」</p>
        <div class="up">崩坏星穹铁道·22小时前</div>
      </div>
      <div class="item1"><img src="../img/hd9zgojy.png" alt=""/>
        <p>每天剪辑一小时，在家接单赚钱养活自己！！！</p>
        <div class="up">中职通</div>
      </div>
      <div class="item1"><img src="../img/ke000nxq.png" alt=""/>
        <p>9.5元一只烤鸭和400元一只烤鸭，究竟有什么区别？</p>
        <div class="up">穿毛裤的小拉泽·7-9</div>
      </div>
      <div class="item1"><img src="../img/skefd75n.png" alt=""/>
        <p>被连体上嘴脸，0/5卧薪尝胆，最后1v5反上嘴脸！</p>
        <div class="up">古月酱cc·7-6</div>
      </div>
      <div class="item1"><img src="../img/zd0arrnf.png" alt=""/>
        <p>上海第一烧鸟有多好吃？小伙把所有串都点一遍直呼过瘾！</p>
        <div class="up">哇塞几张·7-30</div>
      </div>

    </div>
    
    </div>
    
      
   <button @click="run()">检测</button>
   <div id="ceshi" style="background: red;">
    asdsadasdasd
   </div>
  </div>
</template>
<script>
import '@/css/daohang.css'
import  '@/js/lunbo';
export default{
data(){
    return{
      sousuo:'',
    }
},
components:{
  
},
methods:{
  refresh(){
    location.reload();
  },
  run(){
  let a = document.getElementById('ceshi').style
   console.log(a);
  }

}
}

</script>
<style>
#ceshi{
  height: 100px;
  width: 100px;
  background-color: red;
}
</style>
