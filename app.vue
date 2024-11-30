<script setup>
</script>

<template>
  <div>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">logo</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <nuxt-link to="/" class="nav-link">首頁</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="/account/login" class="nav-link">登入</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="/account/signup" class="nav-link">註冊</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="/rooms" class="nav-link">客房列表</nuxt-link>
            </li>
           
            <li class="nav-item">
              <nuxt-link to="/user/userId/profile" class="nav-link">會員 - 修改資料</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="/user/userId/order" class="nav-link">會員 - 訂單查詢</nuxt-link>
            </li>
           
           
          </ul>
         
        </div>
      </div>
    </nav>
    
    <NuxtPage />
  </div>
</template>
