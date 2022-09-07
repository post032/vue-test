<template>
  <div>
    <ol>
      <li v-for="Todo in todos">
        {{ Todo.text }}
      </li>
    </ol>
  </div>
</template>

<script>
export default {
  data() {
    return {
      todos: [
        { text: 'Learn JavaScript' },
        { text: 'Learn Vue' },
        { text: 'Build something awesome' }
      ]
    }
  }
}

</script>
