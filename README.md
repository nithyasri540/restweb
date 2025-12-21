# Ex.06 Restaurant Website
## Date:19.12.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
rest.html
<html>
  <head>
    <title>Flexbox Design</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <div class="shop-name">
      <p>LEAF TABLE</p>
    </div>
    <div class="link">
      <a href="rest.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact-us</a>
    </div>
     <div class="pic">
                <img src="ambience1.png">
    <div class="txt">
                
    </div>

    <div class="footer">
      S.NITHYASRI (25018590)
    </div>
  </body>
</html
style5.css
body {
  background-image: url("restaurant.jpeg");
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.shop-name {
  margin-top: 150px;
  font-size: 60px;
  font-weight: bolder;
  color: rgba(71, 30, 110, 1);
  text-align: right;
}

.
.link {
  display: flex;
  position: fixed;
  top: 10;
  justify-content: space-evenly;
  align:center;
  width: 800px;
  height: 55px;
  font-size: 22px;
}



.footer {
  position:top;
  bottom: 0;
  left: 0;
  width: 100%;
  background-color: rgba(97, 119, 32, 1);
  color: white;
  text-align: center;
  padding: 2px;
}
menu.html
<html>
    <head>
        <title>Restaurant</title>
        <link rel="stylesheet" href="style2.css">
    </head>
    <body>
       
       <h1>Our Menu</h1><br>
                <div class="MENU">
                    
                <a href="rest.html" title="Home">Home</a>
                 <a href="menu.html" title="Menu">Menu</a>
                 <a href="admin.html" title="Admin">Admin</a>
                 <a href="contactus.html" title="Contact Us">Contact Us</a>
                 
            </div>
            
             <div class="container">
            <div class="item">
                <img src="food image 1.png" alt="burger with french fries">         
                <h3>burger with french fries</h3>         
                <p class="price">Rs.300</p>         
                
            </div>
             <div class="item">
                <img src="food image2.png" alt="cheese burger">         
                <h3>cheese burger</h3>         
                <p class="price">Rs.600</p>         
                
 </div>
             <div class="item">
                <img src="food image 3.png" alt="Chappathi">         
                <h3>chappathi</h3>         
                <p class="price">Rs.200</p>         
                
            </div>
            <div class="item">
                <img src="food image 4.png" alt="hiyashi chuka">         
                <h3>hiyashi chuka</h3>         
                <p class="price">Rs.450</p>         
                
            </div>
            <div class="item">
                <img src="food image 5.png" alt="Corn dog">
                <h3>corn dog</h3>         
                <p class="price">Rs.150</p> 
                
            </div>
            <div class="item">
                <img src="food image 6.png" alt="Dahi puri">
                <h3> dahi puri </h3>
                <p class="price">Rs.200</p>  
                
            </div>
            <div class="item">
                <img src="food image 7.png" alt="Pan cake">
                <h3>pan cake</h3>
                <p class="price">Rs.100</p> 
                
            </div>
         </div>
        </div>
    </div>
           
<div class="footer">
                <footer>&copy;S.NITHYASRI(25018590)</footer>           
</div>
 </body>
</html>
style.css
body{
     background-color: peachpuff;
     height: 100%;
     margin: 0;
}
.container{
    background:url(restweb.png) no-repeat center/contain;
    display:flex;
    flex-wrap: wrap;
    
    width: 100%;    

}
.name{
    font-size: 30px;
    font-weight: bold;
    position: absolute;
    left: 5%;
    margin-top: 90px;
    
      
}
.menu{
    position: absolute;
    left: 75%;
    margin-top: 160px;
    font-size: 18px;
    display: flex;
    gap: 20px;
}
a{
    color: black;
    text-decoration: none;
    
}
a:hover{
    color:rgb(255, 213, 0);
}

.footer{
    margin-top: 760px;
    position: absolute;
    left: 0;
    text-align: center;
    width: 100%;
    background-color: peachpuff;
    font-size: 23px;
     
}
.pic
{
    width: 1500px;
    height:500px;
    background: url(restweb.png) no-repeat center/cover;
    margin-top: 120px;
    position: absolute;
}
.pic{
    display: flex;
    justify-content: center;
    gap: 60px;
    margin-top: 250px;
}

.pic img {
    width: 500px;
    height: 450px;
    border-radius: 10px;
}
.txt{
     color: white;
     font-size: 32px;
     position: absolute;
     left: 5%;
     margin-top: -40px;
    -webkit-text-stroke: 2px black;
}

admin.html
<html>
    <head>
        <title>Restaurant</title>
        <link rel="stylesheet" href="style3.css">
    </head>
    <body>
       
       <h1>Administration Team</h1><br>
                <div class="menu">
                    
                <a href="rest.html" title="Home">Home</a>
                 <a href="menu.html" title="Menu">Menu</a>
                 <a href="admin.html" title="Admin">Admin</a>
                 <a href="contactus.html" title="Contact Us">Contact Us</a>
                 
            </div>
            
             <div class="container">
            <div class="admin">
                <img src="myimage.jpeg" alt="CEO">
                <h4>NITHYASRI</h4>         
                <h3>CEO</h3>         
                  
                
            </div>
             <div class="admin">
                <img src="narendra prasath.jpeg" alt=" Markerting Manager">   
                <h4>NARENDRA PRASATH</h4>      
                <h3> Markerting Manager</h3>         
                      
                
            </div>
             <div class="admin">
                <img src="ravi.png" alt="Manager">   
                <h4>RAVI</h4>      
                <h3>Manager</h3>   
               </div>
            <div class="admin">
                <img src="shreyas.png" alt="
                GeneralManager"> 
                <h4>SHREYAS</h4>        
                <h3>General Manager</h3>         
                       
                
            </div>
            <div class="admin">
                <img src="preetha.png" alt="HR"> 
                <h4>PREETHA</h4>        
                <h3>HR</h3> 
            </div>

             <div class="admin">
                <img src="vaaheesan.jpeg" alt="Chef">      
                <h4>VAAHESAN</h4>   
                <h3>Chef</h3> 
            </div>


             <div class="footer">
                <footer>&copy; NITHYASRI S(25018590)</footer>
            </div>
        </div>
        </body>
        </html>
style2.css
body{
     background-color: rgb(255, 185, 185);
     height: 3px;
     margin: 0;
}

.container{
    display:flex;
    flex-wrap: wrap;
    background:url(restweb.png) no-repeat center/contain;
    width: 99%;  
    gap: 18px; 
    align-items: center; 
}

h1{
    text-align: center;
    margin-top: 7px;
}
.menu{
   position: absolute;
    left: 39%;
    top: 7%;
    font-size: 25px;
    display: flex;
    gap: 18px;
    
}
a{
    color: black;
    text-decoration: none;
    
}
a:hover{
    color:rgb(249, 249, 26);
}
.footer{
    margin-top: 30px;
    position: absolute;
    left: 0;
    text-align: center;
    width: 100%;
    background-color: rgb(255, 185, 191);
    font-size: 23px;
     
}

.item{
    margin-top: 25px;
    margin-bottom: 25px;
    width: 220px;     
    background-color: rgb(255, 208, 0);     
    border: 1px solid red;    
    padding: 3px;     
    box-sizing: border-box;     
    border-radius: 7px;     
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);     
    text-align: center; 
    margin-left: 115px;
  
}
h3{
    font-size: 16px;
}
.price{
    font-size: 14px;
}
img{
    height: 145px;
    width: 130px;
    border-radius: 8px;

}

