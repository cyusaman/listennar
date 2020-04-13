<template>
    <v-footer class="footer">
      <div class="ff">
          <div class="ff-f">
          <div>Miraculous Template</div>
           <div>
          Lorem ipsun dolr sit amet, consectetur
          adipisicing elit,sed do eiusmod tempor
          incididunt ut labore et dolore magna
          aliqua. Ut enim ad minim veniam,queue_music
          nostrud exercitation ullamco laboris nisi
          ut aliquip ex ea commondo consequat
          duis aute irure dolor.
        </div>
          </div>
      </div>
      <div class="ff">
          <div class="ff-s">
       <div>Download Our App</div>
        <div>
          Go Mobile with our app.
          Listen to your favourite songs at just one
          click. Download Now !
        </div>
          </div>

      </div>
      <div class="ff">
          <div class=" ff-t">
        <div>Subscribe</div>
        <div>Subscribe to our newsletter and get latest updates and offers</div>
           <div>
      <div><input type="text" placeholder="Enter Your Name"></div>
       <div><input type="text" placeholder="Enter Your Email"></div>
        <div><button>Sign Me Up</button></div>
      </div>
          </div>

      </div>
      <div class="ff ">
          <div class="ff-o">
       <div>Contact Us</div>
        <div class="widt">
          <span class="left"><button> <v-icon dark id="c-icon">call</v-icon></button></span>
          <div class="right">
          <div> call us:</div>
          <div>+2507034879809</div>
          </div>
        </div>
          <div class="widt">
          <span class="left"><button><v-icon dark id="c-icon">mail_outline</v-icon></button></span>
          <div class="rigth">
          <div>Email us:</div>
          <div>demo@gmail.com</div>
          </div>

        </div>
            <div class="widt">
          <span class="left"><button><v-icon dark id="c-icon">location_on</v-icon></button></span>
          <div class="rigth">
          <div>Walk in:</div>
          <div>Makuza peace plaza</div>
          </div>

        </div>
        <div> <span> Follow us:</span> <span><button><v-icon dark>face</v-icon></button></span><span><button><v-icon>linkedin</v-icon></button></span><span><button></button></span><span><button></button></span></div>
          </div>
    </div>
    </v-footer>
</template>
<style scoped>
.footer{
    background: url(../assets/vvv.jpg);
    background-size:cover;
}
.ff{
    color: white;
    display: inline-flex;
    width: 300px;
}
.ff-f{
    width: 80%;
    margin-left: 50px;
}
.ff-s{
    width: 70%;
     margin-left: 100px;
}
.ff-t{
    width: 70%;
       margin-left: 100px;
}
.ff-o{
        width: 70%;
       margin-left: 120px;
}
.ff-t input{
    background: white;
    color: black;
    width: 250px;
    margin-top: 15px;
    border-radius:3px;
    outline: none;
    height: 30px;
}
.ff-t button{
     background:#3BC8E6;
  border-radius:25px;
  padding: 7px 20px 7px 20px;
  margin-top: 13px;
  outline: none;
}
.left{
    float:left;
    width: 20%;
}
.right{
    float: right;
    width: 80%;
}
.left button{
    background:#3BC8E6;
    padding: 3px;
    border-radius: 3px;
    margin-top: 5px;
}
#c-icon{
    font-size: 18px;
}
.widt{
    margin-top: 20px;
    height: 20px;
}
</style>
