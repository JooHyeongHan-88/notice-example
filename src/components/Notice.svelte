<script>
    import { register } from 'swiper/element/bundle'
    register()
  </script>
  
  <swiper-container speed="600" loop="true" centered-slides="true" autoplay-delay="5000" navigation="true" pagination="true" scrollbar="true">
    <swiper-slide>
      <div class="notice">
        <h1>Notice 1</h1>
        <p>공지사항 1입니다.</p>
        <a href="https://www.naver.com" target="_blank"><button class="btn">바로가기</button></a>
      </div>
    </swiper-slide>
    <swiper-slide>
      <div class="notice">
        <h1>Notice 2</h1>
        <p>공지사항 2입니다.</p>
        <a href="https://www.naver.com" target="_blank"><button class="btn">바로가기</button></a>
      </div>
    </swiper-slide>
    <swiper-slide>
        <div class="notice">
          <h1>Notice 2</h1>
          <p>공지사항 2입니다.</p>
          <a href="https://www.naver.com" target="_blank"><button class="btn">바로가기</button></a>
        </div>
      </swiper-slide>
  </swiper-container>
  
  <style>
    .notice {
      padding: 60px 120px;
      height: 360px;
      background-image: url("/banner.png");
      background-size: cover;
      background-position: center;
      color: #fff;
    }
    .notice h1 {
        font-size: 56px;
        font-weight: 700;
    }
    .notice p {
        font-size: 24px;
        font-weight: 700;
    }
    .btn {
      margin-top: 20px;
      width: 128px;
      height: 42px;
      background-color: #000;
      border-radius: 10px;
      color:#fff;
    }
    .btn:hover {
      background-color: rgb(32, 32, 32);
    }
    :root {
        --swiper-navigation-color: rgb(32, 32, 32);
        --swiper-pagination-color: rgb(32, 32, 32);
    }
  </style>