<demo>
支持显示加载中
</demo>
<template>
  <div>
    <Button loading>加载中</Button>
    <Button loading02>第二种加载</Button>
    <Button loading03>第三种加载</Button>
    <Button>加载完毕</Button>
  </div>
</template>

<script lang="ts">
import { Button } from "../lib/index";
export default {
  components: {
    Button,
  },
};
</script>
