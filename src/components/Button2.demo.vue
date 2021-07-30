<demo>
支持 size
</demo>
<template>
  <div>
    <div>
      <Button size="big">大号按钮</Button>
      <Button>正常按钮</Button>
      <Button size="small">小号按钮</Button>
    </div>
    <div>
      <Button theme="link" size="big">大号按钮</Button>
      <Button theme="link">正常按钮</Button>
      <Button size="small" theme="link">小号按钮</Button>
    </div>
    <div>
      <Button size="big" theme="text">大号按钮</Button>
      <Button theme="text">正常按钮</Button>
      <Button size="small" theme="text">小号按钮</Button>
    </div>
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