contact.html
<html>
    <head>
        <title>Restaurant</title>
        <link rel="stylesheet" href="style4.css">
    </head>
    <body>
       
       <h1>Contact Us</h1><br>
                <div class="menu">
                    
                <a href="rest.html" title="Home">Home</a>
                 <a href="menu.html" title="Menu">Menu</a>
                 <a href="admin.html" title="Admin">Admin</a>
                 <a href="contactus.html" title="Contact Us">Contact Us</a>
                 
            </div>
            <div class="container">
                <div class="address">
                    <h2>Contact Us</h2><br>
                    Visit us at:<br>
                    123 Angel Street,Heaven land,India.<br>
                    Phone:994-0592-8651<br>
                    Email: leaftable@gmail.com
                </div>
                 <div class="footer">
                <footer>&copy; nithyasri(25018590)</footer>
            </div>
            </div>
            </body>
            </html>
style4.css
body{
     background:url(restweb.png) no-repeat center/cover;
     height: 5px;
     margin: 0;
}
.container{
    display:flex;
    flex-wrap: wrap;
    background-color: peachpuff;
    width: 100%;  
    gap: 20px; 
    
    align-items: center; 

}

h1{
    text-align: center;
    margin-top: 7px;
    color: white;
}
.menu{
    position: absolute;
    top: 7%;
    left: 39%;
    font-size: 25px;
    display: flex;
    gap: 18px;
    
}
a{
    color: white;
    text-decoration: none;
    
}
a:hover{
 color:blue;
}
.footer{
    margin-top: 1275px;
    position: absolute;
    left: 0;
    text-align: center;
    width: 100%;
    background-color: peachpuff;
    font-size: 23px;
     
}
.address{
    text-align: center;
    position: absolute;
    left: 40%;
    margin-top: 500px;
    font-size: 20px;
    width: 300px;     
    color: white;    
    
}


##OUTPUT:
Screenshot (22).png
Screenshot (23).png
Screenshot (24).png
Screenshot (21).png





## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
