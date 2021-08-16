<template>
  <div id="app-all">
    <header>
      <figure>
        <img alt="logo" src="./assets/logo.png">
      </figure>
      <h1>GAMES LOAD</h1>
      <nav class="navbar">
            <a>Inicio</a>
            <a>Productos</a>
            <a>Ordenes</a>
      </nav>

        <a class="btn">Iniciar sesión</a>
        <a class="btn1">Cerrar sesión</a>
    </header>
    <h1>hola</h1>
    <h1>hola</h1>
    <h1>hola</h1>
    <h1>hola</h1>
    <h1>hola</h1>
    <h1>hola</h1>
    <h1>hola</h1>
    <!--<Who/>-->
    <footer>
      <div class="all-footer">
        <figure>
            <img src="./assets/logo.png" alt="Logo">
        </figure>
        <div class="info">
          <ul>
            <li><a href="#">Contact us</a></li>
            <li><a href="#">About us</a></li>
            <li><a href="#">Direction</a></li>
          </ul>
        </div>
          <div class="socilamedia">
          <ul class="smedia">
            <li>Follow us</li>
            <li><i class="fab fa-facebook-square"></i></li>
            <li><i class="fab fa-youtube-square"></i></li>
            <li><i class="fab fa-instagram-square"></i></li>
          </ul>
          </div>
      </div>
    </footer>
    
  </div>
</template>

<script>

/*import Who from './components/Who.vue'

export default {
  name: 'App',
  components: {
    Who
  }
}*/
</script>

<style>
:root
{--primary-color: #0D0D0D;--palette-pink: #EE05F2 ;--heavy-blue: #0378A6; --medium-blue: #04ADBF;--light-blue: #04D9C4;	--secundary-color: #fff;--font-roboto: 'roboto';--layout: 1fr 1fr 1fr; --size: 18px;}
*
{margin: 0;padding: 0;border: 0;font-size: 100%; background: var(--primary-color);color: var(--secundary-color);}

#app-all
{text-align: center; font:300 20px/1.7 var(--font-roboto);}

header 
{ width: 100%; display:flex; align-items: center; position: fixed; z-index: 1000; height: 70px; padding: 15px 0%;border-bottom: 3px solid var(--medium-blue); font: 20px var(--font-roboto);}

header img
{margin: 0 20px; height: 40px; vertical-align: bottom;}

h1
{font-size: 30px;}

header img:hover, h1:hover
{transform: translateY(-5px);}
nav 
{ height: 63px; display: flex; align-items:center; margin-left: auto; margin-right: 20px;}

nav button 
{ padding: 0 20px; text-decoration: none; text-transform: uppercase; font-weight: 600; cursor: pointer;}

nav a 
{ padding: 0 20px;text-transform: uppercase; font-size: var(--size);font-weight: 600; border-color: none; cursor: pointer;}

nav a:hover
{background: var(--light-blue);padding: 10px;transition: 0.5s;}

.btn 
{ display: inline-table; text-decoration: none; font-weight: 600; padding: 5px 20px; background:var(--medium-blue); border-radius: 25px; position: unset; margin-right: 20px; float: right;text-transform: uppercase;font-size: var(--size);}

.btn:hover 
{ background:var(--palette-pink); cursor: pointer;}

.btn1 
{ display: inline-table; text-decoration: none; font-weight: 600; padding: 5px 20px; background: var(--medium-blue); border-radius: 25px; position: unset; margin-right: 20px; float: right;text-transform: uppercase;font-size: var(--size);}

.btn1:hover 
{ background: var(--palette-pink); cursor: pointer;}

footer 
{ border-top:5px solid var(--medium-blue); color:var(--secundary-color); width: 100%; position: fixed; padding: 20px 0;}

.all-footer
{margin: 0 auto;grid-gap: 40px; display: grid; grid-template-columns: var(--layout); align-items: center;}

footer img
{ height: 80px; margin: 0 20px; vertical-align: bottom;}

footer ul 
{display: inline-table; list-style: none; text-transform: uppercase;font-weight: 500;}

.info a
{text-decoration: none;}

footer .socilamedia ul
{ color: var(--secundary-color); display: flex; list-style: none;}
.socilamedia ul li
{padding: 0 20px; font-size: var(--size); text-transform: uppercase;font-weight: 500;}
.socilamedia ul li i
{font-size: 30px; cursor: pointer;}
</style>
