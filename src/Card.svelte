<script>
  import Button from "./Button.svelte";
  import Badge from "./Badge.svelte";
</script>

<div class="container">
  <img src="../img/shoe.png" alt="" />
  <div class="title-div">
    <p class="title">Shoes!</p>
    <Badge type="secondary">NEW</Badge>
  </div>
  <p>If a dog chews shoes whose shoes does he choose?</p>
  <div class="badges-div">
    <Badge type="ghost">Fashion</Badge>
    <Badge type="ghost">Products</Badge>
  </div>
  <div class="button-div">
    <Button type="primary">BUY NOW</Button>
  </div>
</div>

<style>
  p {
    margin-left: 1rem;
    margin-top: 5px;
    margin-bottom: 5px;
  }
  img {
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
  }
  .container {
    background-color: whitesmoke;
    border-radius: 20px;
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
    max-width: 25rem;
    font-family: "Roboto", sans-serif;
    font-weight: 400;
    font-size: 15px;
    box-shadow: 4px 4px 4px hsl(0 0% 60% /40%);
  }
  .title-div {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 10px;
    margin: 0;
    padding: 0;
  }
  .title {
    margin-left: 1rem;
    font-weight: 500;
    font-size: 20px;
    margin-top: 10px;
  }
  .badges-div {
    display: flex;
    flex-direction: row;
    gap: 5px;
    margin-left: 1rem;
    margin-bottom: 0;
    margin-top: 0;
  }
  .button-div {
    display: flex;
    margin-bottom: 1rem;
    margin-right: 1rem;
    flex-direction: row-reverse;
  }
</style>
