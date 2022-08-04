<template>
  <view class="data-item">
    <slot name="1"></slot>
    <slot name="2"></slot>
  </view>
</template>

<script setup lang="ts">

</script>

<style lang="scss">
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.text-area {
  display: flex;
  justify-content: center;
}

.title {
  font-size: 36rpx;
  color: #8f8f94;
}
</style>
