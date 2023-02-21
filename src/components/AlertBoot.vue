<template>
  <div class="container">
    <div class="card">
        <img alt="VueBoot logo" src="../assets/vueplusboot.png" />
      </div> 
    <h1 style="color: purple"><strong>{{ msg }}</strong></h1>>
    <img alt="Vue logo" src="../assets/alert.png" />
    <p>
        For a guide and recipes on how to configure / customize this component,<br>
        check out the
        <a href="https://getbootstrap.esdocu.com/docs/5.1/components/alerts/" target="_blank" rel="noopener">Alerts documentation</a>.
    </p>

    <h1><mark> [2.1] Alertas Simples</mark></h1>
    <div class="alert alert-primary" role="alert">
        Una simple alerta primary: ¡échale un vistazo!
    </div>
    <div class="alert alert-secondary" role="alert">
        Una simple alerta secondary: ¡échale un vistazo!
    </div>
    <div class="alert alert-success" role="alert">
        Una simple alerta success: ¡échale un vistazo!
    </div>
    <div class="alert alert-danger" role="alert">
        Una simple alerta danger: ¡échale un vistazo!
    </div>
    <div class="alert alert-warning" role="alert">
        Una simple alerta warning: ¡échale un vistazo!
    </div>
    <div class="alert alert-info" role="alert">
        Una simple alerta info: ¡échale un vistazo!
    </div>
    <div class="alert alert-light" role="alert">
        Una simple alerta light: ¡échale un vistazo!
    </div>
    <div class="alert alert-dark" role="alert">
        Una simple alerta dark: ¡échale un vistazo!
    </div>

    <h1><mark>[2.2] Alerta en Vivo</mark></h1>
    <div id="liveAlertPlaceholder">
      <button type="button" class="btn btn-primary" id="liveAlertBtn" style="margin: 20px" @click="myFunction">Mostrar alerta en vivo</button>
    </div>

    <h1><mark>[2.3] Alertas con Enlaces de Colores</mark></h1>
    <div class="alert alert-primary" role="alert">
      Una simple alerta primary con <a href="#" class="alert-link">un enlace de ejemplo</a>. Dale un clic si quieres.
    </div>
    <div class="alert alert-secondary" role="alert">
      Una simple alerta secondary con <a href="#" class="alert-link">un enlace de ejemplo</a>. Dale un clic si quieres.
    </div>
    <div class="alert alert-success" role="alert">
      Una simple alerta success con <a href="#" class="alert-link">un enlace de ejemplo</a>. Dale un clic si quieres.
    </div>
    <div class="alert alert-danger" role="alert">
      Una simple alerta danger con <a href="#" class="alert-link">un enlace de ejemplo</a>. Dale un clic si quieres.
    </div>
    <div class="alert alert-warning" role="alert">
      Una simple alerta warning con <a href="#" class="alert-link">un enlace de ejemplo</a>. Dale un clic si quieres.
    </div>
    <div class="alert alert-info" role="alert">
      Una simple alerta info con <a href="#" class="alert-link">un enlace de ejemplo</a>. Dale un clic si quieres.
    </div>
    <div class="alert alert-light" role="alert">
      Una simple alerta light con <a href="#" class="alert-link">un enlace de ejemplo</a>. Dale un clic si quieres.
    </div>
    <div class="alert alert-dark" role="alert">
      Una simple alerta dark con <a href="#" class="alert-link">un enlace de ejemplo</a>. Dale un clic si quieres.
    </div>

    <h1><mark>[2.4] Alerta con Contenido Adicional</mark></h1>
    <div class="alert alert-success" role="alert">
      <h4 class="alert-heading">¡Bien hecho!</h4>
      <p>Oh, sí, leísto con éxito este importante mensaje de alerta. Este texto de ejemplo se extenderá un poco más para que puedas ver cómo funciona el espaciado dentro de una alerta con este tipo de contenido.</p>
      <hr>
      <p class="mb-0">Siempre que lo necesites, asegúrate de usar utilidades de margen para mantener las cosas ordenadas y ordenadas.</p>
    </div>

    <h1><mark>[2.5] Alerta con Icono</mark></h1>
    <div class="alert alert-primary d-flex align-items-center" role="alert">
      <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-exclamation-triangle-fill flex-shrink-0 me-2" viewBox="0 0 16 16" role="img" aria-label="Warning:">
        <path d="M8.982 1.566a1.13 1.13 0 0 0-1.96 0L.165 13.233c-.457.778.091 1.767.98 1.767h13.713c.889 0 1.438-.99.98-1.767L8.982 1.566zM8 5c.535 0 .954.462.9.995l-.35 3.507a.552.552 0 0 1-1.1 0L7.1 5.995A.905.905 0 0 1 8 5zm.002 6a1 1 0 1 1 0 2 1 1 0 0 1 0-2z"/>
      </svg>
      <div>
        Un ejemplo de alerta con un icono
      </div>
    </div>

    <h1><mark>[2.6] Más Alertas con Iconos</mark></h1>
    <svg xmlns="http://www.w3.org/2000/svg" style="display: none;">
      <symbol id="check-circle-fill" fill="currentColor" viewBox="0 0 16 16">
        <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zm-3.97-3.03a.75.75 0 0 0-1.08.022L7.477 9.417 5.384 7.323a.75.75 0 0 0-1.06 1.06L6.97 11.03a.75.75 0 0 0 1.079-.02l3.992-4.99a.75.75 0 0 0-.01-1.05z"/>
      </symbol>
      <symbol id="info-fill" fill="currentColor" viewBox="0 0 16 16">
        <path d="M8 16A8 8 0 1 0 8 0a8 8 0 0 0 0 16zm.93-9.412-1 4.705c-.07.34.029.533.304.533.194 0 .487-.07.686-.246l-.088.416c-.287.346-.92.598-1.465.598-.703 0-1.002-.422-.808-1.319l.738-3.468c.064-.293.006-.399-.287-.47l-.451-.081.082-.381 2.29-.287zM8 5.5a1 1 0 1 1 0-2 1 1 0 0 1 0 2z"/>
      </symbol>
      <symbol id="exclamation-triangle-fill" fill="currentColor" viewBox="0 0 16 16">
        <path d="M8.982 1.566a1.13 1.13 0 0 0-1.96 0L.165 13.233c-.457.778.091 1.767.98 1.767h13.713c.889 0 1.438-.99.98-1.767L8.982 1.566zM8 5c.535 0 .954.462.9.995l-.35 3.507a.552.552 0 0 1-1.1 0L7.1 5.995A.905.905 0 0 1 8 5zm.002 6a1 1 0 1 1 0 2 1 1 0 0 1 0-2z"/>
      </symbol>
    </svg>
    <div class="alert alert-primary d-flex align-items-center" role="alert">
      <svg class="bi flex-shrink-0 me-2" width="24" height="24" role="img" aria-label="Info:"><use xlink:href="#info-fill"/></svg>
      <div>
        Un ejemplo de alerta con un icono
      </div>
    </div>
    <div class="alert alert-success d-flex align-items-center" role="alert">
      <svg class="bi flex-shrink-0 me-2" width="24" height="24" role="img" aria-label="Success:"><use xlink:href="#check-circle-fill"/></svg>
      <div>
        Un ejemplo de alerta success con un icono
      </div>
    </div>
    <div class="alert alert-warning d-flex align-items-center" role="alert">
      <svg class="bi flex-shrink-0 me-2" width="24" height="24" role="img" aria-label="Warning:"><use xlink:href="#exclamation-triangle-fill"/></svg>
      <div>
        Un ejemplo de alerta warning con un icono
      </div>
    </div>
    <div class="alert alert-danger d-flex align-items-center" role="alert">
      <svg class="bi flex-shrink-0 me-2" width="24" height="24" role="img" aria-label="Danger:"><use xlink:href="#exclamation-triangle-fill"/></svg>
      <div>
        Un ejemplo de alerta danger con un icono
      </div>
    </div>     

    <h1><mark>[2.7] Alerta Descartable</mark></h1>
    <div class="alert alert-danger alert-dismissible fade show" role="alert">
      <strong>!Holy guacamole!</strong> Debes verificar algunos de esos campos a continuación. Esta alerta desaparecerá de la página (DOM) cuando la cierres.
      <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
    </div>

  </div> 
</template>

<script>
export default {
  name: 'AlertBoot',
  props: {
    msg: String
  },
  methods: { 
    myFunction () {
      /*CODIGO JS DE DOCUMENTACION OFICIAL. INICIO*/
      var alertPlaceholder = document.getElementById('liveAlertPlaceholder')
      var alertTrigger = document.getElementById('liveAlertBtn')

      function alert(message, type) {  
      var wrapper = document.createElement('div')
      wrapper.innerHTML = '<div class="alert alert-' + type + ' alert-dismissible fade show" role="alert">' + message 
        + '<button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close" onclick="location.reload()"></button></div>'

      alertPlaceholder.append(wrapper)
      /*location.reload()*/
      }

      if (alertTrigger) {
        alertTrigger.addEventListener('click', function () {
        alert('Genial, activaste este mensaje de alerta.', 'success')
        })
      } 
    }
      /*CODIGO JS DE DOCUMENTACION OFICIAL. FIN*/
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