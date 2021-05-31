<script>
import Input from "./_components/Input.svelte";
import Button from "./_components/Button.svelte";
</script>

<div id="container">

  <div id="header">Login</div>

  <div id="container-inputs-buttons">
    <Input
      label="E-mail"
      placeholder="Exemplo: fulano@tal.com"
      width="35vw"
      height="10vh"
    />

    <Input
      label="Senha"
      placeholder="Exemplo: ******"
      width="35vw"
      height="10vh"
    />

    <Button
      label="Entrar"
      width="35vw"
      height="10vh"
    />
  </div>

</div>

<style>
#container {
  position: absolute;
  left: 19vw;
  top: 8vh;
}

#header {
  color: #FFFFFF;
  font-family: Spectral;
  font-style: normal;
  font-weight: bold;
  font-size: 3.5vmax;
  line-height: 10vh;
}

#container-inputs-buttons {
  margin-left: 15vw;
}
</style>