# BalochGithub
<!DOCTYPE html>
 <html lang="en">
 <head>
     <meta charset="UTF-8">
     <meta http-equiv="X-UA-Compatible" content="IE=edge">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Make with baloch</title>
     <link rel="stylesheet" href="style.css">
     
 </head>
 <body>
     <div class="banner">
         <div class="navbar">
             
             <ul>
                 <li><a href="#">Home</a></li>
                 <li><a href="#">Contact</a></li>
                 <li><a href="#">About</a></li>
             </ul>
         </div>
            <div class="content">
               <h1>WELCOME TO CS BATCH 2K21                                                                                                                                                                                                                                      </h1>
                 <p>Apply For Admission</p>
                   <div>
                  <button type="button"><span></span> Sign in</button>
                 <button type="button"><span></span> Sign up</button>

             </div>
         </div>
     </div>
 </body>
 </html>
 
 // Css Code
 
*{
     margin: 0;
     padding: 0;
     font-family:sans-serif ;
}
.banner{
    width: 100%;
    height: 100vh;
    background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(atqq.jpg);
    background-size: cover;
    background-position: center;
}
.navbar{
    width: 85%;
    margin: auto;
    padding: 35px 0;
    align-items: center;
    justify-content: space-between;
}
.navbar ul li{
    list-style:none;
    display: inline-block;
    margin: 0 20px;
    position: relative;
}
.navbar ul li a{
    text-decoration: none;
    color: #fff;
    text-transform: uppercase;

}
.navbar ul li::after{
    content: '';
    height: 3px;
    width: 0%;
    background: #009688;
    position: absolute;
    left: 0;
    bottom: -10px;
    transition: 0.5s;

}
.navbar ul li:hover::after{
    width: 100%;

}
.content{
    width: 100%;
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    text-align: center;
    color: #fff;

}
.content h1 {
    font-size: 50px;
    margin-top: 80px;
    
}
.content p{
    margin: 20px;
    font-weight: 100;
    line-height: 25px;

}
button{
    width: 200px;
    padding: 15px 0;
    text-align: center;
    margin: 20px 10px;
    font-weight: bold;
    border-radius: 25px;
    border: 2px solid #009688;
    background: transparent;
    color: #fff;
    cursor: pointer;
    position: relative;
    overflow: hidden;
}
span{
    background: #009688;
    height: 100%;
    width: 0%;
    border-radius: 25px;
    position: absolute;
    left: 0;
    bottom: 0;
    z-index: -1;
    transition: 0.5s;
}
button:hover span{
    width: 100%;

}
button:hover{
    border: none;
}
 
