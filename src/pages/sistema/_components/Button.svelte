<script>
export let label;
export let width;
export let height;
</script>

<button style="--width: {width}; --height: {height}">
  {label}
</button>

<style>
button {
  background-color: #FC363B;
  font-family: Karla;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  color: #FFFFFF;

  border: none;
  border-radius: 7px;
  width: var(--width);
  height: var(--height);
}
</style>