<template>
  <footer class="footer">
    <div class="container-fluid">
      <div class="copyright">
         Copyright &copy; {{ year }} - <a href="https://www.segurit.ga">SEGURIT</a>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>
<style></style>
