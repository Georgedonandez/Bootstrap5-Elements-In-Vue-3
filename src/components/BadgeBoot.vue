<template>
    <div class="container">
      <div class="card">
        <img alt="VueBoot logo" src="../assets/vueplusboot.png" />
      </div>
        <h1 style="color: purple"><strong>{{ msg }}</strong></h1>>
        <img alt="Vue logo" src="../assets/badge.png" />
        <p>
            For a guide and recipes on how to configure / customize this component,<br>
            check out the
            <a href="https://getbootstrap.esdocu.com/docs/5.1/components/badge/" target="_blank" rel="noopener">Badges documentation</a>.
        </p>

        <h1><mark>[3.1]. Insignias de Encabezados</mark></h1>
        <h1>Encabezado de ejemplo <span class="badge bg-secondary">Nuevo</span></h1>
        <h2>Encabezado de ejemplo <span class="badge bg-secondary">Nuevo</span></h2>
        <h3>Encabezado de ejemplo <span class="badge bg-secondary">Nuevo</span></h3>
        <h4>Encabezado de ejemplo <span class="badge bg-secondary">Nuevo</span></h4>
        <h5>Encabezado de ejemplo <span class="badge bg-secondary">Nuevo</span></h5>
        <h6>Encabezado de ejemplo <span class="badge bg-secondary">Nuevo</span></h6>

        <h1><mark>[3.2]. Insignia de Botón</mark></h1>
        <button type="button" class="btn btn-primary">
            Notificaciones <span class="badge bg-secondary">4</span>
        </button>

        <h1><mark>[3.3]. Insignias Posicionadas</mark></h1>
        <button type="button" class="btn btn-primary position-relative">
          Inbox
          <span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-danger">
            99+
            <span class="visually-hidden">mensajes no leídos</span>
          </span>
        </button>
        <button type="button" class="btn btn-primary position-relative">
          Perfil
          <span class="position-absolute top-0 start-100 translate-middle p-2 bg-danger border border-light rounded-circle">
            <span class="visually-hidden">Nuevas alertas</span>
          </span>
        </button>

        <h1><mark>[3.4]. Colores de Fondo de Insignias</mark></h1>
        <span class="badge bg-primary">Primary</span>
        <span class="badge bg-secondary">Secondary</span>
        <span class="badge bg-success">Success</span>
        <span class="badge bg-danger">Danger</span>
        <span class="badge bg-warning text-dark">Warning</span>
        <span class="badge bg-info text-dark">Info</span>
        <span class="badge bg-light text-dark">Light</span>
        <span class="badge bg-dark">Dark</span>

        <h1><mark>[3.5]. Insignias de Píldora</mark></h1>
        <span class="badge rounded-pill bg-primary">Primary</span>
        <span class="badge rounded-pill bg-secondary">Secondary</span>
        <span class="badge rounded-pill bg-success">Success</span>
        <span class="badge rounded-pill bg-danger">Danger</span>
        <span class="badge rounded-pill bg-warning text-dark">Warning</span>
        <span class="badge rounded-pill bg-info text-dark">Info</span>
        <span class="badge rounded-pill bg-light text-dark">Light</span>
        <span class="badge rounded-pill bg-dark">Dark</span>

    </div>
</template>

<script>
export default {
  name: 'BadgeBoot',
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