<template>
    <div class="nameweb">
        <br>
        <br>
        <h1>One Mile At A Time</h1>
        <div>
        <table class="piks">
            <th><img src="@/assets/boracs.jpg" width="400" height="300" /></th>
            <th><img src="@/assets/pals.jpg" width="400" height="300" /></th>
        </table>
        <br>
        <router-link to="/TouristDestination">Start the tour</router-link>
        </div>
    </div>
</template>
<style>
.nameweb {
   text-align:center; 
   font-family: 'Courier New', Courier, monospace;
    
}
.piks {
  margin-left: auto;
  margin-right: auto;
    
}
html, body {
    height: 100%;
    margin: 0;
    padding: 0;
    background-image: url('~@/assets/brown.jpg');
    height: 100%; 
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    overflow: auto;
}

</style>