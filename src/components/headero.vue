<template>
    <div class="header">
     <v-toolbar id="header-top" height="50px" dark>
      <div>
               <button class="log">M</button> <span class="s-inp"><input  type="text"><button class="s-btn"><v-icon small>search</v-icon></button> </span><span class="ttitle">Trending Songs: </span>
        <span>Dream your moments, Until I Met You, Gimme Some Courge, Dark Alley(+8 More)</span>  <span class="llan" >Languages <span class="ntub">|</span> </span>
        <span id="a-btn"><button id="reg" @click.native="reg=!reg">Register</button><button  id="login">Login</button></span>
        </div>
  </v-toolbar>
  </div>
</template>
<style>
.header{
  z-index: 999;
  font-family: "Helvetica Neue", Roboto, "Segoe UI", Calibri, sans-serif;
}

</style>
