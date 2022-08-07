<template>
  <div class="start-section">
    <div class="start-section__conent content">
      <h2 class="content__title">Если симптомы бронхиальной астмы сохраняются – <br> об этом стоит рассказать врачу!</h2>
      <p class="content__text">Сохранение и усиление симптомов при соблюдении всех врачебных рекомендаций может говорить об эозинофильной бронхиальной астме*1</p>
    </div>
  </div>
</template>

<style scoped lang="scss">
.start-section {
  background: url(@/assets/img/home_page/asthma-be-eosinophilic-asthma.png) no-repeat left center;
  background-size: contain;
  display: flex;
  justify-content: end;
  .content {
    max-width: 401px;
    padding-top: 210px;
    padding-right: 274px;
    padding-bottom: 257px;
    &__title {
      font-size: 28px;
      line-height: 35px;
      font-weight: 400;
      color: $main-color;
    }
    &__text {
      font-size: 20px;
      line-height: 1.6;
      letter-spacing: -0.06px;
    }
  }
}

</style>
