<template>
  <div>
      <footer class="footer">
        © {{ date }} {{ 2024 }}
        <span class="d-none d-sm-inline-block"> - Todos os direitos reservados </span>.
      </footer>
  </div>
</template>

<script>
export default {
  name: "FooterSite",
  data: () => {
    return {
      date: ''
    }
  },
  mounted() {
    var dt = new Date();
    this.date = dt.getFullYear();
  }
}
</script>

<style scoped>

</style>