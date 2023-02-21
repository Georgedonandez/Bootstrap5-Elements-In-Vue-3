<template>
    <div class="container">
        <div class="card">
        <img alt="VueBoot logo" src="../assets/vueplusboot.png" />
      </div>
        <h1 style="color: purple"><strong>{{ msg }}</strong></h1>
        <img alt="Vue logo" src="../assets/button-group.png" />
            <p>
                For a guide and recipes on how to configure / customize this component,<br>
                check out the
                <a href="https://getbootstrap.esdocu.com/docs/5.1/components/button-group/" target="_blank" rel="noopener">Button-group documentation</a>.
            </p>
        
        <h1><mark>[6.1] Grupos de Botones Básicos</mark></h1>
        <div class="btn-group" role="group" aria-label="Basic example">
            <button type="button" class="btn btn-primary">Izquierdo</button>
            <button type="button" class="btn btn-primary">Medio</button>
            <button type="button" class="btn btn-primary">Derecho</button>
        </div>  
        <div class="btn-group">
            <a href="#" class="btn btn-primary active" aria-current="page">Enlace activo</a>
            <a href="#" class="btn btn-primary">Enlace</a>
            <a href="#" class="btn btn-primary">Enlace</a>
        </div>
    
        <h1><mark>[6.2] Estilos Mixtos de Grupos de Botones</mark></h1>
        <div class="btn-group" role="group" aria-label="Basic mixed styles example">
            <button type="button" class="btn btn-danger">Izquierda</button>
            <button type="button" class="btn btn-warning">Medio</button>
            <button type="button" class="btn btn-success">Derecha</button>
        </div>

        <h1><mark>[6.3] Estilos de Contorno de Grupos de Botones</mark></h1>
        <div class="btn-group" role="group" aria-label="Basic outlined example">
            <button type="button" class="btn btn-outline-primary">Izquierda</button>
            <button type="button" class="btn btn-outline-primary">Medio</button>
            <button type="button" class="btn btn-outline-primary">Derecha</button>
        </div>

        <h1><mark>[6.4] Grupos de Botones Checkbox y Radio</mark></h1>
        <div class="btn-group" role="group" aria-label="Basic checkbox toggle button group">
            <input type="checkbox" class="btn-check" id="btncheck1" autocomplete="off">
            <label class="btn btn-outline-primary" for="btncheck1">Checkbox 1</label>

            <input type="checkbox" class="btn-check" id="btncheck2" autocomplete="off">
            <label class="btn btn-outline-primary" for="btncheck2">Checkbox 2</label>

            <input type="checkbox" class="btn-check" id="btncheck3" autocomplete="off">
            <label class="btn btn-outline-primary" for="btncheck3">Checkbox 3</label>
        </div>  
        <div class="btn-group" role="group" aria-label="Basic radio toggle button group">
            <input type="radio" class="btn-check" name="btnradio" id="btnradio1" autocomplete="off" checked>
            <label class="btn btn-outline-primary" for="btnradio1">Radio 1</label>

            <input type="radio" class="btn-check" name="btnradio" id="btnradio2" autocomplete="off">
            <label class="btn btn-outline-primary" for="btnradio2">Radio 2</label>

            <input type="radio" class="btn-check" name="btnradio" id="btnradio3" autocomplete="off">
            <label class="btn btn-outline-primary" for="btnradio3">Radio 3</label>            
        </div>

        <h1><mark>[6.5] Grupos de Botones Toolbar</mark></h1>
        <div class="btn-toolbar" role="toolbar" aria-label="Toolbar with button groups">
            <div class="btn-group me-2" role="group" aria-label="First group">
                <button type="button" class="btn btn-primary">1</button>
                <button type="button" class="btn btn-primary">2</button>
                <button type="button" class="btn btn-primary">3</button>
                <button type="button" class="btn btn-primary">4</button>
            </div>
            <div class="btn-group me-2" role="group" aria-label="Second group">
                <button type="button" class="btn btn-secondary">5</button>
                <button type="button" class="btn btn-secondary">6</button>
                <button type="button" class="btn btn-secondary">7</button>
            </div>
            <div class="btn-group" role="group" aria-label="Third group">
                <button type="button" class="btn btn-info">8</button>
            </div>
        </div>
        <div class="btn-toolbar mb-3" role="toolbar" aria-label="Toolbar with button groups">
            <div class="btn-group me-2" role="group" aria-label="First group">
                <button type="button" class="btn btn-outline-secondary">1</button>
                <button type="button" class="btn btn-outline-secondary">2</button>
                <button type="button" class="btn btn-outline-secondary">3</button>
                <button type="button" class="btn btn-outline-secondary">4</button>
            </div>
            <div class="input-group">
                <div class="input-group-text" id="btnGroupAddon">@</div>
                <input type="text" class="form-control" placeholder="Input group example" aria-label="Input group example" aria-describedby="btnGroupAddon">
            </div>
        </div>
        <div class="btn-toolbar justify-content-between" role="toolbar" aria-label="Toolbar with button groups">
            <div class="btn-group" role="group" aria-label="First group">
                <button type="button" class="btn btn-outline-secondary">1</button>
                <button type="button" class="btn btn-outline-secondary">2</button>
                <button type="button" class="btn btn-outline-secondary">3</button>
                <button type="button" class="btn btn-outline-secondary">4</button>
            </div>
            <div class="input-group">
                <div class="input-group-text" id="btnGroupAddon2">@</div>
                <input type="text" class="form-control" placeholder="Input group example" aria-label="Input group example" aria-describedby="btnGroupAddon2">
            </div>
        </div>

        <h1><mark>[6.6] Dimensionamiento de Grupos de Botones</mark></h1>
        <div class="btn-group btn-group-lg" role="group" aria-label="Basic outlined example">
            <button type="button" class="btn btn-outline-primary">Izquierda</button>
            <button type="button" class="btn btn-outline-primary">Medio</button>
            <button type="button" class="btn btn-outline-primary">Derecha</button>
        </div>
        <div class="btn-group" role="group" aria-label="Basic outlined example">
            <button type="button" class="btn btn-outline-primary">Izquierda</button>
            <button type="button" class="btn btn-outline-primary">Medio</button>
            <button type="button" class="btn btn-outline-primary">Derecha</button>
        </div>
        <div class="btn-group btn-group-sm" role="group" aria-label="Basic outlined example">
            <button type="button" class="btn btn-outline-primary">Izquierda</button>
            <button type="button" class="btn btn-outline-primary">Medio</button>
            <button type="button" class="btn btn-outline-primary">Derecha</button>
        </div>

        <h1><mark>[6.7] Anidamiento de Grupos de Botones</mark></h1>    
        <div class="btn-group" role="group" aria-label="Button group with nested dropdown">
            <button type="button" class="btn btn-primary">1</button>
            <button type="button" class="btn btn-primary">2</button>    
            <div class="btn-group" role="group">
                <button id="btnGroupDrop1" type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown" aria-expanded="false">
                Dropdown
                </button>
                <ul class="dropdown-menu" aria-labelledby="btnGroupDrop1">
                <li><a class="dropdown-item" href="#">Enlace dropdown</a></li>
                <li><a class="dropdown-item" href="#">Enlace dropdown</a></li>
                </ul>
            </div>
        </div>

        <h1><mark>[6.8] Grupos Verticales de Botones</mark></h1>           
        <div class="btn-group-vertical" role="group" aria-label="Basic example">
            <button type="button" class="btn btn-secondary">Left</button>
            <button type="button" class="btn btn-secondary">Middle</button>
            <button type="button" class="btn btn-secondary">Right</button>
        </div>
        
        <div class="btn-group-vertical" role="group" aria-label="Button group with nested dropdown">
            <button type="button" class="btn btn-primary">1</button>
            <button type="button" class="btn btn-primary">2</button>    
            <div class="btn-group" role="group">
                <button id="btnGroupDrop1" type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown" aria-expanded="false">
                Dropdown
                </button>
                <ul class="dropdown-menu" aria-labelledby="btnGroupDrop1">
                <li><a class="dropdown-item" href="#">Enlace dropdown</a></li>
                <li><a class="dropdown-item" href="#">Enlace dropdown</a></li>
                </ul>
            </div>
        </div>        


    </div>
</template>

<script>
export default {
  name: 'ButtonGroup',
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
  margin: 1px;
}
/*
button {
  margin: 1px;
}
*/
h1 {
    margin: 10px 0 0;  
}
</style>