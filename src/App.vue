<template>
  <main class="bg-[#F0F6F6]">
    <header class="flex justify-center mb-12">
      <header-main/>
    </header>
    <div class="container mx-14">
      <task-day/>
    </div>
  </main>

</template>

<script>
import HeaderMain from "./components/HeaderMain.vue";
import TaskDay from "./components/tasks/TaskDay.vue";
export default {
  components: {
    HeaderMain,
    TaskDay
  }
}
</script>