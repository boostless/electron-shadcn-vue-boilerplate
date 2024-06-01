<script setup lang="ts">
import { Label } from '@/components/ui/label'
import { Switch } from '@/components/ui/switch'
</script>

<template>
  <div class="w-screen h-screen flex items-center justify-center">
    <div class="flex items-center space-x-2">
      <Switch id="electron-shadcn" />
      <Label for="electron-shadcn">This is awesome !</Label>
    </div>
  </div>
</template>
