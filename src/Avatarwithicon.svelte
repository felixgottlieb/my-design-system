<script>
  import Avatar from "./Avatar.svelte";
</script>

<div class="avatarbadge">
  <div class="w-badge">
    <slot />
  </div>
  <div class="badge">
    <div class="badgeicon" />
  </div>
</div>

<style>
  .w-badge {
    width: 4rem;
    height: 4rem;
    font-size: 18px;
    border-radius: 100%;
    background-color: var(--default-color);
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .avatarbadge {
    display: contents;
    color: white;
    font: "Roboto", sans-serif;
    font-weight: 400;

    font-family: var(--primary-font);
  }

  .w-badge {
    position: absolute;
    margin-top: 2.5rem;
  }
  .badge {
    position: absolute;
    margin-left: 3.3rem;
    margin-top: 0;
    width: 18px;
    height: 18px;
    border-radius: 100%;
    background-color: #66d09b;
    border: 1px white solid;
  }
</style>
