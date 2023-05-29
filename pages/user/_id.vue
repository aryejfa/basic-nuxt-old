<template>
  <div>
    <Header />
    <h1>Profile User {{ $route.params.id }}</h1>
  </div>
</template>
<style></style>
<script>
export default {
  validate({ params }) {
    // Must be number
    return /^\d+$/.test(params.id);
  },
};
</script>
