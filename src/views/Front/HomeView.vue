<template>
  <div class='home'>
    <HeaderNav />
    <div class='swiper'>
      <swiper
        :slides-per-view="1"
        :space-between="50"
        :modules="modules"
        navigation
        :pagination="{ clickable: true }"
      >
        <swiper-slide>
          <img
            src='/src/assets/carouselImg.png'
            class='d-block w-100'
            alt='carouselImg'
          />
        </swiper-slide>
        <swiper-slide>
          <img
            src='/src/assets/carouselImg2.png'
            class='d-block w-100'
            alt='carouselImg2'
          />
        </swiper-slide>
      </swiper>
      <div class="nightMarket d-flex justify-content-lg-evenly align-items-lg-end">
       <div class="nightMarketName">
         <div class="MainName mb-3">
          <img src='/src/assets/B臨.png' alt="臨江觀光夜市" class="border border-white border-2">
          <img src='/src/assets/B江.png' alt="臨江觀光夜市" class="border border-white border-2">
          <img src='/src/assets/B街.png' alt="臨江觀光夜市" class="border border-white border-2">
         </div>
         <div class="subName">
          <img src='/src/assets/B觀.png' alt="臨江觀光夜市" class="border border-white border-2">
          <img src='/src/assets/B光.png' alt="臨江觀光夜市" class="border border-white border-2">
          <img src='/src/assets/B夜.png' alt="臨江觀光夜市" class="border border-white border-2">
          <img src='/src/assets/B市.png' alt="臨江觀光夜市" class="border border-white border-2">
         </div>
       </div>
       <div class="clickProduct">
        <button type="button" class="rounded-circle">
            <img src="/src/assets/button.png" alt="前往商品">
        </button>
      </div>
      </div>
    </div>
    <div class="container-fluid bg-origin">
      <div class="row">
        <div class="col-lg-2 news borderLine d-flex flex-lg-column flex-column-reverse justify-content-lg-between align-items-lg-center">
            <div class="newTitle fw-bold fs-3">新商店開幕</div>
            <div class="newSubTitle">十一月零陸號</div>
            <button type="button" class="newButton btn btn-primary">Primary</button>
        </div>
        <div class="col-lg-2 news borderLine d-flex flex-lg-column flex-column-reverse justify-content-lg-between align-items-lg-center">
            <div class="newTitle fw-bold fs-3">12間必吃美食，跟著這篇絕對不會迷路</div>
            <div class="newSubTitle">十一月零陸號</div>
        </div>
        <div class="col-lg-4 news borderLine d-flex text-center flex-lg-column justify-content-center align-items-center">
            <div class="mainTitle fw-bold fs-3">
                最新消息
               <div class="mainTag fs-6">News</div>
            </div>
            <div class="newSubTitle">消息一覽</div>
        </div>
        <div class="col-lg-2 news borderLine d-flex flex-lg-column flex-column-reverse justify-content-lg-between align-items-lg-center">
            <div class="newTitle fw-bold fs-3">新商店開幕</div>
            <div class="newSubTitle">十一月零陸號</div>
        </div>
        <div class="col-lg-2 news borderLine d-flex flex-lg-column flex-column-reverse justify-content-lg-between align-items-lg-center">
            <div class="newTitle fw-bold fs-3">12間必吃美食，跟著這篇絕對不會迷路</div>
            <div class="newSubTitle">十一月零陸號</div>
        </div>

      </div>
    </div>
    <div class="bgHistory">
      <div class="container">
        <div class="historyCulture d-flex flex-row-reverse">
          <div class="historyText">歷史文化</div>
          <div class="historyDetail">/夜市在臺灣，有超過100年的歷史。通常是因為當地的交通方便，或是有遼闊場地以及多人群聚集而加以形成。
            <br>據《臺灣日日新報》資料，1908年，有人在鳳山廳旗津天后宮廟前空地設夜市，營業時間為18時至24時。<br>
            此外，日治時期的納涼（日語：納涼）會活動也影響了後續臺灣夜市的發展
          </div>
        </div>
        <div class="marketCulture d-flex justify-content-lg-between align-items-center">
          <img src='/src/assets/carouselImg.png' alt="" class="rounded-circle" width="400" height="400"/>
          <div class="marketText">夜市文化</div>
          <div class="marketDetail">
            <div class="subDetail">
              /台灣小吃與夜市文化更是獨步全球，種類多樣化，是台灣人生活中最具代表性的飲食文化，舉凡蚵仔煎、蚵仔麵線、臭豆腐、炒米粉、大餅包小餅、萬巒豬腳、大腸蚵仔麵線、甜不辣、台南但仔麵…等,皆是台灣風味獨特的小吃名食，價位便宜又好吃，並且可以吃出該地的人文特色。
              <br>此外，夜市也是台灣飲食的特殊的文化，每個夜市充斥琳瑯滿目的特產與小吃美食，各有不同的特色與風味。<br>透過地方小吃，遊客可以更認識地方特產、文化與人文典故。因此，遊台灣，別錯過了精采絕倫的「夜市文化」!
            </div>
            <ul class="marketCount d-flex">
              <li class="text-center border-end px-5">
                <div class="nCount fs-3 mb-2">36</div>
                <div class="nCity">北部</div>
              </li>
              <li class="text-center border-end px-5">
                <div class="nCount fs-3 mb-2">49</div>
                <div class="nCity">中部</div>
              </li>
              <li class="text-center border-end px-5">
                <div class="nCount fs-3 mb-2">52</div>
                <div class="nCity">南部</div>
              </li>
              <li class="text-center px-5">
                <div class="nCount fs-3 mb-2">24</div>
                <div class="nCity">東部</div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="bg-secondary">
      <div class="container">
        <div class="productTopic text-center">
          <div>Yummy Yummy</div>
          <div class="h1 fw-bold mt-3">人氣美食</div>
        </div>
        <div class="row">
          <div class="col-4 mb-5">
            <div class="productImg">
              <a href="#">
                <img src='/src/assets/food-1.png' class="card-img-top" alt="food-1">
              </a>
              <div class="productTag d-flex flex-column">
                <span class="fw-bold">炸</span>
                <span class="fw-bold">物</span>
              </div>
            </div>
            <div class="productContent mt-3">
              <div class="title d-flex justify-content-between align-items-center">
                <a href="#" class="text-decoration-none"><h3 class="cardTitle fw-bold">炭烤雞排</h3></a>
                <div class="productIcon">
                  <a href="#">
                    <span class="material-symbols-outlined">shopping_cart</span>
                  </a>
                  <a href="#">
                   <span class="material-symbols-outlined">favorite</span>
                  </a>
                </div>
              </div>
               <div class="description d-flex flex-column justify-content-start">
                <p class="detail">炸得又香又酥的雞排和鹹酥雞，大口咬下滿滿雞汁，配上蒜頭香、九層塔香，撒墊胡椒和辣粉，光是用......</p>
                <div class="price d-flex">
                  <span class="fw-bold">NT$70</span>
                  <span><del>90</del></span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import HeaderNav from '@/components/HeaderView.vue'
