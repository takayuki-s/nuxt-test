<template>
  <div>
    life cycle
  </div>
</template>

<script>
export default {
  asyncData( { route, isDev, app, $axios } ) {
    console.log('asyncData') // eslint-disable-line no-console
    console.log('route.name: ', route.name) // eslint-disable-line no-console
    console.log('idDev: ', isDev) // eslint-disable-line no-console
    console.log('app: ', app) // eslint-disable-line no-console
    console.log('app.$axios: ', app.$axios) // eslint-disable-line no-console
    console.log('$axios: ', $axios) // eslint-disable-line no-console
  },
  fetch( context ) {
    console.log('fetch') // eslint-disable-line no-console
    console.log(context.route.name) // eslint-disable-line no-console
  },
  created() {
    console.log('created') // eslint-disable-line no-console
  },
}
</script>