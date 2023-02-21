<template>
    <div class="container">
        <div class="card">
            <img alt="VueBoot logo" src="../assets/vueplusboot.png" />
        </div>
        <h1 style="color: purple"><strong>{{ msg }}</strong></h1>
        <img alt="Vue logo" src="../assets/carousel.png" />
            <p>
                For a guide and recipes on how to configure / customize this component,<br>
                check out the
                <a href="https://getbootstrap.esdocu.com/docs/5.1/components/carousel/" target="_blank" rel="noopener">Carousel documentation</a>.
            </p>
        
        <h1><mark>[8.1] Carrusel de Solo Diapositivas</mark></h1> 
        <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel" data-bs-interval="2000">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="../assets/carousel-slide1.png" class="d-block w-100 img -fluid" alt="Vue logo">
                </div>
                <div class="carousel-item">
                    <img src="../assets/carousel-slide2.png" class="d-block w-100 img-fluid" alt="Vue logo">
                </div>
                <div class="carousel-item">
                    <img src="../assets/carousel-slide3.png" class="d-block w-100" alt="Vue logo">
                </div>
            </div>
        </div>       

        <h1><mark>[8.2] Carrusel con Controles</mark></h1> 
        <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="../assets/carousel-slide1.png" class="d-block w-100" alt="Vue logo">
                </div>
                <div class="carousel-item">
                    <img src="../assets/carousel-slide2.png" class="d-block w-100" alt="Vue logo">
                </div>
                <div class="carousel-item">
                    <img src="../assets/carousel-slide3.png" class="d-block w-100" alt="Vue logo">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Anterior</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Siguiente</span>
            </button>
        </div>

        <h1><mark>[8.3] Carrusel con Indicadores</mark></h1>
        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="../assets/carousel-slide1.png" class="d-block w-100" alt="Vue logo">
                </div>
                <div class="carousel-item">
                    <img src="../assets/carousel-slide2.png" class="d-block w-100" alt="Vue logo">
                </div>
                <div class="carousel-item">
                    <img src="../assets/carousel-slide3.png" class="d-block w-100" alt="Vue logo">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Anterior</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Siguiente</span>
            </button>
        </div> 

        <h1><mark>[8.4] Carrusel con Subtítulos</mark></h1>
        <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="../assets/carousel-slide1.png" class="d-block w-100" alt="Vue logo">
                    <div class="carousel-caption d-none d-md-block">
                        <h5>Etiqueta de la primera diapositiva</h5>
                        <p>Algún contenido placeholder representativo para la primera diapositiva.</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="../assets/carousel-slide2.png" class="d-block w-100" alt="Vue logo">
                    <div class="carousel-caption d-none d-md-block">
                        <h5>Etiqueta de la segunda diapositiva</h5>
                        <p>Algún contenido placeholder representativo para la segunda diapositiva.</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="../assets/carousel-slide3.png" class="d-block w-100" alt="Vue logo">
                    <div class="carousel-caption d-none d-md-block">
                        <h5>Etiqueta de la tercera diapositiva</h5>
                        <p>Algún contenido placeholder representativo para la tercera diapositiva.</p>
                    </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Anterior</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Siguiente</span>
            </button>
        </div>

        <h1><mark>[8.5] Carrusel con Transición de Fundido</mark></h1>
        <div id="carouselExampleFade" class="carousel slide carousel-fade" data-bs-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="../assets/carousel-slide1.png" class="d-block w-100" alt="Vue logo">
                </div>
                <div class="carousel-item">
                    <img src="../assets/carousel-slide2.png" class="d-block w-100" alt="Vue logo">
                </div>
                <div class="carousel-item">
                    <img src="../assets/carousel-slide3.png" class="d-block w-100" alt="Vue logo">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Anterior</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Siguiente</span>
            </button>
        </div>

        <h1><mark>[8.6] Carrusel con Intervalos Individualizados</mark></h1>
        <div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active" data-bs-interval="10000">
                    <img src="../assets/carousel-slide1.png" class="d-block w-100" alt="Vue logo">
                </div>
                <div class="carousel-item" data-bs-interval="2000">
                    <img src="../assets/carousel-slide2.png" class="d-block w-100" alt="Vue logo">
                </div>
                <div class="carousel-item">
                    <img src="../assets/carousel-slide3.png" class="d-block w-100" alt="Vue logo">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Anterior</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Siguiente</span>
            </button>
        </div>

        <h1><mark>[8.7] Carrusel con Deslizamiento Táctil Desactivado</mark></h1>
        <div id="carouselExampleControlsNoTouching" class="carousel slide" data-bs-touch="false" data-bs-interval="false">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="../assets/carousel-slide1.png" class="d-block w-100" alt="Vue logo">
                </div>
                <div class="carousel-item">
                    <img src="../assets/carousel-slide2.png" class="d-block w-100" alt="Vue logo">
                </div>
                <div class="carousel-item">
                    <img src="../assets/carousel-slide3.png" class="d-block w-100" alt="Vue logo">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Anterior</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Siguiente</span>
            </button>
        </div>

        <h1><mark>[8.8] Carrusel en Modo Oscuro</mark></h1>
        <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active" data-bs-interval="10000">
                    <img src="../assets/carousel-slide1.png" class="d-block w-100" alt="...">
                    <div class="carousel-caption d-none d-md-block">
                        <h5>Etiqueta de la primera diapositiva</h5>
                        <p>Algún contenido placeholder representativo para la primera diapositiva.</p>
                    </div>
                </div>
                <div class="carousel-item" data-bs-interval="2000">
                    <img src="../assets/carousel-slide2.png" class="d-block w-100" alt="...">
                    <div class="carousel-caption d-none d-md-block">
                        <h5>Etiqueta de la segunda diapositiva</h5>
                        <p>Algún contenido placeholder representativo para la segunda diapositiva.</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="../assets/carousel-slide3.png" class="d-block w-100" alt="...">
                    <div class="carousel-caption d-none d-md-block">
                        <h5>Etiqueta de la tercera diapositiva</h5>
                        <p>Algún contenido placeholder representativo para la tercera diapositiva.</p>
                    </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Anterior</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Siguiente</span>
            </button>
        </div>

    </div>
</template>

<script>
export default {
  name: 'CarouselBoot',
  props: {
    msg: String
  },
  methods: {
    /*
    var myCarousel = document.querySelector('#myCarousel')
       new Bootstrap.Carousel(myCarousel)
    */
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