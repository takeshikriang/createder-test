<template>
  <div class="max-w-7xl mx-auto px-4">
    <div class="text-center">
      <h1 class="my-4 text-3xl font-semibold text-gray-800 capitalize">Hello {{ name }}</h1>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: ''
    }
  },
  async fetch() {
    const { name } = await this.$http.$get('https://unpkg.com/nuxt/package.json')
    this.name = name
  }
}
</script>
