<template>
  <div class="container">
    <h2>{{ error.statusCode }}</h2>
    <p v-if="error.statusCode === 404">
      That page cannot be found.<br>
      <NuxtLink to="/">Go Home</NuxtLink>
    </p>
    <p v-else>
      Error
    </p>
  </div>
</template>

<script>
export default {
  props: {
    error: {
      type: Object,
      default: null
    }
  }
};
</script>