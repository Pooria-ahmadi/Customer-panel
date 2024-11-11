<template>
  <div class="is-hidden-mobile is-hidden-tablet-only">
    <div class="menu-container w-100-z-index-2 box columns is-vcentered py-0 mt-5">
      <div class="column"></div>
      <div class="column has-text-centered">
        <div class="columns">
          <div class="column">
            <NuxtLink to="/" class="menu-hover">
              <img src="icons8-home-24.png" alt="">
              <p class="width-text-118px">داشبورد</p>
            </NuxtLink>
          </div>
          <div class="column">
            <NuxtLink to="/Managealarms" class="menu-hover">
              <img src="icons8-bell-24.png" alt="">
              <p class="width-text-118px">مدیریت آلارم ها</p>
            </NuxtLink>
          </div>
          <div class="column">
            <NuxtLink to="/Supportmanagement" class="menu-hover">
              <img src="icons8-setting-24.png" alt="">
              <p class="width-text-118px">مدیریت پشتیبانی</p>
            </NuxtLink>
          </div>
          <div class="column">
            <NuxtLink to="/Usermanagement" class="menu-hover">
              <img src="icons8-user-plus-24.png" alt="">
              <p class="width-text-118px">مدیریت کاربران</p>
            </NuxtLink>
          </div>
        </div>
      </div>
      <div class="column has-text-left is-3">
        <NuxtLink to="/login" class="logout-hover">
          <div class="is-flex is-justify-content-left pl-4">
            <img class="pl-4" src="icons8-log-out-24.png" alt="">
            <p>خروج از حساب کاربری</p>
          </div>
        </NuxtLink>
      </div>
    </div>
  </div>
</template>
