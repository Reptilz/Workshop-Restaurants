<template>
  <div>
    <Nav />
    <div class="container">
      <h1>Welcome to Restaurantly</h1>
      <NuxtLink to="/restaurants"
        >Go to restaurants <span>&#8594;</span></NuxtLink
      >
    </div>
  </div>
</template>

<style scoped>
.container {
  text-align: center;
  margin-top: 5rem;
}
</style>
