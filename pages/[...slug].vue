<script setup>
const route = useRoute();
const event = useRequestEvent();
setResponseStatus(event, 404);
</script>

<template>
  <div>
    <h1>404 Not Found</h1>
    <p>沒有{{ route.params.slug }}</p>
  </div>
</template>