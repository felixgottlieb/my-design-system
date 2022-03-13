<script>
  export let type;
  export let mode;
</script>

<button class:inversed={mode === "inversed"} class={type}><slot /></button>

<style>
  button {
    padding-top: 1rem;
    padding-bottom: 1rem;
    padding-right: 1.5rem;
    padding-left: 1.5rem;
    max-height: 4rem;
    max-width: 9rem;
    border-radius: 10px;
    border: 1px;
    font: "Roboto", sans-serif;
    font-weight: var(--button-font-weight);
    background: var(--default-color);
    color: var(--primary-font-color);
  }
  button:hover {
    background: white;
    color: black;
    border: solid 1px black;
    border-radius: 10px;
  }
  .primary {
    background: var(--primary-color);
  }
  .secondary {
    background: var(--secondary-color);
  }
  .accent {
    color: var(--primary-font-color);
    background: var(--accent-color);
  }

  .ghost {
    color: var(--secondary-font-color);
    background: var(--ghost);
  }
  .link {
    color: var(--link-font-color);
    background: var(--link);
  }
</style>
