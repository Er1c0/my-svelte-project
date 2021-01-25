<script>
  let value=0;

  function handleClick() {
    value += 1;
  }
</script>
<style>
</style>
<button on:click={handleClick}>

  Click
</button>
<input type="text" style="width:100px;height: 180px;" value={value}>