<template>
  <div>
    <div class="box columns is-vcentered  mx-auto w-100-z-index-2 py-0 mt-5">
      <div class="column">

      </div>
      <div class="column has-text-centered is-5">
        <div class="columns">
          <div class="column">
            <NuxtLink to="/">
              <img src="icons8-home-24.png" alt="">
              <p>
                داشبورد
              </p>
            </NuxtLink>
          </div>
          <div class="column">
            <NuxtLink to="/Managealarms">
            <img src="icons8-bell-24.png" alt="">
            <p>
              مدیریت آلارم ها
            </p>
          </NuxtLink>
          </div>
          <div class="column">
            <NuxtLink to="/Supportmanagement">
              <img src="icons8-setting-24.png" alt="">
            <p>
              مدیریت پشتیبانی
            </p>
            </NuxtLink>
          </div>
          <div class="column">
            <NuxtLink to="/Usermanagement">
            <img src="icons8-user-plus-24.png" alt="">
            <p>
              مدیریت کاربران
            </p>
          </NuxtLink>
          </div>
        </div>
      </div>
      <div class="column has-text-left">
        <NuxtLink to="/login">
          <div class="is-flex is-justify-content-left pl-4">
          <img class="pl-4" src="icons8-log-out-24.png" alt="">
          <p>
            خروح از حساب کاربری
          </p>
        </div>
        </NuxtLink>
      </div>
    </div>
  </div>
</template>