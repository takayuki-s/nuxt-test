<template>
  <div>
    about<br>
    {{ now }}<br>
    <img src="~/assets/images/mountain.jpg" width="300px"><br>
    <div class="red-b">assets/cssテスト</div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      now: null
    }
  },
  mounted() {
    this.now = this.$dayjs().format('YYYY-MM-DD HH:mm:ss')
  }
}
</script>