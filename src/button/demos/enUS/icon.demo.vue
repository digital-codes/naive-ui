<markdown>
# Icon

Icons can be used in buttons. You can use `render-icon` prop or `icon` slot.
</markdown>

<script lang="ts">
import { CashOutline as CashIcon } from '@vicons/ionicons5'
import { NIcon } from 'naive-ui'
import { defineComponent, h } from 'vue'

export default defineComponent({
  components: {
    CashIcon
  },
  setup() {
    return {
      renderIcon() {
        return h(NIcon, null, {
          default: () => h(CashIcon)
        })
      }
    }
  }
})
</script>

<template>
  <n-space>
    <n-button :render-icon="renderIcon">
      +100$
    </n-button>
    <n-button icon-placement="right">
      <template #icon>
        <n-icon>
          <CashIcon />
        </n-icon>
      </template>
      +100$
    </n-button>
  </n-space>
</template>
