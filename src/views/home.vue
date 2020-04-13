<template>
    <div class="app">
        <v-toolbar>
            <div class="log">LISTENNAR</div>
            <v-spacer></v-spacer>
            <v-btn id="menu" text small>support</v-btn>
            <span>
            <v-treeview id="menu"  :items="items"></v-treeview>
            </span>
        </v-toolbar>
        <div class="main">
            <div class="title">LISTENNAR playlist Box</div>
            <div>
                <button class="btn"></button>
            </div>
            <div class="dom">Welcome to our platfrom together we can bluid stong connection, mentally and physically</div>
            <div><button  class="go">Go now</button></div>
        </div>
    </div>
</template>
<style scoped>
.dom{
    font-size: 17px;
    margin-top: 20px;
}
.go{
    background:#736CDC;
    color: white;
    width: 350px;
    height: 80px;
    font-size: 30px;
    margin-top:50px;
    border-radius: 10px;
    box-shadow: 6px 6px #736CDC;
    border: none;
    outline: none;
}
.btn{
    background:#736CDC;
    border: none;
    outline: none;
    height: 70px;
    width: 100px;
    border-radius:100px;
    clip-path: polygon(100% 0, 0 0, 50% 100%);
    margin-top:50px;
}
.title{
    font-size: 40px;
    font-weight: bold;
    padding-top: 100px;
}
.main{
    background: white;
    width: 900px;
    height: 550px;
    border:   1px #ddd solid;
    margin:20px 0px 0px 140px;
    border-radius: 14px;
    text-align: center;
    /* box-shadow: 0px 14px black; */
    /* justify-content: center;
    display: flex;
    align-items: center; */
}
#menu{
    color: #736CDC;
    font-size: 15px;
}

.app{
    background: #F5F5F5;
    color: #736CDC;
    height: 660px;
    width: 100%;
}
.log{
    font-size: 40px;
    font-weight:bold;
    color: #736CDC;
    margin-left: 100px;
}
</style>
<script>
export default {
  data: () => ({
    items: [
      {
        id: 1,
        name: 'English',
        children: [
          { id: 2, name: 'English' },
          { id: 3, name: 'frech' }
        ]
      }
    ]
  })
}
</script>
