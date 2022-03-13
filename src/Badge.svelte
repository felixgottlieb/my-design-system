<script>
  export let type;
</script>

<div class={type}><slot /></div>

<style>
  div {
    height: 1.3rem;
    max-width: 5rem;
    padding-left: 1rem;
    padding-right: 1rem;
    border-radius: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    border: none;
    font-family: "Roboto", sans-serif;
    font-weight: 400;
    font-size: 15px;
    background: var(--default-color);
    color: var(--primary-font-color);
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
    border: 1px solid black;
  }
</style>
