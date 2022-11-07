<template>
  <view class="index">
    <text @click="fn">我是一段文字</text>
  </view>
</template>

<script>
import "./index.scss";

export default {
  setup() {
    const fn = () => {
      console.log("666");
    };
    return {
      fn,
    };
  },
};
</script>
