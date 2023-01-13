<template>
  <p class="error">
    <br/><br/><br/>
    请确保你启用了Javascript！
    <br/><br/><br/>
    或者云监控（服务端）未启动或已关闭。
    <br/><br/><br/>
  </p>
</template>
<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'TheError'
});
</script>
<style>
p.error {
  text-align: center;
  color: #616366;
  margin-bottom: 0;
}
</style>
