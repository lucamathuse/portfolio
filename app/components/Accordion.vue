<template>
  <div class="my-24 flex flex-col gap-6">
    <div class="wrapper title">
      <h2>
        <slot></slot>
      </h2>
    </div>
    <div class="flex flex-col">
      <div v-for="project in projects" :key="project.id" class="project py-16 border-t-2 last:border-b-2 border-secondary dark:border-primary border-dashed">
        <div class="wrapper flex flex-col lg:flex-row gap-6 lg:gap-36">
          <h3 class="!font-normal">{{ project.id }}</h3>
          <div class="flex flex-col gap-8">
            <h3>{{ project.title }}</h3>
            <div class="">
                <span v-for="stack in project.stack" class="mr-4">{{ stack }}</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      projects: []
    }
  },
  async created() {
    this.projects = await import('../assets/data/projects.json').then(m => m.default || m)
  }
}
</script>

<style>

</style>