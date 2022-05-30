<template>
  <div class="flex  flex-col justify-start items-start">
    <h1 class="title text-4xl font-extrabold text-blue-400 my-4">{{title}}</h1>
    <h2 class="sub_title text-2xl font-bold text-gray-600">{{subtitle}}</h2>
  </div>
</template>

<script>
export default {
  props: {
        title: {type: String}, 
        subtitle: {type: String},
  }
}
</script>

<style>
</style>
 