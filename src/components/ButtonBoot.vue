<template>
    <div class="container">
      <div class="card">
        <img alt="VueBoot logo" src="../assets/vueplusboot.png" />
      </div>
      <h1 style="color: purple"><strong>{{ msg }}</strong></h1>
      <img alt="Vue logo" src="../assets/button.png" />
        <p>
            For a guide and recipes on how to configure / customize this component,<br>
            check out the
            <a href="https://getbootstrap.esdocu.com/docs/5.1/components/buttons/" target="_blank" rel="noopener">Buttons documentation</a>.
         </p>
      
      <h1><mark>[5.1]  Botones Predefinidos</mark></h1>
      <button type="button" class="btn btn-primary">Primary</button>
      <button type="button" class="btn btn-secondary">Secondary</button>
      <button type="button" class="btn btn-success">Success</button>
      <button type="button" class="btn btn-danger">Danger</button>
      <button type="button" class="btn btn-warning">Warning</button>
      <button type="button" class="btn btn-info">Info</button>
      <button type="button" class="btn btn-light">Light</button>
      <button type="button" class="btn btn-dark">Dark</button>
      <button type="button" class="btn btn-link">Enlace</button>

      <h1><mark>[5.2] Etiquetas de Botón</mark></h1>
      <a class="btn btn-primary" href="#" role="button" style="margin: 10px">Enlace</a>
      <button class="btn btn-primary" type="submit">Botón</button>
      <input class="btn btn-primary" type="button" value="Input" style="margin: 10px">
      <input class="btn btn-primary" type="submit" value="Submit" style="margin: 10px">
      <input class="btn btn-primary" type="reset" value="Reset" style="margin: 10px">

      <h1><mark>[5.3] Botones de Contorno</mark></h1>
      <button type="button" class="btn btn-outline-primary">Primary</button>
      <button type="button" class="btn btn-outline-secondary">Secondary</button>
      <button type="button" class="btn btn-outline-success">Success</button>
      <button type="button" class="btn btn-outline-danger">Danger</button>
      <button type="button" class="btn btn-outline-warning">Warning</button>
      <button type="button" class="btn btn-outline-info">Info</button>
      <button type="button" class="btn btn-outline-light">Light</button>
      <button type="button" class="btn btn-outline-dark">Dark</button>

      <h1><mark>[5.4] Tamaños de Botones</mark></h1>
      <h3>Ejemplo 1</h3>
      <button type="button" class="btn btn-primary btn-lg">Botón grande</button>
      <button type="button" class="btn btn-secondary btn-lg">Botón grande</button>
      <h3>Ejemplo 2</h3>
      <button type="button" class="btn btn-primary btn-sm">Botón pequeño</button>
      <button type="button" class="btn btn-secondary btn-sm">Botón pequeño</button>

      <h1><mark>[5.5] Estado Deshabilitado de Botones</mark></h1>
      <h3>Ejemplo 1</h3>
      <button type="button" class="btn btn-lg btn-primary" disabled>Botón primary</button>
      <button type="button" class="btn btn-secondary btn-lg" disabled>Botón</button>
      <h3>Ejemplo 2</h3>
      <a class="btn btn-primary btn-lg disabled" role="button" aria-disabled="true">Enlace primary</a>
      <a class="btn btn-secondary btn-lg disabled" role="button" aria-disabled="true">Enlace</a>

      <h1><mark>[5.6] Advertencia de Funcionalidad de Enlace</mark></h1>
      <a href="#" class="btn btn-primary btn-lg disabled" tabindex="-1" role="button" aria-disabled="true">Enlace primary</a>
      <a href="#" class="btn btn-secondary btn-lg disabled" tabindex="-1" role="button" aria-disabled="true">Enlace</a>
      
      <h1><mark>[5.7] Botones de Bloque</mark></h1>
      <h3>Ejemplo 1</h3>
      <div class="d-grid gap-2">
          <button class="btn btn-primary" type="button">Botón</button>
          <button class="btn btn-primary" type="button">Botón</button>
      </div>
      <h3>Ejemplo 2</h3>
      <div class="d-grid gap-2 d-md-block">
          <button class="btn btn-primary" type="button">Botón</button>
          <button class="btn btn-primary" type="button">Botón</button>
      </div>
      <h3>Ejemplo 3</h3>
      <div class="d-grid gap-2 col-6 mx-auto">
          <button class="btn btn-primary" type="button">Botón</button>
          <button class="btn btn-primary" type="button">Botón</button>
      </div>
      <h3>Ejemplo 4</h3>
      <div class="d-grid gap-2 d-md-flex justify-content-md-end">
          <button class="btn btn-primary me-md-2" type="button">Botón</button>
          <button class="btn btn-primary" type="button">Botón</button>
      </div>
      
      <h1><mark>[5.8] Botones Complementarios (Toggle)</mark></h1>
      <h3>Ejemplo 1</h3>
      <button type="button" class="btn btn-primary" data-bs-toggle="button" autocomplete="off">Botón toggle</button>
      <button type="button" class="btn btn-primary active" data-bs-toggle="button" autocomplete="off" aria-pressed="true">Botón toggle activo</button>
      <button type="button" class="btn btn-primary" disabled data-bs-toggle="button" autocomplete="off">Botón toggle deshabilitado</button>
      <h3>Ejemplo 2</h3>
      <a href="#" class="btn btn-primary" role="button" data-bs-toggle="button">Enlace toggle</a>
      <a href="#" class="btn btn-primary active" role="button" data-bs-toggle="button" aria-pressed="true">Enlace toggle activo</a>
      <a class="btn btn-primary disabled" aria-disabled="true" role="button" data-bs-toggle="button">Enlace toggle deshabilitado</a>
    </div>
</template>

<script>
export default {
  name: 'ButtonBoot',
  props: {
    msg: String
  },
  methods: {

  }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
  margin: 10px;
}
button {
  margin: 10px;
}
h1 {
    margin: 10px 0 0;  
}
</style>