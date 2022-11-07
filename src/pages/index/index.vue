<template>
  <view class="index">
    <text @click="fn">我是一段文字</text>
    <hello-world msg="hello world"></hello-world>
  </view>
</template>

<script>
import helloWorld from '../../components/helloworld/index.vue'

export default {
  components: {
    'hello-world': helloWorld
  },
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
