<template>
  <div>
    <h1>Input 组件示例</h1>
    <Demo :component="Input1Demo" />
    <Demo :component="Input2Demo" />
  </div>
</template>

<script lang="ts">
import Input1Demo from "./Input1.demo.vue";
import Input2Demo from "./input2.demo.vue";

import Demo from "./Demo.vue";
import { ref } from "vue";
export default {
  components: {
    Demo,
  },
  setup() {
    return {
      Input1Demo,
      Input2Demo,
    };
  },
};
</script>

<style lang="scss" scoped>
$border-color: #d9d9d9;

.demo {
  border: 1px solid $border-color;
  margin: 16px 0 32px;

  > h2 {
    font-size: 20px;
    padding: 8px 16px;
    border-bottom: 1px solid $border-color;
  }

  &-component {
    padding: 16px;
  }

  &-actions {
    padding: 8px 16px;
    border-top: 1px dashed $border-color;
  }

  &-code {
    padding: 8px 16px;
    border-top: 1px dashed $border-color;

    > pre {
      line-height: 1.1;
      font-family: Consolas, "Courier New", Courier, monospace;
      margin: 0;
    }
  }
}
</style>
