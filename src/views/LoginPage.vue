<template>
  <div>
    <h1>登入頁面</h1>
    <input placeholder="帳號" />
    <input type="password" placeholder="密碼" />
    <button @click="goHome">登入</button>
  </div>
</template>

<script setup>
import { useRouter } from 'vue-router'

const router = useRouter()

function goHome() {
  router.push('/home')
}
</script>
