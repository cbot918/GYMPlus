<script></script>

<template>
  <div class="yale_banner">
    <img src="../assets/home/banner.png" alt="banner">
  </div>
  <div class="yale_features">
    <section>
      <div>Features</div>
      <div>服務特色</div>
    </section>
    <section>
      <div class="yale_features_down">
        <div class="card text-center mb-3" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">優質教練團隊</h5>
            <p class="card-text">富有經驗的教練群，提供專業的動作指導，讓您訓練事半功倍。</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="card text-center mb-3" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">免費體驗課程</h5>
            <p class="card-text">踏入健身旅程的第一步，尋找最適合您的健身之道。</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="card text-center mb-3" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">即時客服諮詢</h5>
            <p class="card-text">不論是課程資訊、健身建議，線上客服將迅速為您解答。</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style>
  .yale_features{
    height: 606px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .yale_features_down {
    display: flex;
  }
  .yale_features_down div{
    margin: 20px;
  }
  .yale_banner img {
    max-width: 100%;
  }
</style>
