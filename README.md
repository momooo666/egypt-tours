# egypt-tours
<!DOCTYPE html>
<html>
    <head>
        <!-- title of web page-->
        <title>EGY TOURS</title>
        <!--description and keywords of page-->
        <meta charset="UTF-8"/>
        <meta name="description" content="travel to egypt discover anncient egypt and enjoy the sea trips and safari in desert"/>
        <meta name="keywords" content="travel, egypt tours, luxor, pyramids, hurghada, sharm elshik, safari, desert"/>
        <meta name="robots" content="nofollow"/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <meta name="author" content="mohamed saad"/>
        <meta http-equiv="pragma" content="no-cache"/>
        <!--links of stylesheet and frameworks external-->
        <link rel="stylesheet" href="css-stylesheet/styleesheet.css" type="text/css"/>
        <!--stylesheet internal-->
        <style type="text/css">
        @font-face{
    src: url("../fonts/Sen/Sen-Bold.ttf");
    font-family: "mom";
    font-weight: 600;
}
@font-face{
    src: url("../fonts/Sen/Sen-ExtraBold.ttf");
    font-family: "mom";
    font-weight: 900;
}
@font-face{
    src: url("../fonts/Sen/Sen-Regular.ttf");
    font-family: "mom";
    font-weight: 200;
}
body{
    font-size: 16px;
    font-family:"mom", sans-serif;
    font-weight: 200;
    text-align: center;
    margin: 0px;
    
}
/*  header display flex*/
header{
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: space-between;
}
/* nav bar style*/
#nav{
    width:80%;
    max-width: 700px;
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-content: center;
    margin: 10px;
    padding: 10px;
    box-sizing: border-box;
}
li{
    align-self:center;
    list-style: none;
    width:20%;
    max-width: 150px;
    min-width: 100px;
    margin: 5px;
    padding: 5px;
    box-sizing: border-box;
   
}
a{
    font-family: "mom", sans-serif;
    font-weight: 600;
    text-decoration: none;
    transition-property:border ;
    transition-duration: 1s;
    transition-timing-function: cubic-bezier(0.1, 0.82, 0.165, 1);
}
a:link{
    color: rgb(0, 0, 0);
}
a:visited{
    color: rgb(4, 17, 84);
}
#nav a:hover{
    border-bottom:5px solid black;
    padding-bottom: 5px;
}
a img{
   vertical-align: bottom;
   margin-right:10px ;
}
/* signup button*/
#sign-up{
    border-radius:20px 20px;
    background-color: rgb(12, 12, 203);
    font-family: "mom", sans-serif;
    font-weight: 600;
}
#sign-up a{
    color: white;
    vertical-align: middle;
}
#sign-up a:hover {
    border: 0px;
    background-color: rgb(7, 7, 97);
}
/*logo of page*/
#logo{
    text-align: left;
    width: 30%;
    max-width: 100px;
    min-width: 70px;
    margin: 10px;
    padding: 10px;
    box-sizing: border-box;
}
#logo img{
    width:100%;
}
/* body contnet search*/
#intro{
    width: 100%;
    height: 500px;
    background-image: url("../images/giza-2.jpg");
    background-repeat: no-repeat;
    background-size:cover;
    
}

