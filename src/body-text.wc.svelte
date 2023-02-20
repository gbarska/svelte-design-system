<svelte:options tag="tk-body-text" />

<script>
    export let text = "";
    export let label = "";
</script>

<p class="body-text">
  {text}
</p>

<span class="body-label">
  {label}
</span>

<style>
  .body-text {
    color: var(--secondary-color);
    font-size: 18px;
  }
  .body-label {
    color: var(--primary-color);
    font-size: 12px;
  }
</style>
