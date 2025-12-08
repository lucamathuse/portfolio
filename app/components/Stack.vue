<template>
  <div class="wrapper my-24 flex flex-col gap-6">
    <div class="title">
      <h2>
        <slot></slot>
      </h2>
    </div>
    <div class="badge flex flex-row flex-wrap gap-2 md:gap-4">
      <span v-for="stack in techstack.stack">{{ stack }}</span>
    </div> 
  </div>
</template>

<script>
export default {
  data() {
    return {
      techstack: []
    }
  },
  async created() {
    this.techstack = await import('../assets/data/techstack.json').then(m => m.default || m)
  }
}
</script>