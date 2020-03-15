<template>
  <div class="home">
    <h1>Welcome to the App!</h1>
    <p>To use this app you'll need to
      <router-link :to="{ name: 'login' }">Login
      </router-link>
      or
      <router-link :to="{ name: 'register' }">Register
      </router-link>
    </p>
  </div>
</template>

<script>
export default {}
</script>
