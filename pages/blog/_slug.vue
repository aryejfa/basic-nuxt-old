<template>
  <div>
    <Header />
    <main v-if="$route.params.slug">
        <h1>Blog {{ $route.params.slug }}</h1>
    </main>
    <main v-else>
        <h1>List Blog</h1>
    </main>
    
  </div>
</template>
<style></style>
<script></script>
