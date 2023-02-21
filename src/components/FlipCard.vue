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
        
        <h1><mark>[7.1] Flip Cards para Catalógos I</mark></h1>
        <p><a href="https://bbbootstrap.com/snippets/bootstrap-5-flipping-cards-for-catalog-29291738" target="_blank" rel="noopener">Fuente: Bootstrap 5 Flipping cards for catalog</a></p>

        <div class="container d-flex align-items-center justify-content-center flex-wrap">
            <div class="box">
                <div class="body">
                    <div class="imgContainer">
                        <img src="https://images.pexels.com/photos/3601422/pexels-photo-3601422.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="">
                    </div>
                    <div class="content d-flex flex-column align-items-center justify-content-center">
                        <div>
                            <h3 class="text-white fs-5">Post Title</h3>
                            <p class="fs-6 text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo sed cum neque, rem provident ex. Laboriosam perspiciatis modi eveniet in?</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="box">
                <div class="body">
                    <div class="imgContainer">
                        <img src="https://images.pexels.com/photos/1532771/pexels-photo-1532771.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="">
                    </div>
                    <div class="content d-flex flex-column align-items-center justify-content-center">
                        <div>
                            <h3 class="text-white fs-5">Post Title</h3>
                            <p class="fs-6 text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo sed cum neque, rem provident ex. Laboriosam perspiciatis modi eveniet in?</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="box">
                <div class="body">
                    <div class="imgContainer">
                        <img src="https://images.pexels.com/photos/573238/pexels-photo-573238.jpeg?auto=compress&cs=tinysrgb&dpr=3&h=750&w=1260" alt="">
                    </div>
                    <div class="content d-flex flex-column align-items-center justify-content-center">
                        <div>
                            <h3 class="text-white fs-5">Post Title</h3>
                            <p class="fs-6 text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo sed cum neque, rem provident ex. Laboriosam perspiciatis modi eveniet in?</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'FlipCard',
  props: {
    msg: String
  },
  methods: {

  }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap');

/* Reseting */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body{
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
}

.container{
    transform-style: preserve-3d;
}

.container .box{
    position: relative;
    width: 300px;
    height: 300px;
    margin: 20px;
    transform-style: preserve-3d;
    perspective: 1000px;
    cursor: pointer;
}

.container .box .body{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    transform-style: preserve-3d;
    transition: 0.9s ease;
}  

.container .box .body .imgContainer{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    transform-style: preserve-3d;
}

.container .box .body .imgContainer img{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.container .box .body .content{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: #333;
    backface-visibility: hidden;
    transform-style: preserve-3d;
    transform: rotateY(180deg);
}

.container .box:hover .body{
    transform: rotateY(180deg);
}

.container .box .body .content div{
    transform-style: preserve-3d;
    padding: 20px;
    background: linear-gradient(45deg, #FE0061,#FFEB3B);
    transform: translateZ(100px);
}

.container .box .body .content div h3{
    letter-spacing: 1px;
}

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
