<template>
  <div id="app">
    <a-menu mode="horizontal">
      <submenu/>
    </a-menu>
  </div>
</template>

<script>
import submenu from './components/SubMenu.vue'

export default {
  name: 'app',
  components: {
    submenu
  }
}
</script>
