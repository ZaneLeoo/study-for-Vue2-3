<template>
  <div>
    <h1>This is school{{ emjoy }},I have a student</h1>
    <student></student>
  </div>
</template>

<script>
import student from './student.vue'
export default {
  data() {
    return {
      emjoy: '🤩',
    }
  },
  components: {
    student,
  },
}
</script>

<style></style>
