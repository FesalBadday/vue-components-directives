<template>
  <main class="flex justify-evenly gap-x-16 gap-y-16 flex-wrap p-16 bg-gray-400">
    <nuxt-img :src="pageInfo.image" sizes="sm:600px md:900px lg:1000px" />
  </main>
</template>
<script>
export default {
  props: ['pageInfo']
}
</script>