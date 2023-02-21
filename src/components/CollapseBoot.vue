<template>
    <div class="container">
        <div class="card">
            <img alt="VueBoot logo" src="../assets/vueplusboot.png" />
        </div>
        <h1 style="color: purple"><strong>{{ msg }}</strong></h1>
        <img alt="Vue logo" src="../assets/collapse.png" />
            <p>
                For a guide and recipes on how to configure / customize this component,<br>
                check out the
                <a href="https://getbootstrap.esdocu.com/docs/5.1/components/collapse/" target="_blank" rel="noopener">Collapse documentation</a>.
            </p>
            
        <h1><mark>[10.1] Colapsos Básicos</mark></h1>
        <p>
            <a class="btn btn-primary" data-bs-toggle="collapse" href="#collapseExample" role="button" aria-expanded="false" aria-controls="collapseExample">
                Enlace con href
            </a>
            <button class="btn btn-primary" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
                Botón con data-bs-target
            </button>
        </p>
        <div class="collapse" id="collapseExample">
            <div class="card card-body">
                Algún contenido placeholder para el componente de contracción. Este panel está oculto de forma predeterminada, pero se revela cuando el usuario activa el disparador correspondiente.
            </div>
        </div>

        <h1><mark>[10.2] Colapso Horizontal</mark></h1>
        <p>
            <button class="btn btn-primary" type="button" data-bs-toggle="collapse" data-bs-target="#collapseWidthExample" aria-expanded="false" aria-controls="collapseWidthExample">
                Toggle con collapse
            </button>
        </p>
        <div style="min-height: 120px;">
            <div class="collapse collapse-horizontal" id="collapseWidthExample">
                <div class="card card-body" style="width: 300px;">
                    Este es un contenido placeholder para un colapso horizontal. Está oculto de forma predeterminada y se muestra cuando se activa.
                </div>
            </div>
        </div>

        <h1><mark>[10.3] Colapso de Múltiples Objetivos</mark></h1>
        <p>
            <a class="btn btn-primary" data-bs-toggle="collapse" href="#multiCollapseExample1" role="button" aria-expanded="false" aria-controls="multiCollapseExample1">Alternar el primer elemento</a>
            <button class="btn btn-primary" type="button" data-bs-toggle="collapse" data-bs-target="#multiCollapseExample2" aria-expanded="false" aria-controls="multiCollapseExample2">Alternar el segundo elemento</button>
            <button class="btn btn-primary" type="button" data-bs-toggle="collapse" data-bs-target=".multi-collapse" aria-expanded="false" aria-controls="multiCollapseExample1 multiCollapseExample2">Alternar ambos elementos</button>
        </p>
        <div class="row">
            <div class="col">
                <div class="collapse multi-collapse" id="multiCollapseExample1">
                    <div class="card card-body">
                        Algún contenido placeholder para el primer componente de colapso de este ejemplo de colapso múltiple. Este panel está oculto de forma predeterminada, pero se revela cuando el usuario activa el disparador correspondiente.
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="collapse multi-collapse" id="multiCollapseExample2">
                    <div class="card card-body">
                        Parte del contenido placeholder para el segundo componente de contracción de este ejemplo de contracción múltiple. Este panel está oculto de forma predeterminada, pero se revela cuando el usuario activa el disparador correspondiente.
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'CollapseBoot',
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