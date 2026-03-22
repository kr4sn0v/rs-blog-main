<script setup lang="ts">
import { Field } from 'vee-validate'

defineProps<{
  name: string
}>()
</script>

<template>
  <Field :name="name" class="w-full rounded-md border border-gray-300 bg-white p-2"></Field>
</template>
