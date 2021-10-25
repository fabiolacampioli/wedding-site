<template>
  <div id="counter">
    Counter: {{msg}}
  </div>
</template>

<script>
export default {
  name: 'Counter',
  props: {
    msg: String
  }
}
</script>