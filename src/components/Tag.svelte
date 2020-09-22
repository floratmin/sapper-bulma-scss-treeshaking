<script>
  export let label;
  export let classes = [];
</script>

<span class={["tag", ...classes].join(' ')}>{label}</span>