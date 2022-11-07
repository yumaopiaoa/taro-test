<template>
  <view class="index">
    index2
    <hello-world msg="hello world"></hello-world>

  </view>
</template>

<script>
import helloWorld from '../../components/helloworld/index.vue'

export default {
  setup() {
    return {
    };
  },
  components: {
    'hello-world': helloWorld
  },
};
</script>
