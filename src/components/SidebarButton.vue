<template>
  <button class="flex flex-row rounded-full p-2 mb-1 items-center text-white hover:text-twitterblue-600 hover:bg-gray-800">
    <div class="mr-4">
      <i :class="icone" class="w-auto text-3xl"></i>
    </div>
    <span class="font-bold text-lg pr-4">{{nome}}</span>
  </button>
</template>

<script>
export default {
  name: 'SidebarButton',
  props: {
    nome: String,
    icone: String
  }
}
</script>

<style>

</style>