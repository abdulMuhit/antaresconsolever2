<template>
  <div class="app">
    <div class="app-body">
      <main class="main">
        <div class="container-fluid">
          <router-view></router-view>
        </div>
      </main>
    </div>
  </div>
</template>

<script>
export default {
  name: "BaseContainer",
  data() {
    return {
      name: "base"
    };
  },
  computed: {
    name() {
      return this.$route.name;
    }
  }
};
</script>
