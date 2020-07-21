<template>
  <div>
    <el-container class="main-container">
      <template>
         <my-header />
      </template>
      <el-main>
        <Nuxt />
      </el-main>
      <el-footer>Footer</el-footer>
    </el-container>
  </div>
</template>
<script>
import myHeader from "@/components/header/index.vue"
export default {
  data () {
    return {
    };
  },

  components: {
    myHeader
  },

  computed: {},

  mounted() {},

  methods: {}
}

</script>
<style lang="scss" scoped>
</style>
