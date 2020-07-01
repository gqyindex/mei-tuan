<template>
  <div>
      <city />
      <user />
      <about />
  </div>
</template>

<script>
import city from "./city";
import user from "./user";
import about from "./about";
export default {
  data () {
    return {
    };
  },

  components: {
      city,
      user,
      about
  },

  computed: {},

  mounted() {},

  methods: {}
}

</script>
<style scoped>
</style>