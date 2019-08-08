<template lang="html">
  <div>
    <h4>{{ title }}</h4>
  </div>
</template>

<script>
export default {
  data() {
    return {
      event: {
        id: 1,
        title: "Event Name Placeholder",
        date: "Wed August 19, 2019",
        time: "6:00PM",
        attendees: [
          {
            id: "abc123",
            name: "John Doe"
          },
          {
            id: "def456",
            name: "Jane Doe"
          }
        ]
      }
    };
  }
};
</script>

<style lang="scss" scoped>
h4 {
  color: #00ff00;
}
</style>
