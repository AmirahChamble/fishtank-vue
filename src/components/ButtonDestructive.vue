<template>
  <BaseButton 
    v-bind="$attrs"
    class="ft-button--destructive"
    v-on="$listeners"
  >
    <slot/>
  </BaseButton>
</template>

<script lang="ts">
import Vue from "vue"
import BaseButton from "./BaseButton.vue"

export default Vue.extend({
  name: "ButtonDestructive",
  components: {
    BaseButton
  },
})
</script>
