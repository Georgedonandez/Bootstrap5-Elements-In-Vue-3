<template>
    <div class="container">
        <div class="card">
            <img alt="VueBoot logo" src="../assets/vueplusboot.png" />
        </div>        
        <h1 style="color: purple"><strong>{{ msg }}</strong></h1>
        <img alt="Vue logo" src="../assets/accordion.png" />
        <p>
            For a guide and recipes on how to configure / customize this component,<br>
            check out the
            <a href="https://getbootstrap.esdocu.com/docs/5.1/components/accordion/" target="_blank" rel="noopener">Accordion documentation</a>.
         </p>
        <h1><mark>[1.1] Acordeones Simples</mark></h1>
        <div class="accordion" id="accordionExample">
            <div class="accordion-item">
                <h2 class="accordion-header" id="headingOne">
                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                        Acordeón artículo #1
                    </button>
                </h2>
                <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
                    <div class="accordion-body">
                        <strong>Este es el cuerpo del acordeón del primer elemento.</strong> Se muestra de forma predeterminada, hasta que el complemento de colapso agrega las clases apropiadas que usamos para diseñar cada elemento. Estas clases controlan la apariencia general, así como la visualización y ocultación a través de transiciones CSS. Puedes modificar cualquiera de esto con CSS personalizado o sobrescribir nuestras variables predeterminadas. También vale la pena señalar que casi cualquier HTML puede ir dentro de <code>.accordion-body</code>, aunque la transición limita el desbordamiento.
                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header" id="headingTwo">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                        Acordeón artículo #2
                    </button>
                </h2>
                <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
                    <div class="accordion-body">
                        <strong>Este es el cuerpo del acordeón del segundo elemento.</strong> Está oculto de manera predeterminada, hasta que el complemento de Collapse agregue las clases apropiadas que usamos para diseñar cada elemento. Estas clases controlan la apariencia general, así como la visualización y ocultación a través de transiciones CSS. Puedes modificar cualquiera de esto con CSS personalizado o sobrescribir nuestras variables predeterminadas. También vale la pena señalar que casi cualquier HTML puede ir dentro de <code>.accordion-body</code>, aunque la transición limita el desbordamiento.
                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header" id="headingThree">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                        Acordeón artículo #3
                    </button>
                </h2>
                <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                    <div class="accordion-body">
                        <strong>Este es el cuerpo del acordeón del tercer elemento.</strong> Está oculto de manera predeterminada, hasta que el complemento Collapse agregue las clases apropiadas que usamos para diseñar cada elemento. Estas clases controlan la apariencia general, así como la visualización y ocultación a través de transiciones CSS. Puedes modificar cualquiera de esto con CSS personalizado o sobrescribir nuestras variables predeterminadas. También vale la pena señalar que casi cualquier HTML puede ir dentro de <code>.accordion-body</code>, aunque la transición limita el desbordamiento.
                    </div>
                </div>
            </div>
        </div>

        <h1><mark> [1.2] Acordeones Con Flush</mark></h1>
        <div class="accordion accordion-flush" id="accordionFlushExample">
            <div class="accordion-item">
                <h2 class="accordion-header" id="flush-headingOne">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
                        Acordeón artículo #1
                    </button>
                </h2>
                <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
                    <div class="accordion-body">Contenido placeholder para este acordeón, que pretende demostrar la clase <code>.accordion-flush</code>. Este es el cuerpo de acordeón del primer elemento.</div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header" id="flush-headingTwo">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
                        Acordeón artículo #2
                    </button>
                </h2>
                <div id="flush-collapseTwo" class="accordion-collapse collapse" aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">
                    <div class="accordion-body">Contenido placeholder para este acordeón, que pretende demostrar la clase <code>.accordion-flush</code>. Este es el cuerpo del acordeón del segundo elemento. Imaginemos que esto se llena con algún contenido real.</div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header" id="flush-headingThree">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
                        Acordeón artículo #3
                    </button>
                </h2>
                <div id="flush-collapseThree" class="accordion-collapse collapse" aria-labelledby="flush-headingThree" data-bs-parent="#accordionFlushExample">
                    <div class="accordion-body">Contenido placeholder para este acordeón, que pretende demostrar la clase <code>.accordion-flush</code>. Este es el cuerpo del acordeón del tercer elemento. No sucede nada más emocionante aquí en términos de contenido, sino simplemente llenar el espacio para que se vea, al menos a primera vista, un poco más representativo de cómo se vería esto en una aplicación del mundo real.</div>
                </div>
            </div>
        </div>        

        <h1><mark>[1.3] Acordeones Siempre Abiertos</mark></h1>
        <div class="accordion" id="accordionPanelsStayOpenExample">
            <div class="accordion-item">
                <h2 class="accordion-header" id="panelsStayOpen-headingOne">
                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapseOne" aria-expanded="true" aria-controls="panelsStayOpen-collapseOne">
                        Acordeón artículo #1
                    </button>
                </h2>
                <div id="panelsStayOpen-collapseOne" class="accordion-collapse collapse show" aria-labelledby="panelsStayOpen-headingOne">
                    <div class="accordion-body">
                        <strong>Este es el cuerpo del acordeón del primer elemento.</strong> Se muestra de forma predeterminada, hasta que el complemento Collapse agrega las clases apropiadas que usamos para diseñar cada elemento. Estas clases controlan la apariencia general, así como la visualización y ocultación a través de transiciones CSS. Puedes modificar cualquiera de esto con CSS personalizado o sobrescribir nuestras variables predeterminadas. También vale la pena señalar que casi cualquier HTML puede ir dentro de <code>.accordion-body</code>, aunque la transición limita el desbordamiento.
                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header" id="panelsStayOpen-headingTwo">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapseTwo" aria-expanded="false" aria-controls="panelsStayOpen-collapseTwo">
                        Acordeón artículo #2
                    </button>
                </h2>
                <div id="panelsStayOpen-collapseTwo" class="accordion-collapse collapse" aria-labelledby="panelsStayOpen-headingTwo">
                    <div class="accordion-body">
                        <strong>Este es el cuerpo del acordeón del segundo elemento.</strong> Está oculto de manera predeterminada, hasta que el complemento Collapse agregue las clases apropiadas que usamos para diseñar cada elemento. Estas clases controlan la apariencia general, así como la visualización y ocultación a través de transiciones CSS. Puedes modificar cualquiera de esto con CSS personalizado o sobrescribr nuestras variables predeterminadas. También vale la pena señalar que casi cualquier HTML puede ir dentro de <code>.accordion-body</code>, aunque la transición limita el desbordamiento.
                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header" id="panelsStayOpen-headingThree">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapseThree" aria-expanded="false" aria-controls="panelsStayOpen-collapseThree">
                        Acordeón artículo #3
                    </button>
                </h2>
                <div id="panelsStayOpen-collapseThree" class="accordion-collapse collapse" aria-labelledby="panelsStayOpen-headingThree">
                    <div class="accordion-body">
                        <strong>Este es el cuerpo del acordeón del tercer elemento.</strong> Está oculto de manera predeterminada, hasta que el complemento Collapse agregue las clases apropiadas que usamos para diseñar cada elemento. Estas clases controlan la apariencia general, así como la visualización y ocultación a través de transiciones CSS. Puedes modificar cualquiera de esto con CSS personalizado o sobrescribir nuestras variables predeterminadas. También vale la pena señalar que casi cualquier HTML puede ir dentro de <code>.accordion-body</code>, aunque la transición limita el desbordamiento.
                    </div>
                </div>
            </div>
        </div>
  
    </div>
</template>

<script>
export default {
  name: 'AccordionBoot',
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
button {
  margin: 10px;
}
h1 {
    margin: 10px 0 0;  
}
</style>