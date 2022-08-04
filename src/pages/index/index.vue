<template>
  <view class="content">
    <DataItem>
      <template v-for="item in ['1','2']" :key="item" v-slot:[item]>
        <div>{{ item }}</div>
      </template>
    </DataItem>
  </view>
</template>

<script setup lang="ts">
import DataItem from './DataItem.vue';
</script>

<style lang="scss">
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
</style>
