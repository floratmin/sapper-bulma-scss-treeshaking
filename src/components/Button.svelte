<style lang="scss">
  @import "../../scss/variables";
  a {
    color: $orange;
  }
</style>

<script>
  export let href;
  export let linktext;
</script>

<a {href} class="button">{linktext}</a>