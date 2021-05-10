<template>
  <div>
      <li>
    {{ todo.text }}
      </li>
    <button class="btn btn-primary" @click="$emit('remove', todo.id)">Delete</button>
  </div>
</template>

<script>
export default {
  props: {
    todo: {
      type: Object,
      required: true,
    },
  },
};
</script>