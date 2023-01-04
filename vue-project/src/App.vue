<script setup>
import { ref } from 'vue'

const msg = ref('Credit Card checkout Example')
</script>

<template>
  <h1>{{ msg }}</h1>

  <a href="/card.html?signature=lCC4%2FhOExMqDqrv0RmxEhMqvZjiH7mGIjlqz%2Bcd13OKiY%2FcoYZHGTV4zos8jDbLQR0gyGe%2BX7%2BdXvg3SRsvDQUSVC7LPJdSA08v64Cjj4FlMRtlhJ6GP7SMkPlxnuvAVONQaNsTZxET1JfTQ6A52LSdKSsYIWQFzaG8qPwYGPSBKH9z7zv4moOHd9g%2F4DDfC&amount=1000&currency=EUR">
Payment</a>
</template>
