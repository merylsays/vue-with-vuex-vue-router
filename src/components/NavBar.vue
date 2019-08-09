<template>
  <div id="nav" class="nav">
    <router-link to="/" class="brand">Real World Events</router-link> |
    <nav>
      <router-link :to="{ name: "event-list" }">List</router-link> |
      <router-link :to="{ name: "event-create" }">Create</router-link>
    </nav>
  </div>
</template>
<script>
export default {
}
</script>

<style lang="css" scoped>
</style>
