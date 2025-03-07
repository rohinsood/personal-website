<script>
  let { children } = $props();
  import "../app.css";
</script>
{@render children()}


<style lang="postcss">
  :global(html) {
    /* background-color: theme(colors.slate.50); */
    overflow: hidden;
  }
</style>