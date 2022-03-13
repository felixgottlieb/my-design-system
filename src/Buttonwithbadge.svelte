<script>
  import Button from "./Button.svelte";
  import Badge from "./Badge.svelte";
</script>

<div class="buttonbadge">
  <div class="button">
    <Button>INBOX</Button>
  </div>
  <div class="badge">
    <Badge type="secondary">99+</Badge>
  </div>
</div>

<style>
  .buttonbadge {
    display: contents;
  }
  .button {
    position: absolute;
    margin-top: 3rem;
    margin-right: 5rem;
  }
  .badge {
    position: absolute;
    margin-left: 0;
    margin-top: 0;
    margin: 0;
  }
</style>
