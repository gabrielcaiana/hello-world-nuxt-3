<template>
  <div>
      <h1 v-text="message"></h1>
  </div>
</template>

<script>
export default {
  setup() {
    const message = "Gabriel Caiana"

    return {
      message
    }
  },
}
</script>
