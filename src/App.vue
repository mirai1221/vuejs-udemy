<template>
  <div>
    <LikeHeader></LikeHeader>
    <LikeNumber></LikeNumber>
    <a href="">テスト</a>
  </div>
</template>

<script>
import LikeHeader from "./components/LikeHeader.vue";
import LikeNumber from "./components/LikeNumber.vue";

export default {
  components: {
    LikeHeader,
    LikeNumber
  }
};
</script>

<style lang="scss" scoped>
div {
  border: 1px solid blue;
  a{
    width: 100px;
    background-color: aqua;
  }
}
</style>

