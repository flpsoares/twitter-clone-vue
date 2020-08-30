<template>
  <div class="flex flex-col w-full p-2 pl-4 mx-10">
    <button class="flex items-center mb-2 justify-center rounded-full h-12 w-12 hover:bg-gray-800">
      <i class="lab la-twitter text-4xl text-white"></i>
    </button>
    <div class="inline-block" style="height: 422px;">
      <SidebarButton nome="Página Inicial" icone="las la-home" />
      <SidebarButton nome="Explorar" icone="las la-hashtag" />
      <SidebarButton nome="Notificações" icone="las la-bell" />
      <SidebarButton nome="Mensagens" icone="las la-bookmark" />
      <SidebarButton nome="Itens salvos" icone="las la-flag" />
      <SidebarButton nome="Listas" icone="las la-bars" />
      <SidebarButton nome="Perfil" icone="las la-user" />
      <SidebarButton nome="Mais" icone="las la-ellipsis-h" />
    </div>
    <div class="">
      <PatternButton nome="Tweetar" fundo="bg-twitterblue-600" largura="56" altura="12" fonte="bold" hover="bg-twitterblue-400"/>
    </div>
    <button class="flex flex-row justify-between items-center rounded-full mt-3 p-2 hover:bg-twitterblue-700">
      <div class="flex flex-row">
        <div class="flex items-center">
          <img class="rounded-full w-10 h-10" src="../assets/img/perfil.jpg">
        </div>
        <div class="flex flex-col ml-1 items-start">
          <span class="font-bold">Filipe</span>
          <span class="text-gray-600 text-sm">@meykfeel</span>
        </div>
      </div>
      <button class="flex">
        <i class="las la-angle-down"></i>
      </button>
    </button>
  </div>
</template>

<script>
import SidebarButton from './SidebarButton'
import PatternButton from './PatternButton'

export default {
  name: 'Sidebar',
  components:{
    SidebarButton,
    PatternButton,
  }
}
</script>

<style>

</style>