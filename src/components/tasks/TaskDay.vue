<template>
  <div class="bg-white shadow-md p-4 w-[350px] rounded-3xl relative">
    <div class="w-full bg-main-cyan text-center py-2 rounded-2xl shadow-inner mb-4 sticky top-0">
      <h4>Monday 23</h4>
    </div>
    <div class="flex flex-col gap-5 scrollbar-thin scrollbar-thumb-gray-200 scrollbar-track-white overflow-y-scroll max-h-[620px]">
      <task-item/>
      <task-item/>
      <task-item/>
      <task-item/>
      <task-item/>
      <task-item/>
    </div>

  </div>
</template>

<script>
import TaskItem from "./TaskItem.vue";
export default {
  name: "TaskDay",
  components: {
    TaskItem
  }
}
</script>

<style scoped>

</style>