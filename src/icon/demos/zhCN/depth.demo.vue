<markdown>
# 深度

为了搭配不同级的文字颜色，图标提供 `depth` 选项。
</markdown>

<script lang="ts">
import { CashOutline } from '@vicons/ionicons5'
import { defineComponent } from 'vue'

export default defineComponent({
  setup() {
    return {
      CashOutline
    }
  }
})
</script>

<template>
  <n-icon :component="CashOutline" size="40" :depth="1" />
  <n-icon :component="CashOutline" size="40" :depth="2" />
  <n-icon :component="CashOutline" size="40" :depth="3" />
  <n-icon :component="CashOutline" size="40" :depth="4" />
  <n-icon :component="CashOutline" size="40" :depth="5" />
</template>
