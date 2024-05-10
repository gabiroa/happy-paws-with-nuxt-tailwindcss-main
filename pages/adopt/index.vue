<script setup>
  definePageMeta({
    // layout: 'default',
    // name: 'blog',
    // alias: 'blog',
    title: 'Adopt Now',
    description: 'Adopt Your Plant Mate!',
    navOrder: 2,
    type: 'primary',
    icon: 'i-mdi-home',
    // ogImage: 'images/ogImage.png', // url or local images inside public folder, for eg, ~/public/images/ogImage.png
  })
</script>
<template>
  <div
    class="py-12 bg-primary-100 dark:bg-primary-700 text-primary-900 dark:text-primary-100"
  >
    <div class="flex flex-col items-center">
      <div class="px-4 text-center w-full lg:w-7/12">
        <h6 class="uppercase">Adopt A Plant</h6>
        <h3 class="capitalize">Small Gesture For A Big Impact</h3>
        <p class="mb-4">
          Plants are vital for sustaining life on Earth by providing oxygen, absorbing carbon dioxide, regulating the climate, and supporting diverse ecosystems.
        </p>
      </div>
    </div>
    <div class="-mt-4 mx-auto pt-8 px-4 relative">
      <div class="-mx-4 flex flex-wrap items-center justify-center mb-4">
        <PetList />
      </div>
    </div>
  </div>
</template>
