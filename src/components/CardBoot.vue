<template>
    <div class="container">
        <div class="card">
            <img alt="VueBoot logo" src="../assets/vueplusboot.png" />
        </div>
        <h1 style="color: purple"><strong>{{ msg }}</strong></h1>
        <img alt="Vue logo" src="../assets/card.png" />
            <p>
                For a guide and recipes on how to configure / customize this component,<br>
                check out the
                <a href="https://getbootstrap.esdocu.com/docs/5.1/components/card/" target="_blank" rel="noopener">Cards documentation</a>.
            </p>
        
        <h1><mark>[7.1] Tarjeta Básica</mark></h1>        
        <div class="card" style="width: 18rem;">            
            <img src="../assets/card-photo.png" class="card-img-top" alt="Vue logo">
            <div class="card-body">
                <h5 class="card-title">Título de la tarjeta</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocar cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
                <a href="#" class="btn btn-primary">Ir a algún lugar</a>
            </div>
        </div>        
        
        <h1><mark>[7.2] Tarjeta con Cuerpo</mark></h1>
        <div class="card">
            <div class="card-body">
                Este es un texto dentro del cuerpo de una tarjeta.
            </div>
        </div>

        <h1><mark>[7.3] Tarjeta con Títulos, Textos y Enlaces</mark></h1>
        <div class="card" style="width: 18rem;">
            <div class="card-body">
                <h5 class="card-title">Título de la tarjeta</h5>
                <h6 class="card-subtitle mb-2 text-muted">Subtítulo de la tarjeta</h6>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
                <a href="#" class="card-link">Enlace de tarjeta</a>
                <a href="#" class="card-link">Otro enlace</a>
            </div>
        </div>

        <h1><mark>[7.4] Tarjeta con Imagen</mark></h1>
        <div class="card" style="width: 18rem;">
            <img src="../assets/card-layer.png" class="card-img-top" alt="Vue logo">
            <div class="card-body">
                <p class="card-text">Un texto de ejemplo rápido para colocar cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>

        <h1><mark>[7.5] Tarjetas con Grupos de Listas</mark></h1>
        <h3>Ejemplo 1</h3>
        <div class="card" style="width: 18rem;">
            <ul class="list-group list-group-flush">
                <li class="list-group-item">Un elemento</li>
                <li class="list-group-item">Un segundo elemento</li>
                <li class="list-group-item">Un tercer elemento</li>
            </ul>
        </div>
        <h3>Ejemplo 2</h3>
        <div class="card" style="width: 18rem;">
            <div class="card-header">
                Destacado
            </div>
            <ul class="list-group list-group-flush">
                <li class="list-group-item">Un elemento</li>
                <li class="list-group-item">Un segundo elemento</li>
                <li class="list-group-item">Un tercer elemento</li>
            </ul>
        </div>        
        <h3>Ejemplo 3</h3>
        <div class="card" style="width: 18rem;">
            <ul class="list-group list-group-flush">
                <li class="list-group-item">Un elemento</li>
                <li class="list-group-item">Un segundo elemento</li>
                <li class="list-group-item">Un tercer elemento</li>
            </ul>
            <div class="card-footer">
                Pie de tarjeta
            </div>
        </div>

        <h1><mark>[7.6] Tarjeta con Contenido Mixto</mark></h1>
        <div class="card" style="width: 18rem;">
            <img src="../assets/card-layer.png" class="card-img-top" alt="Vue logo">
            <div class="card-body">
                <h5 class="card-title">Título de la tarjeta</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocar cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
            <ul class="list-group list-group-flush">
                <li class="list-group-item">Un elemento</li>
                <li class="list-group-item">Un segundo elemento</li>
                <li class="list-group-item">Un tercer elemento</li>
            </ul>
            <div class="card-body">
                <a href="#" class="card-link">Enlace de tarjeta</a>
                <a href="#" class="card-link">Otro enlace</a>
            </div>
        </div>

        <h1><mark>[7.7] Tarjeta con Encabezado y Pié de Página</mark></h1>
        <h3>Ejemplo 1</h3>
        <div class="card">
            <div class="card-header">
                Destacado
            </div>
            <div class="card-body">
                <h5 class="card-title">Tratamiento especial del título</h5>
                <p class="card-text">Con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                <a href="#" class="btn btn-primary">Ir a algún lugar</a>
            </div>
        </div>
        <h3>Ejemplo 2</h3>
        <div class="card">
            <h5 class="card-header">Destacado</h5>
            <div class="card-body">
                <h5 class="card-title">Tratamiento especial del título</h5>
                <p class="card-text">Con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                <a href="#" class="btn btn-primary">Ir a algún lugar</a>
            </div>
        </div>
        <h3>Ejemplo 3</h3>
        <div class="card">
            <div class="card-header">
                Cita
            </div>
            <div class="card-body">
                <blockquote class="blockquote mb-0">
                <p>Una cita conocida, contenida en un elemento blockquote.</p>
                <footer class="blockquote-footer">Alguien famoso en <cite title="Título de la fuente">Título de la fuente</cite></footer>
                </blockquote>
            </div>
        </div>
        <h3>Ejemplo 4</h3>
        <div class="card text-center">
            <div class="card-header">
                Destacado
            </div>
            <div class="card-body">
                <h5 class="card-title">Tratamiento especial del título</h5>
                <p class="card-text">Con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                <a href="#" class="btn btn-primary">Ir a algún lugar</a>
            </div>
            <div class="card-footer text-muted">
                Hace 2 días
            </div>
        </div>

        <h1><mark>[7.8] Dimensionamiento</mark></h1>
        <h3>Ejemplo 1. Usando marcado de cuadrícula</h3>
        <div class="row">
            <div class="col-sm-6">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Tratamiento especial del título</h5>
                        <p class="card-text">Con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                        <a href="#" class="btn btn-primary">Ir a algún lugar</a>
                    </div>
                </div>
            </div>
            <div class="col-sm-6">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Tratamiento especial del título</h5>
                        <p class="card-text">Con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                        <a href="#" class="btn btn-primary">Ir a algún lugar</a>
                    </div>
                </div>
            </div>
        </div>
        <h3>Ejemplo 2. Usando utilidades de tamaño disponibles</h3>
        <div class="card w-75">
            <div class="card-body">
                <h5 class="card-title">Título de la tarjeta</h5>
                <p class="card-text">Con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                <a href="#" class="btn btn-primary">Botón</a>
            </div>
        </div>
        <div class="card w-50">
            <div class="card-body">
                <h5 class="card-title">Título de la tarjeta</h5>
                <p class="card-text">Con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                <a href="#" class="btn btn-primary">Botón</a>
            </div>
        </div>
        <h3>Ejemplo 3. Usando CSS personalizado</h3>
        <div class="card" style="width: 18rem;">
            <div class="card-body">
                <h5 class="card-title">Tratamiento especial del título</h5>
                <p class="card-text">Con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                <a href="#" class="btn btn-primary">Ir a algún lugar</a>
            </div>
        </div>

        <h1><mark>[7.9] Alineación de Texto</mark></h1>
        <div class="card" style="width: 18rem;">
            <div class="card-body">
                <h5 class="card-title">Tratamiento especial del título</h5>
                <p class="card-text">Con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                <a href="#" class="btn btn-primary">Ir a algún lugar</a>
            </div>
        </div>
        <div class="card text-center" style="width: 18rem;">
            <div class="card-body">
                <h5 class="card-title">Tratamiento especial del título</h5>
                <p class="card-text">Con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                <a href="#" class="btn btn-primary">Ir a algún lugar</a>
            </div>
        </div>
        <div class="card text-end" style="width: 18rem;">
            <div class="card-body">
                <h5 class="card-title">Tratamiento especial del título</h5>
                <p class="card-text">Con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                <a href="#" class="btn btn-primary">Ir a algún lugar</a>
            </div>
        </div>

        <h1><mark>[7.10] Navegación</mark></h1>
        <h3>Ejemplo 1</h3>
        <div class="card text-center">
            <div class="card-header">
                <ul class="nav nav-tabs card-header-tabs">
                <li class="nav-item">
                    <a class="nav-link active" aria-current="true" href="#">Activo</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Enlace</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled">Deshabilitado</a>
                </li>
                </ul>
            </div>
            <div class="card-body">
                <h5 class="card-title">Tratamiento especial del título</h5>
                <p class="card-text">Con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                <a href="#" class="btn btn-primary">Ir a algún lugar</a>
            </div>
        </div>
        <h3>Ejemplo 2</h3>
        <div class="card text-center">
            <div class="card-header">
                <ul class="nav nav-pills card-header-pills">
                <li class="nav-item">
                    <a class="nav-link active" href="#">Activo</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Enlace</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled">Deshabilitado</a>
                </li>
                </ul>
            </div>
            <div class="card-body">
                <h5 class="card-title">Tratamiento especial del título</h5>
                <p class="card-text">Con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                <a href="#" class="btn btn-primary">Ir a algún lugar</a>
            </div>
        </div>

        <h1><mark>[7.11] Imágenes</mark></h1>
        <h3>Ejemplo 1. Capas de imágenes</h3>
        <div class="card mb-3">
            <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
            <div class="card-body">
                <h5 class="card-title">Título de la tarjeta</h5>
                <p class="card-text">Esta es una tarjeta más amplia con texto de apoyo a continuación como introducción natural a contenido adicional. Este contenido es un poco más largo.</p>
                <p class="card-text"><small class="text-muted">Última actualización hace 3 minutos</small></p>
            </div>
        </div>
        <div class="card">
            <div class="card-body">
                <h5 class="card-title">Título de la tarjeta</h5>
                <p class="card-text">Esta es una tarjeta más amplia con texto de apoyo a continuación como introducción natural a contenido adicional. Este contenido es un poco más largo.</p>
                <p class="card-text"><small class="text-muted">Última actualización hace 3 minutos</small></p>
            </div>
            <img src="../assets/card-layer2.png" class="card-img-bottom" alt="Vue logo">
        </div>
        <h3>Ejemplo 2. Superposición de imágenes</h3>
        <div class="card bg-dark text-white">
            <img src="../assets/card-layer5.png" class="card-img" alt="Vue logo">
            <div class="card-img-overlay">
                <h5 class="card-title">Título de la tarjeta</h5>
                <p class="card-text">Esta es una tarjeta más amplia con texto de apoyo a continuación como introducción natural a contenido adicional. Este contenido es un poco más largo.</p>
                <p class="card-text">Última actualización hace 3 minutos</p>
            </div>
        </div>

        <h1><mark>[7.12] Tarjeta Horizontal</mark></h1>
        <div class="card mb-3" style="max-width: 540px;">
            <div class="row g-0">
                <div class="col-md-4">
                    <img src="../assets/card-layer.png" class="img-fluid rounded-start" alt="Vue logo">>
                </div>
                <div class="col-md-8">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta es una tarjeta más amplia con texto de apoyo a continuación como introducción natural a contenido adicional. Este contenido es un poco más largo.</p>
                        <p class="card-text"><small class="text-muted">Última actualización hace 3 minutos</small></p>
                    </div>
                </div>
            </div>
        </div>

        <h1><mark>[7.13] Estilos de Tarjeta</mark></h1>
        <h3>Ejemplo 1. Fondo y color</h3>
        <div class="card text-white bg-primary mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body">
                <h5 class="card-title">Título de tarjeta Primary</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>
        <div class="card text-white bg-secondary mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body">
                <h5 class="card-title">Título de tarjeta Secondary</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
             </div>
        </div>
        <div class="card text-white bg-success mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body">
                <h5 class="card-title">Título de tarjeta Success</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>
        <div class="card text-white bg-danger mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body">
                <h5 class="card-title">Título de tarjeta Danger</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>
        <div class="card text-dark bg-warning mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body">
                <h5 class="card-title">Título de tarjeta Warning</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>
        <div class="card text-dark bg-info mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body">
                <h5 class="card-title">Título de tarjeta Info</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>
        <div class="card text-dark bg-light mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body">
                <h5 class="card-title">Título de tarjeta Light</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>
        <div class="card text-white bg-dark mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body">
                <h5 class="card-title">Título de tarjeta Dark</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>
        <h3>Ejemplo 2. Borde</h3>
        <div class="card border-primary mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body text-primary">
                <h5 class="card-title">Título de la tarjeta Primary</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>
        <div class="card border-secondary mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body text-secondary">
                <h5 class="card-title">Título de la tarjeta Secondary</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>
        <div class="card border-success mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body text-success">
                <h5 class="card-title">Título de la tarjeta Success</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>
        <div class="card border-danger mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body text-danger">
                <h5 class="card-title">Título de la tarjeta Danger</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>
        <div class="card border-warning mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body">
                <h5 class="card-title">Título de la tarjeta Warning</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>
        <div class="card border-info mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body">
                <h5 class="card-title">Título de la tarjeta Info</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>
        <div class="card border-light mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body">
                <h5 class="card-title">Título de la tarjeta Light</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>
        <div class="card border-dark mb-3" style="max-width: 18rem;">
            <div class="card-header">Encabezado</div>
            <div class="card-body text-dark">
                <h5 class="card-title">Título de la tarjeta Dark</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
        </div>
        <h3>Ejemplo 3. Utilidades mixins</h3>
        <div class="card border-success mb-3" style="max-width: 18rem;">
            <div class="card-header bg-transparent border-success">Encabezado</div>
            <div class="card-body text-success">
                <h5 class="card-title">Título de tarjeta Success</h5>
                <p class="card-text">Un texto de ejemplo rápido para colocal cerca del título de la tarjeta y componer la mayor parte del contenido de la tarjeta.</p>
            </div>
            <div class="card-footer bg-transparent border-success">Pie de tarjeta</div>
        </div>
        
        <h1><mark>[7.14] Layout de Tarjeta</mark></h1>  
        <h3>Ejemplo 1. Grupos de tarjetas 1</h3>  
        <div class="card-group">
            <div class="card">
                <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                <div class="card-body">
                    <h5 class="card-title">Título de la tarjeta</h5>
                    <p class="card-text">Esta es una tarjeta más amplia con texto de apoyo a continuación como introducción natural a contenido adicional. Este contenido es un poco más largo.</p>
                    <p class="card-text"><small class="text-muted">Última actualización hace 3 minutos</small></p>
                </div>
            </div>
            <div class="card">
                <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                <div class="card-body">
                    <h5 class="card-title">Título de la tarjeta</h5>
                    <p class="card-text">Esta tarjeta tiene texto de apoyo a continuación como una introducción natural a contenido adicional.</p>
                    <p class="card-text"><small class="text-muted">Última actualización hace 3 minutos</small></p>
                </div>
            </div>
            <div class="card">
                <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                <div class="card-body">
                    <h5 class="card-title">Título de la tarjeta</h5>
                    <p class="card-text">Esta es una tarjeta más amplia con texto de apoyo a continuación como introducción natural a contenido adicional. Esta tarjeta tiene un contenido aún más largo que la primera para mostrar esa acción de igual altura.</p>
                    <p class="card-text"><small class="text-muted">Última actualización hace 3 minutos</small></p>
                </div>
            </div>
        </div>
        <h3>Ejemplo 2. Grupos de tarjetas 2</h3> 
        <div class="card-group">
            <div class="card">
                <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                <div class="card-body">
                    <h5 class="card-title">Título de la tarjeta</h5>
                    <p class="card-text">Esta es una tarjeta más amplia con texto de apoyo a continuación como introducción natural a contenido adicional. Este contenido es un poco más largo.</p>
                </div>
                <div class="card-footer">
                    <small class="text-muted">Última actualización hace 3 minutos</small>
                </div>
            </div>
            <div class="card">
                <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                <div class="card-body">
                    <h5 class="card-title">Título de la tarjeta</h5>
                    <p class="card-text">Esta tarjeta tiene texto de apoyo a continuación como una introducción natural a contenido adicional.</p>
                </div>
                <div class="card-footer">
                    <small class="text-muted">Última actualización hace 3 minutos</small>
                </div>
            </div>
            <div class="card">
                <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                <div class="card-body">
                    <h5 class="card-title">Título de la tarjeta</h5>
                    <p class="card-text">Esta es una tarjeta más amplia con texto de apoyo a continuación como introducción natural a contenido adicional. Esta tarjeta tiene un contenido aún más largo que la primera para mostrar esa acción de igual altura.</p>
                </div>
                <div class="card-footer">
                    <small class="text-muted">Última actualización hace 3 minutos</small>
                </div>
            </div>
        </div>
        <h3>Ejemplo 3. Tarjetas de cuadrícula 1</h3> 
        <div class="row row-cols-1 row-cols-md-2 g-4">
            <div class="col">
                <div class="card">
                    <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta es una tarjeta más larga con texto de apoyo a continuación como introducción natural a contenido adicional. Este contenido es un poco más largo.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta es una tarjeta más larga con texto de apoyo a continuación como introducción natural a contenido adicional. Este contenido es un poco más largo.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta es una tarjeta más larga con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta es una tarjeta más larga con texto de apoyo a continuación como introducción natural a contenido adicional. Este contenido es un poco más largo.</p>
                    </div>
                </div>
            </div>
        </div>
        <h3>Ejemplo 4. Tarjetas de cuadrícula 2</h3> 
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <div class="col">
                <div class="card">
                    <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta es una tarjeta más larga con texto de apoyo a continuación como introducción natural a contenido adicional. Este contenido es un poco más largo.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta es una tarjeta más larga con texto de apoyo a continuación como introducción natural a contenido adicional. Este contenido es un poco más largo.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta es una tarjeta más larga con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta es una tarjeta más larga con texto de apoyo a continuación como introducción natural a contenido adicional. Este contenido es un poco más largo.</p>
                    </div>
                </div>
            </div>
        </div>
        <h3>Ejemplo 5. Tarjetas de cuadrícula 3</h3>
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <div class="col">
                <div class="card h-100">
                    <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta es una tarjeta más larga con texto de apoyo a continuación como introducción natural a contenido adicional. Este contenido es un poco más largo.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card h-100">
                    <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta es una tarjeta corta.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card h-100">
                    <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta es una tarjeta más larga con texto de apoyo a continuación como introducción natural a contenido adicional.</p>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card h-100">
                    <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta es una tarjeta más larga con texto de apoyo a continuación como introducción natural a contenido adicional. Este contenido es un poco más largo.</p>
                    </div>
                </div>
            </div>
        </div>
        <h3>Ejemplo 6. Pies de página alineados</h3>
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <div class="col">
                <div class="card h-100">
                    <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta es una tarjeta más amplia con texto de apoyo a continuación como introducción natural a contenido adicional. Este contenido es un poco más largo.</p>
                    </div>
                    <div class="card-footer">
                        <small class="text-muted">Última actualización hace 3 minutos</small>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card h-100">
                    <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta tarjeta tiene texto de apoyo a continuación como una introducción natural a contenido adicional.</p>
                    </div>
                    <div class="card-footer">
                        <small class="text-muted">Última actualización hace 3 minutos</small>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card h-100">
                    <img src="../assets/card-layer2.png" class="card-img-top" alt="Vue logo">
                    <div class="card-body">
                        <h5 class="card-title">Título de la tarjeta</h5>
                        <p class="card-text">Esta es una tarjeta más amplia con texto de apoyo a continuación como introducción natural a contenido adicional. Esta tarjeta tiene un contenido aún más largo que la primera para mostrar esa acción de igual altura.</p>
                    </div>
                    <div class="card-footer">
                        <small class="text-muted">Última actualización hace 3 minutos</small>
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>


<script>
export default {
  name: 'CardBoot',
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