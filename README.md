# b7web
CSS
 <!DOCTYPE html>
   <html lang="pt-br">
   <head>
         <meta charset="UTF-8">
            <meta id="viewport" name="viewport" content="width=device-width, user-scalable=no">
            <title>MediCenter</title>
            <link rel="stylesheet" type="text/css" href="assets/css/style.css"/>

           
         
           
   
     

       </style>        
   </head>
   <body>
      <header>
         <div class="container">
            <div class="logo">
               <a href=""><img src="assets/img/logo.png"/>
            </div>
        </div>
        <div class="menu">
            <nav>
               <ul>

                  <li class="active"><a href="">HOME</a></li>
                  <li><a href="">HOME</a></li>
                  <li><a href="">HOME</a></li>
                  <li><a href="">HOME</a></li>
                  <li><a href="">HOME</a></li>
                  <li><a href="">HOME</a></li>
                 
               </ul>

            </nav>

        </div>
      </header>
         
         <section id="banner">
            <div class="container colum" ></div>
               <div class="banner_headliner">
                  <h1>Top notch experience</h1>
                  <h2> medicenter is a responsive template perfect for all screen sizes</h2>

            </div>
           
           
            <div class="banner_options">
               .....
            </div>
           
         </section>

         

         
   </body>  


</html>




body {
    margin: 0;
    padding: 0;

}
header{
    display: flex;
    justify-content: center;
    height: 120px;
}
.container{
    display: flex;
    justify-content: space-between;
    width: 990px;
 
}
.logo{

 display: flex;
 align-items: center;

}
.menu{
   
    display: flex;
    align-items: center;

}
nav ul,nav li {
    list-style: none;
    margin: 0;
    padding: 0;
    text-align: center;
   
}
nav ul {
    display: flex;
}
nav a {
    display: block;
    padding: 15px;
    text-decoration: none;
    text-transform: uppercase;
    color: #727272;
}
nav .active a,
nav a:hover {
   
   
background-color: #39aae1;
   
   
color: white;
}
#banner {
    display: flex;
    justify-content: center;
    background-image: url('../img/img1.jpg');
    background-position: center;
    background-size: cover;
    height: 670px;
}
.colum {
    flex-direction: column;
    float: left;
   
}
.banner_headliner {
 
    display: flex;
    flex-direction: column;
    justify-content: center;
   
}
.banner_headliner h1{
    color:#FFFFFF;
    font-size: 50px;
    text-shadow: 2px 2px 0px #000000;
   
   

}
.banner_options{
   

   
}
