<template>
  <div id="app" class="container">
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/netlify">Netlify</router-link> | 
      <router-link to="/vue">Vue</router-link>
    </nav>
    <router-view/>
  </div>
</template>
