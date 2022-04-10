<script>
  export let onClick;
</script>

<button class="button" on:click={onClick}>
  <slot />
</button>

<style>
  button {
		font-family: "IBM Plex Mono", monospace;
		font-size: 1rem;
		font-weight: 400;
		text-align: center;
		color: var(--colour-black);
    background: none;
    border: none;
    padding: 0;
    cursor: pointer;
  }
</style>