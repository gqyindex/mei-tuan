<template>
  <div class="header-content">
    <div>
      <el-col :span="8">
        <city />
      </el-col>
      <el-col :span="8">
        <user />
      </el-col>
      <el-col :span="8">
        <about />
      </el-col>
    </div>
  </div>
</template>

<script>
import city from "./city";
import user from "./user";
import about from "./about";
export default {
  data() {
    return {};
  },

  components: {
    city,
    user,
    about
  },

  computed: {},

  mounted() {},

  methods: {}
};
</script>
<style scoped lang="scss">
.header-content {
  > div {
    width: $main-container;
    margin: 0 auto;
  }
  display: flex;
  color: #999;
  font-size: 12px;
  height: 40px;
  line-height: 40px;
  background: $b-key;
}
</style>