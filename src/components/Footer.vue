<template>
  <footer class="ph3 ph4-ns pv4 bt b--black-10 black-70">
    <a href="mailto:" class="link b f3 f2-ns dim black-70 lh-solid">odohi.david@gmail.com</a>
    <p class="f6 db b ttu lh-solid">© {{date}} COMPANY Inc.</p>
    <div class="mt5">
      <a href="/language/" title="Language" class="f6 dib pr2 mid-gray dim">Language</a>
      <a href="/terms/" title="Terms" class="f6 dib ph2 mid-gray dim">Terms of Use</a>
      <a href="/privacy/" title="Privacy" class="f6 dib pl2 mid-gray dim">Privacy</a>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  props: {
    msg: String
  },
  data() {
    return {
      date: new Date().getFullYear()
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
