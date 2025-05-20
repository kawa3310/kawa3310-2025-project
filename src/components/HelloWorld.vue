<template>
  <div class="bg-color">
    <navbar class="container">
      <ul class="d-flex justify-content-center fw-bold">
        <li class="px-8">首頁</li>
        <li>部落格</li>
      </ul>
    </navbar>
    <header class="mb-9">
      <div>
        <div class="d-flex position-relative">
          <div class="img-header img-header-1"></div>
          <div class="img-header img-header-2">
            <div class="img-text ps-9 d-flex flex-column">
              <p class="img-title">Alyse Wang</p>
              <p class="side-title">前端工程師 & 職涯諮詢師</p>
            </div>
          </div>
        </div>
          <div class="header-title position-absolute">
            <div class="header-text">
              <p class="pb-2">嗨，我是Alyse一名深耕前端技術的工程師。</p>
              <p>擅長 React、Vue 等框架，同時熱愛為轉職與新手工程師提供職涯指導。邀請你與我一起，開啟更具潛能的程式與職涯之旅！</p>
              <ul class="d-flex pt-3">
                <li>
                  <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2025-web-camp/desktop/index/onlyIcon.png?raw=true" alt="youtube-logo">
                </li>
                <li>
                  <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2025-web-camp/desktop/index/onlyIcon-1.png?raw=true" alt="podcast-logo">
                </li>
                <li>
                  <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2025-web-camp/desktop/index/onlyIcon-2.png?raw=true" alt="podcast-logo">
                </li>
                <li>
                  <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2025-web-camp/desktop/index/icons8-linkedin.png?raw=true" alt="podcast-logo">
                </li>
                <li>
                  <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2025-web-camp/desktop/index/onlyIcon-3.png?raw=true" alt="podcast-logo">
                </li>
              </ul>
            </div>
          </div>
      </div>
    </header>
    <main class="main container">
      <h1 class="pb-7 fw-bold">專業服務與方案</h1>
      <div class="row main-group">
        <div class="col-lg-6">
          <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2025-web-camp/desktop/index/photo.png?raw=true" alt="people-photo">
        </div>
        <div class="col-lg-6">
          <div class="main-side-group">
            <div class="main-side-text">
              <p class="side-title text-dark pb-2">履歷健檢</p>
              <p>履歷是打開機會之門的第一步。讓我協助你突顯專業技術與核心能力，並透過簡短模擬面試為你加分，讓面試官第一眼就被你吸引。</p>
            </div>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="main-side-group">
            <div class="main-side-text-left pb-4 px-4">
              <p class="side-title text-dark pb-2">線上諮詢</p>
              <p>想快速解決前端學習瓶頸，或需要專業職涯指引？透過線上一對一諮詢，我將協助你更有方向地邁進。</p>
            </div>
          </div>
        </div>
        <div class="col-lg-6 people-photo my-6">
          <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2025-web-camp/desktop/index/photo2.png?raw=true" alt="people-photo">
        </div>
        <div class="col-lg-6">
          <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2025-web-camp/desktop/index/photo3.png?raw=true" alt="people-photo">
        </div>
        <div class="col-lg-6">
          <div class="main-side-group">
            <div class="main-side-text">
              <p class="side-title text-dark pb-2">網頁開發</p>
              <p>想打造高效能、具美感的網站？我提供從需求訪談到架構實作的一站式服務，讓你的品牌與產品在線上脫穎而出。</p>
            </div>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="main-side-group">
            <div class="main-side-text-left pb-4 px-4">
              <p class="side-title text-dark pb-2">企業內訓</p>
              <p>想讓團隊快速掌握前端最新技術或優化現有專案流程？我可協助打造專業、實用的企業內訓課程，一次解決團隊痛點。</p>
            </div>
          </div>
        </div>
        <div class="col-lg-6 people-photo my-6">
          <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2025-web-camp/desktop/index/photo4.png?raw=true" alt="people-photo">
        </div>
      </div>
      <div class="d-flex justify-content-end">
        <p class="side-title text-dark">聯繫我，取得更多資訊！</p>
        <a href="#" class="ps-2">
          <i class="bi bi-arrow-right-circle fw-normal"></i>
        </a>
      </div>
    </main>
  </div>
</template>

<style>
  .bg-color {
    background: #FBFBFB;
  }
  .img-header{
    width: 960px;
    height: 834px;
  }
  .img-header-1 {
    background: url('https://github.com/hexschool/2022-web-layout-training/blob/main/2025-web-camp/desktop/index/Hero%20Section.png?raw=true');
  }
  .img-header-2 {
    background: url('https://github.com/hexschool/2022-web-layout-training/blob/main/2025-web-camp/desktop/index/Hero%20Section2.png?raw=true');
  }
  .img-text {
    margin-top: 300px;
  }
  .img-title {
    font-size: 120px;
    color: #0027D5;
    font-weight: 900;
  }
  .side-title {
    font-size: 28px;
    color: #0027D5;
    font-weight: 700;
  }
  .header-title {
    width: 1077px;
    top: 90%;
    left: 40%;
    background-color: #fff;
    .header-text {
      padding: 80px 40px;
      font-size: 28px;
      font-weight: 500;
    }
  }

  .main {
    width: 1976px;
    margin-top: 160px;
  }
  .main-group {
    max-width: 100%;
    padding: 0 98px;
    img {
      width: 636px;
      height: 100%;
    }
  }
  .main-side-group {
    position: relative;
    padding-bottom: 64px;
  }
  .main-side-text {
    padding: 64px 24px 24px 24px;
    background-color: #fff;
    position: absolute;
    top: 118%;
    left: 0%;
    p {
      color: #4B4B4B;
      font-weight: 500;
    }
    &::before{
      content: "";
      width: 30px;
      border-bottom: 5px solid #0027D5;
      border-radius: 5px;
      left: 6%;
      top: 20%;
      position: absolute;
    }
  }
  .main-side-text-left {
    padding: 64px 24px 24px 24px;
    background-color: #fff;
    position: absolute;
    top: 200%;
    left: 0%;
    p {
      color: #4B4B4B;
      font-weight: 500;
    }
    &::before{
      content: "";
      width: 30px;
      border-bottom: 5px solid #0027D5;
      border-radius: 5px;
      left: 6%;
      top: 20%;
      position: absolute;
    }
  }
  .people-photo {
    margin: 0 -100px;
  }
  .bi-arrow-right-circle {
    font-size: 40px;
  }
</style>