import { Swiper, SwiperSlide } from 'swiper/vue'
import { Navigation, Pagination } from 'swiper'

// Import Swiper styles
import 'swiper/css'
import 'swiper/css/navigation'
import 'swiper/css/pagination'

export default {
  data () {
    return {
      modules: [Navigation, Pagination]
    }
  },
  components: {
    HeaderNav,
    Swiper,
    SwiperSlide
  }
}
</script>

<style scoped>
.home{
  font-family: 'Noto Serif TC';
}
ul{
  list-style:none;
}
.swiper{
  max-width: 100%;
  position: relative;
}
.nightMarket{
  width:100%;
  position: absolute;
  bottom:40px;
  z-index:1;
}
.MainName{
  max-width:100%;
}
.MainName img{
  margin-right: 1rem;
  max-height: 140px;
  max-width: 140px;
}
.subName img{
  margin-right: 1rem;
  height: 140px;
  width: 140px;
}
.newButton{
  display: none;
}
.bg-origin{
  background-color:#F2EFE7;
}
.news{
  padding: 80px;
}
.bg-origin:has(.news:hover){
  background-image: url("/src/assets/hoverImg.png");
  color:#919191;
}
.news:hover{
    color:#fff;
}

.mainTitle{
  position: relative;
  -webkit-writing-mode: vertical-lr;
  writing-mode: vertical-lr;
  margin-bottom: 40px;
}
.mainTag{
  position: absolute;
  top:-20px;
  font-weight: 400;
}
.newTitle{
  height: 300px;
  margin-bottom: 80px;
  -webkit-writing-mode: vertical-lr;
  writing-mode: vertical-lr;
}
.newSubTitle{
  -webkit-writing-mode: vertical-lr;
  writing-mode: vertical-lr;
}
.swiper-slide img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.borderLine{
  border-right-style: dotted;
  border-right-color: #D1D1D1;
}
.productTopic{
  padding-top:120px;
  padding-bottom:80px;
}
.productImg{
  position: relative;
}
.productTag {
position: absolute;
background-color: #000000;
color: #fff;
padding: 4px;
top:-10px;
right: -10px;
}

.bgHistory{
  background-image: url("/src/assets/history.png");
  background-repeat: no-repeat;
  background-size: cover;
  color:#fff;
}

@media screen and (max-width:992px){
  .news{
    padding: 24px;
  }
  .newTitle{
    height: 10px;
    margin-bottom: 20px;
    -webkit-writing-mode: horizontal-tb;
    writing-mode: horizontal-tb;
  }
  .newSubTitle{
    margin-bottom: 8px;
    -webkit-writing-mode: horizontal-tb;
    writing-mode: horizontal-tb;
  }
  .borderLine{
    border-bottom-style: dotted;
    border-bottom-color: #D1D1D1;
  }
}

</style>