form{
    margin: 10px auto ;
}
#search-1{
    width: 70%;
    max-width: 700px;
    min-width: 400px;
    max-height: 80px;
    min-height: 60px;
    text-align: left;
    padding-left: 60px;
    margin: 40px;
    border-radius: 30px;
    box-sizing: border-box;
    font-family: "mom", sans-serif;
    font-weight: 600;
    font-size: 1.2em;
    background-image: url("../images/icons/search-1.png");
    background-repeat: no-repeat;
    background-position: 15px 15px;
    color: black;
}
#search-2{
    width:100px;
    text-align: center;
    font-family: "mom", sans-serif;
    font-size: 1.2em;
    font-weight: 600;
    color: white;
    background-color: blue;
    border-radius: 20px;
    max-height: 60px;
    min-height: 40px;
}
h1{
    position: relative;
    top:50px;
    left: 200px;
    width: 50%;
    max-width: 500px;
    min-width: 300px;
    padding: 20px;
    box-sizing: border-box;
    text-align: left;
    font-family: "mom", sans-serif;
    font-weight: 900;
    font-size: 3em;
    color: white;
}
/* fig-1 first figure of images */
h2{
    text-align: left;
    font-size: 2em;
    font-family: "mom", sans-serif;
    font-weight: 600;
    margin: 30px;
    padding: 30px;
    box-sizing: border-box;
}
.fig-1{
    display:flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content:flex-start;
    margin: 20px;
    padding: 20px;
    box-sizing: border-box;
}
.trips{
    position: relative;
    text-align: left;
    display: flex;
    flex-direction: column;
    align-content: space-between;
    width: 20%;
    height: 100%;
    max-width: 500px;
    min-width: 250px;
    max-height: 800px;
    min-height: 500px;
    margin: 20px;
    padding: 20px;
    box-sizing: border-box;
    box-shadow: 3px 3px 5px 5px rgb(166, 164, 164);
    border-radius:20px ;
    
}
.trips img{
    align-items: flex-start;
    width: 100%;
    max-width: 250;
    min-width: 200px;
    max-height: 250px;
    min-height: 200px;
    border-radius: 10px;   
}

.pra{
    position: absolute;
    top: 220px;
    align-items:center;
    margin: 10px;
    padding: 10px;
}
/*Avaliable activites in egypt*/
.activites{
    border-top: 2px solid rgb(166, 164, 164);
    margin: 20px;
    padding: 20px;
}
.fig-2{
    
    display:flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content:flex-start;
    margin: 20px;
    padding: 20px;
    box-sizing: border-box;
}
.activites li{
    border:2px solid rgb(16, 16, 162);
    border-radius: 10px;
    text-align: center;
}
.activites img{
    vertical-align: bottom;
}
/* section of cities in egypt*/
.cities{
    border-top: 2px solid rgb(166, 164, 164);
    margin: 20px;
    padding: 20px;
}
.cities div{
    width: 25%;
    max-width: 400px;
    min-width: 300px;
    max-height: 400px;
    min-height: 300px;
    border-radius: 20px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin: 10px;
    padding: 10px;
    box-sizing: border-box;
}
.cities a{
    align-items:center ;
    color: rgb(7, 62, 110);
    font-family: "mom", sans-serif;
    font-weight: 600;
    font-size: 2em;
}
.fig-3{
    display:flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content:flex-start;
    margin: 20px;
    padding: 20px;
    box-sizing: border-box;
}
#cairo{
    max-width: 400px;
    min-width: 250px;
    background-image: url("../images/paragrap-images/cairo.jpg");
    background-repeat: no-repeat;
    background-size:cover;
    
    
}
#giza{
    max-width: 400px;
    min-width: 250px;
    background-image: url("../images/paragrap-images/giza.jpg");
    background-repeat: no-repeat;
    background-size:cover;
   
    
}

#alexandria{
    max-width: 400px;
    min-width: 250px;
    background-image: url("../images/paragrap-images/alexandria-1.jpg");
    background-repeat: no-repeat;
    background-size:cover;
    
}
#luxor{
    width: 25%;
    max-width: 400px;
    min-width: 250px;
    background-image: url("../images/paragrap-images/luxor-3.jpg");
    background-repeat: no-repeat;
    background-size:cover;
    
    
}
#aswan{
    max-width: 500px;
    min-width: 250px;
    background-image: url("../images/paragrap-images/aswan-2.jpg");
    background-repeat: no-repeat;
    background-size:cover;
    
    
}
#hurghada{
    max-width: 400px;
    min-width: 250px;
    background-image: url("../images/paragrap-images/hurghada.jpg");
    background-repeat: no-repeat;
    background-size:cover;
    
    
}
#sharm{
    max-width: 400px;
    min-width: 250px;
    background-image: url("../images/paragrap-images/sharm.jpg");
    background-repeat: no-repeat;
    background-size:cover;
    
    
}
#dahab{
    max-width: 400px;
    min-width: 250px;
    background-image: url("../images/paragrap-images/dahab.jpg");
    background-repeat: no-repeat;
    background-size:cover;
    
    
}
#marsa{
    max-width: 400px;
    min-width: 250px;
    background-image: url("../images/paragrap-images/marsaalam.jpg");
    background-repeat: no-repeat;
    background-size:cover;
    
}
/* last section of mainbody*/
#reserv{
    position: relative;
    max-height: 700px;
    min-height: 300px;
    margin: 10px;
    padding: 10px;
    box-sizing: border-box;
    background-image: url("../images/sea.jpg");
    background-repeat: no-repeat;
    background-size: 50% 100%;
    background-color: rgba(151, 192, 255, 0.762);
    border-radius: 20px;
    border-bottom:2px solid rgb(166, 164, 164);
}
#reserv h2{
    margin: 0px;
    padding: 0px;
}

