<template>
  <header class="header">
    <div class="header__wrapper">
      <img class="header__logo" src="@/assets/img/give-your-lungs-a-voice.png" alt="logo" >
      <nav class="header__menu menu">
        <ul class="menu__list">
          <li class="menu__list-item">
            <a class="menu__link" href="#">ГЛАВНАЯ СТРАНИЦА</a>
          </li>
          <li class="menu__list-item">
            <a class="menu__link" href="#">ЧТО ТАКОЕ ЭОЗИНОФИЛЬНАЯ БРОНХИАЛЬНАЯ АСТМА</a>
          </li>
          <li class="menu__list-item">
            <a class="menu__link" href="#">ИСТОРИИ ПАЦИЕНТОВ</a>
          </li>
          <li class="menu__list-item">
            <a class="menu__link" href="#">ПОЛЕЗНЫЕ РЕСУРСЫ</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style lang="scss">
.header {
  position: fixed;
  top: 5px;
  left: 0;
  &__wrapper {
    min-width: 1280px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    height: 103px;
    align-items: center;
    padding-left: 25px;
  }
  &__logo {
    object-fit: contain;
    width: 260px;
    margin-top: -9px;
  }
  .menu {
    padding-top: 8px;
    height: 36px;
    display: flex;
    align-items: center;
    &__list {
      display: flex;
    }
    &__list-item {
      font-size: 13px;
      font-weight: 700;
    }
    &__list-item:not(:last-child) {
      padding-right: 18px;
    }
  }
}
</style>
