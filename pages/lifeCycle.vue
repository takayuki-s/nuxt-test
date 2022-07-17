<template>
  <div>
    life cycle
  </div>
</template>

<script>
export default {
  asyncData() {
    console.log('asyncData') // eslint-disable-line no-console
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