#reserv-email{
    position: absolute;
    left: 50%;
    margin: 10px;
    padding: 10px;
    box-sizing: border-box;
    text-align: left;
}
#email-address{
    width: 100%;
    max-width: 400px;
    min-width: 250px;
    height: 40px;
    border-radius: 10px;
}
#button{
    font-family: "mom", sans-serif;
    font-weight: 600;
    width: 20%;
    max-width: 100px;
    min-width: 80px;
    height: 40px;
    background-color: rgb(0, 0, 255);
    border-radius: 10px;
    margin: 10px;
    padding: 10px;
    box-sizing: border-box;
    color: white;
}
/* footer of page*/
#footer{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-evenly;
    margin-top: 50px;
    padding: 10px;
    border-top: 2px solid rgb(166, 164, 164);
    background-image: linear-gradient(to bottom, rgb(4, 13, 79), rgb(94, 143, 250));
    color: rgb(255, 255, 255);
    font-family: "mom", sans-serif;
    font-weight: 600;
}
#footer a {
    color: rgb(255, 255, 255);
}
#footer div{
    margin: 10px;
    padding: 10px;
    text-align: left;
    
}
select{
    padding: 10px;
    width: 25%;
    max-width: 700px;
    min-width: 250px;
    height: 40px;
    border-radius: 10px;
    box-sizing: border-box;
}

.socialmedia{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-self: flex-end;
    
}
.payment{
    max-width: 300px;
    min-width: 250px;

}
#privacy{
    align-self: flex-end;
}
/* login form*/
#log-in-1{
    font-family: "mom", sans-serif;
    font-weight: 600;
    margin: 50px;
    display: flex;
    flex-direction: column;
    align-content:space-between;
   
}
#log-in-1 div{
    margin: 10px;
    padding: 10px;
}
fieldset{
    width: 80%;
    max-width: 500px;
    min-width: 400px;
    margin: 5px auto;
    box-sizing: border-box;
    border-radius: 20px;
    background-image:linear-gradient(to bottom, rgb(46, 5, 123), rgb(122, 70, 255)) ;
}
#log-in-1 input{
    width: 30%;
    max-width: 500px;
    min-width: 400px;
    padding: 10px 10px 10px 50px;
    box-sizing: border-box;
    border-top:  transparent ;
    border-right: transparent;
    border-left: transparent;
    border-bottom: 2px solid rgb(162, 162, 162);
    border-radius: 10px;
    font-size: 1.2;
    font-weight: bold;
}
#log-in-1 h2{
    margin: 0px;
    padding: 5px;
    font-size: 1.8em;
    text-align: center;
    color: rgb(7, 154, 253);
}
#log-in-1 p{
    text-align: center;
    color: rgb(175, 177, 179);
}
#user input{
    background-image: url("../images/icons/mail.png");
    background-repeat: no-repeat;
    background-position:  left;
}
#psw input{
    background-image: url("../images/icons/lock.png");
    background-repeat: no-repeat;
    background-position:  left;
}
#rem-1{
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content:space-between;
    color: rgb(255, 255, 255);
}
#rem-1 a{
    color: rgb(255, 255, 255);
}
#rem-1 input{
    align-self: flex-start;
    width: 30px;
    max-width: 20px;
    min-width: 10px;
}

