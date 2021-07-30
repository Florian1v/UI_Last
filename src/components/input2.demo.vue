<demo>
基础用法--禁用输入
</demo>

<template>
  <Input placeholder="禁用" v-model="text" disabled />
</template>

<script lang="ts">
import { Input } from "../lib/index";
import { ref } from "vue";
export default {
  components: {
    Input,
  },
  setup() {
    const text = ref("");
    return { text };
  },
};
</script>
<style lang="scss" scoped>
.picked {
  padding: 10px 15px;
}
</style>