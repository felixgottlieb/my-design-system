<script>
  export let type;
</script>

<div class={type}><slot /></div>

<style>
  div {
    border-radius: 100%;
    background-color: var(--default-color);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: white;
    font: "Roboto", sans-serif;
    font-weight: 400;

    font-family: var(--primary-font);
  }
  .XL {
    width: 5rem;
    height: 5rem;
    font-size: 25px;
  }
  .L {
    width: 4rem;
    height: 4rem;
    font-size: 18px;
  }
  .M {
    width: 3rem;
    height: 3rem;
    font-size: 16px;
  }

  .S {
    width: 2rem;
    height: 2rem;
    font-size: 14px;
  }
</style>
