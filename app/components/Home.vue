<template>
  <div class="big-header">
    <h1>{{ message }}</h1>
    <br />
    <router-link class="button" to="/character">Go to Character</router-link>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello Gamer !'
    };
  }
};
</script>
