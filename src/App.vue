<script setup lang="ts">
import { TresCanvas } from '@tresjs/core'

import TheExperience from './components/TheExperience.vue'
</script>

<template>
  <TresCanvas clear-color="#040404" shadows window-size>
    <TheExperience />
  </TresCanvas>
</template>
