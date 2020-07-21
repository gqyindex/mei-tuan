<template>
  <div>
    <ul class="about">
      <li>
        <nuxt-link to="">我的美团</nuxt-link>
      </li>
      <li>
        <nuxt-link to="">手机APP</nuxt-link>
      </li>
      <li>
        <nuxt-link to="">商家中心</nuxt-link>
      </li>
      <li>
        <nuxt-link to="">美团规则</nuxt-link>
      </li>
      <li>
        <nuxt-link to="">网站导航</nuxt-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },

  components: {},

  computed: {},

  mounted() {},

  methods: {}
};
</script>
<style scoped lang="scss">
.about {
  display: flex;
  li {
    flex: 1;
  }
}
</style>