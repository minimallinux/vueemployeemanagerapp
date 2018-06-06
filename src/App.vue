<template>
  <div id="app">
    <Navbar />
   <div class="tm-container uk-container">
    <router-view/>
    </div> 
  </div>
</template>

<script>
import Navbar from './components/Navbar'
export default {
  name: 'App',
  components: {
    Navbar
  }
}
</script>
<style>
.tm-navbar {
    padding: 15px 0;
    border: none;
    background: #01579B;
    text-transform: uppercase;
    height: 40px;
    margin-top: 0;
    text-shadow: none;
}
.uk-navbar.uk-navbar-container {
background: #01579B;
}
.uk-logo {
color: aliceblue;  
}
.uk-logo:active,
.uk-logo:focus,
.uk-logo:hover {
color:aliceblue;
}
.tm-container {
padding-top: 30px;
}
.float{
	position:fixed;
	width:60px;
	height:60px;
	bottom:40px;
	right:40px;
	background-color:aqua;
	color:#FFF;
	border-radius:50px;
	text-align:center;
	box-shadow: 2px 2px 3px #999;
}

.btn-float{
	margin-top:22px;
}
</style>


