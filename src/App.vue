<template>
  <div id="app">
    <link rel="stylesheet" href="https://maxst.icons8.com/vue-static/landings/line-awesome/line-awesome/1.3.0/css/line-awesome.min.css">
    <div class="flex h-screen w-screen text-white bg-twitterblue-800">
      <div class="flex h-full border-r border-red-500" style="width: 315px;">
        <Sidebar />
      </div>
      <div class="flex h-full border-r border-green-600" style="width: 599px;">
        
      </div>
      <div class="flex h-full border-r border-purple-700" style="width: 442px;">
        
      </div>
    </div>
  </div>
</template>

<script>
import Sidebar from './components/Sidebar'

export default {
  name: 'App',
  components: {
    Sidebar,
  }
}
</script>

<style>
@import 'assets/css/style.css';

*, *::before, *::after{
  outline: none !important;
}
</style>