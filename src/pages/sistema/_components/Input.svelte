<script>
export let label;
export let placeholder;
export let width;
export let height;
</script>

<div id="container">
  <div id="label">{label}</div>
  <input type="text" placeholder={placeholder} style="--width: {width}; --height: {height}" />
</div>

<style>
div#container {
  margin: 1.5vh auto;
}

div#label {
  font-family: Karla;
  font-style: normal;
  font-weight: normal;
  font-size: 3.7vmin;
  color: #BFCED9;

  margin-bottom: 0.7vh;
}

input {
  border: none;
  border-radius: 7px;
  padding-left: 20px;
  width: var(--width);
  height: var(--height);
}

input:focus {
  border: 3px solid #4D4DFF;
  outline: none;
}

::placeholder {
  color: #BFCED9;
  opacity: 1; /* Firefox */
}
</style>