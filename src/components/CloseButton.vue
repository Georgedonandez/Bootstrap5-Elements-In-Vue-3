<template>
    <div class="container">
        <div class="card">
            <img alt="VueBoot logo" src="../assets/vueplusboot.png" />
        </div>
        <h1 style="color: purple"><strong>{{ msg }}</strong></h1>
        <img alt="Vue logo" src="../assets/closebutton.png" />
            <p>
                For a guide and recipes on how to configure / customize this component,<br>
                check out the
                <a href="https://getbootstrap.esdocu.com/docs/5.1/components/close-button/" target="_blank" rel="noopener">Close Button documentation</a>.
            </p>
        
        <h1><mark>[9.1] Botón de Cierre Genérico</mark></h1> 
        <div class="bd-example">
            <button type="button" class="btn-close" aria-label="Close"></button>
        </div>

        <h1><mark>[9.2] Botón de Cierre Deshabilitado</mark></h1>
        <div class="bd-example">
            <button type="button" class="btn-close" disabled aria-label="Cerrar"></button>
        </div>

        <h1><mark>[9.3] Variante Clara</mark></h1>
        <div class="bd-example bg-dark">
            <button type="button" class="btn-close btn-close-white" aria-label="Cerrar"></button>
            <button type="button" class="btn-close btn-close-white" disabled aria-label="Cerrar"></button>
        </div>

    </div>

</template>

<script>
export default {
  name: 'CloseButton',
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
}
span {
  margin: 5px;
}
button {
  margin: 10px;
}
h1 {
    margin: 10px 0 0;  
}    
</style>



