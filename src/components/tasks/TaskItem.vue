<template>
  <div class="border-main-cyan border bg-white p-4 flex flex-col gap-2 rounded-2xl mr-4">
    <h5>Здесь текст заголовка какотйто задачи</h5>
    <p class="text-md text-gray-500 font-light">Здесь краткое описание какойто задачи или еще что нибуть...</p>
    <div class="flex justify-end gap-3">
      <check-icon class="w-[24px]"/>
      <pencil-alt-icon class="w-[24px]"/>
      <trash-icon class="w-[24px]"/>
    </div>
  </div>
</template>

<script>
import { CheckIcon } from "@heroicons/vue/outline";
import { PencilAltIcon } from "@heroicons/vue/outline";
import { TrashIcon } from "@heroicons/vue/outline"
export default {
  name: "TaskItem",
  components: {
    CheckIcon, PencilAltIcon, TrashIcon
  }
}
</script>

<style scoped>

</style>