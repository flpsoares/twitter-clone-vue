<template>
  <button :class="`${fundo} text-${corTexto} w-${largura} h-${altura} font-${fonte} hover:${hover}`" class="text-center rounded-full">
    {{nome}}
  </button>
</template>

<script>
export default {
  name: 'PatternButton',
  props:{
    nome: String,
    fundo: String,
    corTexto: String,
    largura: String,
    altura: String,
    fonte: String,
    hover: String
  }
}
</script>

<style>

</style>