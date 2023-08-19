<script>
  export let type = "primary";
  export let disabled = false;
</script>

<button class={type} class:disabled={disabled}>
  <slot></slot>
</button>

<style>
button {
  border: 2px solid black;
  cursor: pointer;
  border-radius: 10px;
  padding: 10px;
  box-shadow: 2px rgba (0,0,0,0.2);
  margin: 5px;
}
.primary{
  background: green;
}
.secondary{
  background: blue;
}
.disabled{
  background: grey;
  cursor: none;
}
</style>