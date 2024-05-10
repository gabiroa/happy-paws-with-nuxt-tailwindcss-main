<script setup lang="ts">
  // const props = defineProps({
  // 	name: {
  // 		type: String,
  // 		default: 'StatsSection',
  // 	},
  // })
</script>
<template>
  <section>
    <div class="container mx-auto px-4 py-12 relative">
      <div class="-mx-4 flex flex-wrap items-center">
        <div class="p-4 w-full lg:w-2/5">
         
          <NuxtImg
            src="https://images.unsplash.com/photo-1601985705806-5b9a71f6004f?q=80&w=987&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            class="mb-6 rounded-3xl w-full"
            alt="Stats"
          />
        </div>
        <div class="lg:w-6/12 mx-auto p-4 w-full">
          <h6
            class="font-bold mb-2 text-primary-600 dark:text-primary-200 uppercase"
          >
            Our Work
          </h6>
          <h3 class="capitalize mb-6">Impact we make</h3>
          <p>
            You're one step away from benefitting your life and the life of a Plant.
          </p>
          <div class="-mx-4 flex flex-wrap items-center">
            <div class="px-4 py-6 w-1/2">
              <h2 class="mb-2">1200+</h2>
              <p>Plants Adopted</p>
            </div>
            <div class="px-4 py-6 w-1/2">
              <h2 class="mb-2">100+</h2>
              <p>Spaces United</p>
            </div>
            <div class="px-4 py-6 w-1/2">
              <h2 class="mb-2">200+</h2>
              <p>Active Volunteers</p>
            </div>
            <div class="px-4 py-6 w-1/2">
              <h2 class="mb-2">1K+</h2>
              <p>Forests Helped</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style scoped></style>
