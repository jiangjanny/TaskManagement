<template>
    <div>
      <header>
        <nav>
          <!-- 导航链接 -->
          <NuxtLink to="/">Home</NuxtLink>
          <NuxtLink to="/about">About</NuxtLink>
        </nav>
      </header>
  
      <main>
      <slot />
    </main>
  
      <footer>
        <p>Footer Content</p>
      </footer>
    </div>
  </template>
  
  <style scoped>
  /* 你可以在这里定义页面布局的样式 */
  header {
    background-color: #333;
    color: #fff;
    padding: 10px;
  }
  
  footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
  }
  </style>
  