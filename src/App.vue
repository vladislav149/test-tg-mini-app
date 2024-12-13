<script setup lang="ts"></script>

<template>
  <div class="wrapper">
    <header class="header">
      <div class="container">
        <img src="@/assets/logo.png" alt="logo" width="50px" />
      </div>
    </header>
    <main>
      <div class="container">
        <div class="main">content</div>
      </div>
    </main>
  </div>
</template>

<style scoped>
.wrapper {
  min-height: 100dvh;
}

.container {
  padding: 0 10px;
  max-width: 800px;
  margin: 0 auto;
}

.header {
  padding: 20px 0;
  border-bottom: 1px solid black;
}

main {
  background-color: #ccc;
}

.main {
  min-height: 300px;
  display: grid;
  place-items: center;
}
</style>
