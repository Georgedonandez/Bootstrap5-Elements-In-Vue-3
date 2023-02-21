<template>
    <div class="container">
      <div class="card">
        <img alt="VueBoot logo" src="../assets/vueplusboot.png" />
      </div>
        <h1 style="color: purple"><strong>{{ msg }}</strong></h1>>
        <img alt="Vue logo" src="../assets/breadcrumb.png" />
        <p>
            For a guide and recipes on how to configure / customize this component,<br>
            check out the
            <a href="https://getbootstrap.esdocu.com/docs/5.1/components/breadcrumb/" target="_blank" rel="noopener">Breadcrumps documentation</a>.
        </p>
        
        <h1><mark>[4.1]. Rutas Básicas</mark></h1>
        <nav aria-label="breadcrumb">
          <ol class="breadcrumb">
            <li class="breadcrumb-item active" aria-current="page">Inicio</li>
          </ol>
        </nav>
        <nav aria-label="breadcrumb">
          <ol class="breadcrumb">
            <li class="breadcrumb-item"><a href="#">Inicio</a></li>
            <li class="breadcrumb-item active" aria-current="page">Biblioteca</li>
          </ol>
        </nav>
        <nav aria-label="breadcrumb">
          <ol class="breadcrumb">
            <li class="breadcrumb-item"><a href="#">Inicio</a></li>
            <li class="breadcrumb-item"><a href="#">Biblioteca</a></li>
            <li class="breadcrumb-item active" aria-current="page">Datos</li>
          </ol>
        </nav>

        <h1><mark>[4.2]. Rutas con Divisores</mark></h1>
        <nav style="--bs-breadcrumb-divider: '>';" aria-label="breadcrumb">
          <ol class="breadcrumb">
            <li class="breadcrumb-item"><a href="#">Inicio</a></li>
            <li class="breadcrumb-item active" aria-current="page">Biblioteca</li>
          </ol>
        </nav>
        <nav style="--bs-breadcrumb-divider: url(&#34;data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='8' height='8'%3E%3Cpath d='M2.5 0L1 1.5 3.5 4 1 6.5 2.5 8l4-4-4-4z' fill='currentColor'/%3E%3C/svg%3E&#34;);" aria-label="breadcrumb">
          <ol class="breadcrumb">
            <li class="breadcrumb-item"><a href="#">Inicio</a></li>
            <li class="breadcrumb-item active" aria-current="page">Biblioteca</li>
          </ol>
        </nav>
        <nav style="--bs-breadcrumb-divider: '';" aria-label="breadcrumb">
          <ol class="breadcrumb">
            <li class="breadcrumb-item"><a href="#">Inicio</a></li>
            <li class="breadcrumb-item active" aria-current="page">Biblioteca</li>
          </ol>
        </nav>
        
    </div>
</template>

<script>
export default {
  name: 'BreadCrumb',
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