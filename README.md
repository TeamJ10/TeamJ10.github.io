# TeamJ10.github.io
aku belajar
<header>
 <div class="container">
  <div class="head">
<!-- nanti ini logonya di ganti yang saya kirim di discord -->
   <img class="logo" src="https://prog-8.com/images/html/advanced/main_logo.png">
  </div>
  <div class="head-right">
  <a class="login" href="#">Log in</a>
  </div>
 </div>
</header>
   
<!-- CSS Header -->
header{
  height:65px;
  width:100%;  
  background-color:rgba(34, 49, 52, 0.9);
  position:fixed;
  top:0;
  z-index:10;
}
.head{
  float:left;
}
.logo{
  width:124px;
  margin-top:20px;
  
}
.head-right{
  float:right;
  background-color:rgba(255,255,255,0.3);
  transition:all 0.5s;
}
.head-right:hover{
  background-color:rgba(255,255,255,0.3);
}
.head-right a{
  line-height:65px;
  padding:0 25px;
  color:white;
  display:block;
}
.container{
  width:1170px;
  padding:0 15px;
  margin:0 auto;
  color:white;
}
