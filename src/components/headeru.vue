<template>
     <div class="header">
     <v-toolbar id="header-top" height="50px" dark>
      <div>
        <button class="log">M</button> <span class="s-inp"><input  type="text"><button class="s-btn"><v-icon small>search</v-icon></button> </span><span class="ttitle">Trending Songs: </span>
        <span>Dream your moments, Until I Met You, Gimme Some Courge, Dark Alley(+8 More)</span>  <span class="llan" >Languages <span class="ntub">|</span> </span>
        <span id="a-btn"> <router-link to="/upload"><button id="reg">Upload</button></router-link></span> <span class="name"><span class="ntub">|</span><span class="n-re">Hello Bella</span> <router-link to="/edit-profile"><button class="bs">Bs</button></router-link></span>
        </div>
  </v-toolbar>
  <router-view/>
  </div>
</template>
<style scoped>
.bs{
    background: #3BC8E6;
    margin-left:10px;
    width: 30px;
    height: 30px;
    border-radius: 100%;
    outline: none;
}
button{
    color: white;
}
.llan{
    margin: 35px;
}
.name{
    margin-left: 10px;
}
.n-re{
    margin-left:5px;
}
</style>
