<script>
  let visible = true;
  function toggle() {
    visible = !visible;
  }
</script>

{#if visible}
  <a href="/" on:click={toggle}>remove</a>
{:else}
  <a href="/" on:click={toggle}>add</a>
{/if}
