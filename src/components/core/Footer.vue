<template>
  <v-footer
    id="core-footer"
    absolute
    height="82"
  >
    <div class="footer-items">
      <span
        v-for="link in links"
        :key="link.name"
      >
        <a
          :href="link.Link"
          class="tertiary--text footer-links">{{ link.name }}</a>
      </span>
    </div>
    <v-spacer/>
    <span class="font-weight-light copyright">
      &copy;
      {{ (new Date()).getFullYear() }}
      Continental 
      <v-icon
        color="tertiary"
        style="margin: 0px 0px 2px 5px;"
        size="17">mdi-cloud</v-icon>
    
    </span>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    links: [
      { name: 'Home', Link: '/dashboard' },
      { name: 'Connext', Link: '/dashboard' },
      { name: 'Request help', Link: '/dashboard' },
      { name: 'Updates', Link: '/dashboard' }
    ]
  })
}
</script>

<style>
#core-footer {
  z-index: 0;
}
</style>