#submit-1 input{
    text-align: center;
    padding: 20px;
    box-sizing: border-box;
    border: 2px solid rgb(104, 117, 211);
    border-radius: 20px;
    background-color: rgb(40, 40, 116);
    color: rgb(255, 255, 255);
    font-size: 1.2em;

}
/*sign-up form*/
#sign-up-1{
    font-family: "mom", sans-serif;
    font-weight: 600;
    margin: 50px;
    display: flex;
    flex-direction: column;
    align-content:space-between;
}
#sign-up-1 input{
    width: 30%;
    max-width: 500px;
    min-width: 400px;
    padding: 10px 10px 10px 50px;
    box-sizing: border-box;
    border-top:  transparent ;
    border-right: transparent;
    border-left: transparent;
    border-bottom: 2px solid rgb(162, 162, 162);
    border-radius: 10px;
    font-size: 1.2;
    font-weight: bold;
}
#sign-up-1 div{
    margin: 10px;
    padding: 10px;
}
#sign-up-1 h2{
    margin: 0px;
    padding: 5px;
    font-size: 1.8em;
    text-align: center;
    color: rgb(7, 154, 253);
}
#policy-1{
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content:space-between;
    color: rgb(255, 255, 255);
}
#policy-1 input{
    align-self:flex-start;
    width: 30px;
    max-width: 20px;
    min-width: 10px;
}
#policy-1 label{
    text-align: left;
    margin-left:10px ;
}
#submit-2 input{
    text-align: center;
    padding: 20px;
    box-sizing: border-box;
    border: 2px solid rgb(104, 117, 211);
    border-radius: 20px;
    background-color: rgb(40, 40, 116);
    color: rgb(255, 255, 255);
    font-size: 1.2em;
}
/* responsive for mobile 0-500px*/
@media only screen and (max-width: 500px){
    
    #wish,#cart, #log-in, #help{
        display: none;
    }
    #logo{
        max-width: 60px;
        min-width: 50px;
    }
    li{
        max-width: 50px;
        min-width: 30px;
        margin: 2px;
        padding: 2px;
        box-sizing: border-box;
    }
    #nav{
        max-width: 300px;
        min-width: 200px;
    }
    .fig-1{
        justify-content: space-around;
    }
    .fig-2{
        justify-content: space-around;
    }
    .fig-3{
        justify-content: space-around;
    }
    #intro{
        width: 100%;
        max-width: 500px;
        min-width: 450px;
        height: 500px;
        background-image: url("../images/giza-2.jpg");
        background-repeat: no-repeat;
        background-size:cover;
        
       
    }
    #search-1{
        max-width: 300px;
        min-width: 200px;
    }
    h1{
        position: static;
        
    }
    .pra{
        position: static;
    }
    .activites ul{
        display: none;
    }
    #footer{
        width: 100%;
        max-width: 500px;
        min-width: 300px;
        justify-content: space-between;
    }
    #forms select{
        
        max-width: 300px;
        min-width: 200px;
    }
    
    
    
    
}
/*responsive from 500*/
@media only screen and (min-width: 500px){
    body{
        font-size:14px;
       
    }
    #wish,#cart, #log-in, #help{
        display: none;
    }
    li{
        max-width: 50px;
        min-width: 30px;
        margin: 2px;
        padding: 2px;
        box-sizing: border-box;
    }
    .activites ul{
        display: none;
    }
    .fig-3{
        justify-content: center;
    }
    .trips{
        margin: 20px auto;
    }
    
   
}
@media only screen and (min-width: 800px){
    body{
        font-size:16px;
       
    }
    #wish,#cart, #log-in, #help{
        display:inline;
    }
    li{
        align-self:center;
        list-style: none;
        width:20%;
        max-width: 150px;
        min-width: 100px;
        margin: 5px;
        padding: 5px;
        box-sizing: border-box;
       
    }
    .activites ul{
        display: flex;
    }
    .trips{
        margin: 20px;
    }
    .fig-1{
        justify-content: space-between;
    }
    
   
}
@media only screen and (max-width: 700px){
    body{
        font-size: 10px;
    }
    #reserv{
        position: static;
        background-image: none;
        max-height: 500px;
        min-height: 300px;
        margin: 10px;
        padding: 10px;
    }
    #reserv-email{
        position: static;
        margin: 5px;
        padding: 5px;
    }
    #email-address{
        width: 60%;
        max-width: 600px;
        min-width: 200px;
    }
    #log-in-1 h2{
        font-size: 1.3em;
    }
    #log-in-1 p{
        font-size: 1.2em;
    }
    fieldset{
        width: 100%;
        max-width: 500px;
        min-width: 300px;
        
    }
    #log-in-1 input{
       
        max-width: 300px;
        min-width: 230px;
    }
    #rem-1 input{
        
        width: 20px;
        max-width: 10px;
        min-width: 5px;
    
    }
    #sign-up-1 h2{
        font-size: 1.3em;
    }
    #sign-up-1 label{
        font-size: 1.2em;
        
    }
    #sign-up-1 input{
        max-width: 300px;
        min-width: 230px;
    }
    #policy-1 input{
        width: 30px;
        max-width: 20px;
        min-width: 10px;
    }
}
@media only screen and (width: 540px){
    body{
        font-size: 10px;
    }
    #log-in-1 h2 {
            font-size: 1.3em;
        }
    
        #log-in-1 p {
            font-size: 1.2em;
        }
    
        fieldset {
            width: 100%;
    
        }
    
        #log-in-1 input {
            max-width: 400px;
            min-width: 300px;
        }
    
        #rem-1 input {
            width: 20px;
            max-width: 15px;
            min-width: 10px;
        }
        #rem-1{
            justify-content: space-around;
        }
        #sign-up-1 h2{
            font-size: 1.3em;
        }
        #sign-up-1 label{
            font-size: 1.2em;
            
        }
        #sign-up-1 input{
            max-width: 400px;
            min-width: 300px;
        }
        #policy-1 input{
            width: 20px;
            max-width: 15px;
            min-width: 10px;
        }
}




        </style>
        <!--script of javascripts code-->
        <script>

        </script>
    </head>
    <!--body of our contents-->
    <body>
        <!--the header of nav bar-->
        <header>
            <div id="logo">
                <img src="images/logo/logo-1.png" alt="logo-egy-tours"/>
            </div>
            <ul id="nav">
                <li><a href="#"><img src="images/icons/heart-1.png" alt="wishlist"/><span id="wish">Wishlist</span></a>
                </li>
                <li><a href="#"><img src="images/icons/shopping-cart-1.png" alt="cart"/><span id="cart">cart</span></a>
                </li>
                <li><a href="#"><img src="images/icons/question-1.png" alt="help"/><span id="help">Help</span></a>
                </li>
                <li><a href="log-in/log-in.html"><img src="images/icons/log-in-1.png" alt="log-in"/><span id="log-in">log in</span></a>
                </li>
                <li id="sign-up"><a href="sign-up/sign-up.html">Sign up</a></li>
            </ul>
        </header>
        <main>
            <!--intro of page with bagground-->
            <section>
                <div id="intro">
                    <form method="post" action="#">
                        <input id="search-1" type="search" name="search" placeholder="where are you going?"/>
                        <input id="search-2" type="submit" name="search" value="Search"/> 
                    </form>
                    <h1>Discover a wonderful places in Egypt</h1>
                </div>
            </section>
            <!--content of page-->
            <section>
                <h2>Our bset places to visit in Egypt</h2>
                <figure class="fig-1">
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/luxor-1.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">Luxor</a></h3>
                            <p>
                                Wonderful place you can visit to see history around you in most greatest temples not just
                                in Egypt but also in world like karnak tempel and luxor tempel.     
                            </p>
                            <p>
                                duration 12 - 15 hours trip
                            </p>
                        </div>
                    </div>
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/aswan-2.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">Aswan</a></h3>
                            <p>
                                The second most wonderful place that you can visit and enjoy your time
                                just you can go to Aswan where a beautiful tempel called Phillie.
                            </p>
                            <p>
                                duration 6 - 8 hours trip
                            </p>
                        </div>
                    </div>
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/cave-1.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">Pyramids</a></h3>
                            <p>
                                The most imprortant journey that make you feel ammazed that watching one of seven wonders
                                of ancient world take you to a journy inside ancient history.  
                            </p>
                            <p>
                                duration 3 - 4 hours trip
                            </p>
                        </div>
                    </div>
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/boat.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">Sea trip</a></h3>
                            <p>
                                Here you can find a wonderful journey to sea trips where a beautiful coral reefs
                                and clear water you can find it in one of two popular places in Egypt sharm el shekh and hurghada.  
                            </p>
                            <p>
                                duration 6- 7 hours trip
                            </p>
                        </div>
                    </div>
                </figure>
            </section>
            <!--avaliable activites in Egypt-->
            <section class="activites">
                <h2>
                    Avaliable activites
                </h2>
                <ul class="fig-2">
                    <li>
                        <a href="#">Guided Tours</a>
                    </li>
                    <li>
                        <a href="#">Water activities</a>
                    </li>
                <li>
                    <a href="#">Desert safari</a>
                </li>
                <li>
                    <a href="#">Day trips</a>
                </li>
                <li>
                    <a href="#">Adventuers</a>
                </li>
                <li>
                    <a href="#">Private tours</a>
                </li>
                <li>
                    <a href="#"><img src="images/icons/filter-1.png"/>Filter</a>
                </li>
            </section>
            <!--second part of activites-->
            <section>
                <figure class="fig-1">
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/luxor-2.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">Day Trip</a></h3>
                            <p>
                                From Hurghada: Luxor valley of the kings Full-day Trips     
                            </p>
                            <p>
                                duration 13 - 16 hours trip small group
                            </p>
                        </div>
                    </div>
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/canyon.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">Water Activity</a></h3>
                            <p>
                                Sharm El-sheikh: Colored Canyon, Blue Hole and Dahab day trip
                            </p>
                            <p>
                                duration 8 hours trip small group
                            </p>
                        </div>
                    </div>
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/nile.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">Water Activity</a></h3>
                            <p>
                                Cairo: Dinner cruise on the Nile river with entertainment.
                            </p>
                            <p>
                                duration 4 hours trip small group
                            </p>
                        </div>
                    </div>
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/safari.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">Adventuer</a></h3>
                            <p>
                                Hurghada: Quad, jeep, camel and Buggy safari with BBQ dinner.  
                            </p>
                            <p>
                                duration 7 hours trip
                            </p>
                        </div>
                    </div>
                    <!--third activites in egypt-->
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/pyramids.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">Day Trip</a></h3>
                            <p>
                                From Cairo: Pyramids of Giza, Sphinx, Saqqara & Memphis Tour.     
                            </p>
                            <p>
                                duration 8 hours.
                            </p>
                        </div>
                    </div>
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/tent.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">ADVENTURE</a></h3>
                            <p>
                                Sharm El Sheikh: ATV, Bedouin Tent with BBQ Dinner and Show
                            </p>
                            <p>
                                duration 5 hours.
                            </p>
                        </div>
                    </div>
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/dolphin.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">WATER ACTIVITY</a></h3>
                            <p>
                                Hurghada: Dolphin-Watching Cruise with Snorkeling and Lunch
                            </p>
                            <p>
                                duration 7 - 8 hours.
                            </p>
                        </div>
                    </div>
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/saqqara.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">DAY TRIP</a></h3>
                            <p>
                                Cairo: Pyramids, Sakkara & Memphis Private Tour with Lunch  
                            </p>
                            <p>
                                duration 8 hours.
                            </p>
                        </div>
                    </div>
                    <!--Fourth activites in egypt-->
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/alexandria.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">Day Trip</a></h3>
                            <p>
                                From Cairo: Full-Day Historical Alexandria Tour    
                            </p>
                            <p>
                                duration 10 - 11 hours.
                            </p>
                        </div>
                    </div>
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/egypt.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">DAY TRIP</a></h3>
                            <p>
                                From Hurghada: Full-Day Trip to Cairo & Giza with BBQ Lunch
                            </p>
                            <p>
                                duration 16 hours - 1 day.
                            </p>
                        </div>
                    </div>
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/orange.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">WATER ACTIVITY</a></h3>
                            <p>
                                Red Sea Governorate: Orange Bay Snorkeling Cruise with Lunch
                            </p>
                            <p>
                                duration 7 - 8 hours small group.
                            </p>
                        </div>
                    </div>
                    <div class="trips">
                        <div class="img-1">
                            <a href="#"><img src="images/paragrap-images/oasis.jpg"/></a>
                        </div>
                        <div class="pra">
                            <h3><a href="#">ADVENTURE</a></h3>
                            <p>
                                Cairo: 2-Day Bahariya Oasis Camp and Desert Tour 
                            </p>
                            <p>
                                duration 2 days.
                            </p>
                        </div>
                    </div>
                </figure>
            </section>    
            <!--cities in egypt section-->
            <section class="cities">
                <h2>Citie in Egypt</h2>
                <figure class="fig-3">
                    <div id="cairo">
                        <a href="#">Cairo</a>
                    </div>
                    <div id="giza">
                        <a href="#">Giza</a>
                    </div>
                    <div id="alexandria">
                        <a href="#">Alexandria</a>
                    </div>
                    <div id="luxor">
                        <a href="#">Luxor</a>
                    </div>
                    <div id="aswan">
                        <a href="#">Aswan</a>
                    </div>
                    <div id="hurghada">
                        <a href="#">Hurghada</a>
                    </div>
                    <div id="sharm">
                        <a href="#">Sharm elsheikh</a>
                    </div>
                    <div id="dahab">
                        <a href="#">Dahab</a>
                    </div>
                    <div id="marsa">
                        <a href="#">Marsa alam</a>
                    </div>
                </figure>
            </section>
            <!--last section of main body-->
            <section id="reservition">
                <div id="reserv">
                    <div id="reserv-email">
                        <form>
                            <h2>Your travel journey starts here</h2>
                            <p>
                            Sign up now for travel tips, personalized itineraries, 
                            and vacation inspiration straight to your inbox.
                            </p>
                            <input id="email-address" type="email" name="sign-up" placeholder="Email"/>
                            <input id="button" type="submit" name="submit" value="Sign up"/>
                        </form>
                    </div>
                </div>
            </section>
        </main>
        <!--footer of page-->
        <footer id="footer">
            <!--languages and currency-->
            <div id="forms">
                <form>
                    <div>
                        <label for="lang">Languages</label>
                    </div>
                    <select id="lang" name="lang">
                        <option value="Eng">English</option>
                        <option value="Fren">French</option>
                        <option value="Italy">Italian</option>
                        <option value="german">German</option>
                        <option value="rus">Russian</option>
                        <option value="chin">Chinese</option>
                        <option value="arabic">Arabic</option>
                        <option value="spanish">Spanish</option>
                    </select>
                    <div>
                        <label for="cur">Currency</label>
                    </div>
                    <select id="cur" name="currency">
                        <option value="$">USA DOLLAR</option>
                        <option value="euro">EURO</option>
                        <option value="gbp">BRITISH POUND</option>
                        <option value="egp">EGYPTIAN POUND</option>
                    </select>   
                </form>
            </div>
            <!--suuport and about company-->
            <div>
                <div><a href="#">Support</a></div>
                <div><a href="#">Contact</a></div>
                <div><a href="#">Blog</a></div>
                <div><a href="#">Privacy and Policy</a></div>
            </div>
            <div>
                <div><a href="#">About us</a></div>
                <div><a href="#">Gift cards</a></div>
                <div><a href="#">Company</a></div>
                <div><a href="#">Travel guide</a></div>
            </div> 
            <!--our social media-->
            <div class="socialmedia">
                <div><a href="#"><img src="images/icons8-facebook-f-48.png" alt="facebook" title="facebook"/></a></div>
                <div><a href="#"><img src="images/icons8-twitter-48.png" alt="twitter" title="tiwtter"/></a></div>
                <div><a href="#"><img src="images/icons8-instagram-24.png" alt="instgram" title="instgram"/></a></div>
                <div><a href="#"><img src="images/icons8-pinterest-24.png" alt="pinterest" title="pinterest"/></a></div>
            </div>
            <div id="privacy">
                <div>© 2023 – 2024 EGY-TOURS. Made in EGYPT in Cairo.</div>
                <div class="payment">
                    <img src="images/payment-methods/cards-icons.png"/>
                </div> 
            </div>  
        </footer>
    </body>
</html>
