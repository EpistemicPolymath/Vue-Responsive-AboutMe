<template>
  <div id="app">
    <DesktopNav id="desktop-nav"/>
    <MobileNav id="mobile-nav"/>
    <div class="view-container">
        <router-view/>
    </div>
  </div>
</template>

<script>
import DesktopNav from '@/components/DesktopNav'
import MobileNav from '@/components/DesktopNav'

export default {
   components: {
     DesktopNav,
     MobileNav
   }
}
</script>

<style lang="scss">
</style>

<style lang="sass" scoped>
  .view-container
      width: 79w
      padding: 1.5em
      margin-left: 20vw
      box-sizing: border-box
      min-height: 100vh
</style>