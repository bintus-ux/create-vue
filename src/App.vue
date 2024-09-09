<script>
export default {
  data () {
    return {
      name: 'John Doe',
      status: false,
    }
  }
}
</script>

<template>
  <h1>{{ name }}</h1>
  <p v-if="status">user is active</p>
  <p v-if="status">user is active</p>
</template>

