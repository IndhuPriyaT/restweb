# Ex.07 Restaurant Website
## Date: 15.12.2024

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

<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width , initial-scale=1.0">
    </head>    
        <style type="text/css">
              *{
                padding: 0%;
                margin: 0%;
                
              }
              body
              {
                background-color: #4bc558;
              }
            h1{
                 background-color: rgb(9, 73, 9) ; 
                 text-align: center;
                text-indent: 5px;
                font-size: 55px;
                color: rgba(30, 206, 59, 0.873);
                height: 85px;
                padding: 55px;
                position: relative;  
            }
            
           
   
        .navbar{
            background-color: rgb(17, 44, 17) ;
            display: flex;
            width: 100%;
            padding: 14px 25px;
            align-items: center;
            justify-content: center;
             height: 15px;

        }
        .nav-links{
            list-style: none;
            display: flex;
            color:aquamarine;
                }
        .nav-links li{
            margin-top: 16px;
            padding: 80px 50px 68px 99px;
            color:  rgb(17, 44, 17);
        }
        .nav-links a {
    color: #1cb72b;
    text-decoration: none;
    font-size: 18px;
    font-family: 'Open Sans', sans-serif;
    font-weight: 600;
    transition: all 0.3s ease-in-out;
    padding: 10px 15px;
    border-radius: 5px;
}

.nav-links a:hover {
    color: #35ab4e; 
    background-color: #053403; 
    transform: scale(1.1); 
}

.nav-links a.active {
    color:  #35ab4e; ; 
    font-weight: 700;
    border-bottom: 2px solid #062c0f; 
}
.container
{
    position: relative;
}
img
{
    height: 450px;
    width: 100%;
    border-radius: 3;

}
.photo{
    
    
    margin-top: 20px;
   margin-bottom: 5px; 
   /* margin-left: 10px; */
   margin-right: 20px;
   width: 100%;
   height: 550px;
   background-image: url(photo.png);
   border-radius: 5%;
   z-index: 1;
}


.centered {
  font-size: 60px;
  color: rgb(217, 237, 223);
  top: 50%;
  left: 50%;
  right: -20%;
  position: absolute;
  transform: translate(-50%,-50%);
  text-align: left;
  bottom: -50%;
}
.image-content{
    box-shadow: #062c0f;
    

}

.shadow-box{
    padding: 20px;
    background-color: #062c0f;
    box-shadow: 30px 28px 30px rgba(4, 51, 30, 0.237);
    border-radius: 8px;
    max-width: 200px;
    max-height: 350px;
    text-align: center;
    color: rgb(217, 237, 223);
    


}
.container-box{
    display: flex;
    justify-content: space-between;
    gap: 10px;
}
.box{
    width: 900px;
    height: 900px;
    background-color: #053403;
    opacity: 0.5;
    align-items: center;
    justify-content: center;
    border-radius: 10px;
    color: rgba(30, 206, 59, 0.873);
    font-size: 45px;

    
}
.small-image{
    width: 500px;
    height: 400px;
    margin-left: 45px;
    margin-top: 25px;
    border-radius: 20px;

}
.link-color{
    color: greenyellow;
    text-decoration: #1cb72b;
}
            
        </style>
        <body>
            <main>
                <h1> The Lime Light</h1>
                <div class="navbar">
                   <ul class="nav-links">
                    <li><a href="home.html">HOME</a></li> <br>
                    <li><a href="menu.html">MENU</a></li>
                    <li><a href="admin.html">ADMIN</a></li>
                    <li><a href="contact.html">CONTACT US</a></li>
                   </ul>
                
                
                </div>
            
               
                <div class="container">
                    <img src="photo.png">
                <div class="centered">
                    <h2>SPECIAL<br> WEEKEND <br>OFFERS</h2>
                    <div class="image-content">
                        <p></p>
                    </div>
                </div>
                <div class="shadow-box">
                    <p> Enjoy the exclusive discounts offered every weekend</p>
                </div>
               <div class="container-box">
                <div class="box"><h4>Book a Table</h4> 
                <img src="table.png" alt="Table Image" class="small-image">
                <p>Book a Table now and whine later.  <br> <br>
                  <a href="bookatable.html" class="link-color">book a table now !</a> 
                </p>
                

                </div>
                
                <div class="box"><h4>Our New Menu</h4>
                <img src="food.jpg" alt=" Menu Image" class="small-image">
                <p>Change is good. Try our newest change in the menu. <br> <br>
                    <a href="menu.html" class="link-color">checkout the new menu</a>
                </p>
                
            
            
            </div>
               
                <div class="box"><h4>Opening Hours</h4>
                    <img src="window.png" alt="Hours Image" class="small-image">
                    <p>Working exclusive hours for our exclusive customers.</p>
                    <br> Working from Monday to Friday <br>
                    Open till 12 a.m exclusively.
                </div>
                
               </div>

                </div>
               
                     <hr>
                     <h2 align="center">Designed and Developed by Indhu Priya</h2>


                </div>
            
            </main> 
          
        </body>
</html>

home.html

<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width , initial-scale=1.0">
    </head>    
        <style type="text/css">
              *{
                padding: 0%;
                margin: 0%;
                
              }
              body
              {
                background-color: #4bc558;
              }
            h1{
                 background-color: rgb(9, 73, 9) ; 
                 text-align: center;
                text-indent: 5px;
                font-size: 55px;
                color: rgba(30, 206, 59, 0.873);
                height: 85px;
                padding: 55px;
                position: relative;  
            }
            
           
   
        .navbar{
            background-color: rgb(17, 44, 17) ;
            display: flex;
            width: 100%;
            padding: 14px 25px;
            align-items: center;
            justify-content: center;
             height: 15px;

        }
        .nav-links{
            list-style: none;
            display: flex;
            color:aquamarine;
                }
        .nav-links li{
            margin-top: 16px;
            padding: 80px 50px 68px 99px;
            color:  rgb(17, 44, 17);
        }
        .nav-links a {
    color: #1cb72b;
    text-decoration: none;
    font-size: 18px;
    font-family: 'Open Sans', sans-serif;
    font-weight: 600;
    transition: all 0.3s ease-in-out;
    padding: 10px 15px;
    border-radius: 5px;
}

.nav-links a:hover {
    color: #35ab4e; 
    background-color: #053403; 
    transform: scale(1.1); 
}

.nav-links a.active {
    color:  #35ab4e; ; 
    font-weight: 700;
    border-bottom: 2px solid #062c0f; 
}
.container
{
    position: relative;
}
img
{
    height: 450px;
    width: 100%;
    border-radius: 3;

}
.photo{
    
    
    margin-top: 20px;
   margin-bottom: 5px; 
   /* margin-left: 10px; */
   margin-right: 20px;
   width: 100%;
   height: 550px;
   background-image: url(photo.png);
   border-radius: 5%;
   z-index: 1;
}


.centered {
  font-size: 60px;
  color: rgb(217, 237, 223);
  top: 50%;
  left: 50%;
  right: -20%;
  position: absolute;
  transform: translate(-50%,-50%);
  text-align: left;
  bottom: -50%;
}
.image-content{
    box-shadow: #062c0f;
    

}

.shadow-box{
    padding: 20px;
    background-color: #062c0f;
    box-shadow: 0 8px 10px rgba(4, 51, 30, 0.237);
    border-radius: 8px;
    max-width: 200px;
    text-align: center;
    color: rgb(217, 237, 223);
    


}

      
            
        </style>
        <body>
            <main>
                <h1> The Lime Light</h1>
                <div class="navbar">
                   <ul class="nav-links">
                    <li><a href="home.html">HOME</a></li> <br>
                    <li><a href="menu.html">MENU</a></li>
                    <li><a href="admin.html">ADMIN</a></li>
                    <li><a href="contact.html">CONTACT US</a></li>
                   </ul>
                
                
                </div>
            
               
                <div class="container">
                    <img src="photo.png">
                <div class="centered">
                    <h2>SPECIAL<br> WEEKEND <br>OFFER</h2>
                    <div class="image-content">
                        <p></p>
                    </div>
                </div>
                <div class="shadow-box">
                    <p> Enjoy the exclusive discounts offered this weekend</p>
                </div>
              
                     
                <hr>
                <h2 align="center">Designed and Developed by Indhu Priya</h2>


                </div>
            
            </main> 
          
        </body>
</html>

admin.html

<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width , initial-scale=1.0">
    </head>    
        <style type="text/css">
              *{
                padding: 0%;
                margin: 0%;
                
              }
              body
              {
                background-color: #4bc558;
              }
            h1{
                 background-color: rgb(9, 73, 9) ; 
                 text-align: center;
                text-indent: 5px;
                font-size: 55px;
                color: rgba(30, 206, 59, 0.873);
                height: 85px;
                padding: 55px;
                position: relative;  
            }
            
           
   
        .navbar{
            background-color: rgb(17, 44, 17) ;
            display: flex;
            width: 100%;
            padding: 14px 25px;
            align-items: center;
            justify-content: center;
             height: 15px;

        }
        .nav-links{
            list-style: none;
            display: flex;
            color:aquamarine;
                }
        .nav-links li{
            margin-top: 16px;
            padding: 80px 50px 68px 99px;
            color:  rgb(17, 44, 17);
        }
        .nav-links a {
    color: #1cb72b;
    text-decoration: none;
    font-size: 18px;
    font-family: 'Open Sans', sans-serif;
    font-weight: 600;
    transition: all 0.3s ease-in-out;
    padding: 10px 15px;
    border-radius: 5px;
}

.nav-links a:hover {
    color: #35ab4e; 
    background-color: #053403; 
    transform: scale(1.1); 
}

.nav-links a.active {
    color:  #35ab4e; ; 
    font-weight: 700;
    border-bottom: 2px solid #062c0f; 
}
.container
{
    position: relative;
}
img
{
    height: 450px;
    width: 100%;
    border-radius: 3;

}
.photo{
    
    
    margin-top: 20px;
   margin-bottom: 5px; 
   /* margin-left: 10px; */
   margin-right: 20px;
   width: 100%;
   height: 550px;
   background-image: url(photo.png);
   border-radius: 5%;
   z-index: 1;
}


.centered {
  font-size: 60px;
  color: rgb(217, 237, 223);
  top: 50%;
  left: 50%;
  right: -20%;
  position: absolute;
  transform: translate(-50%,-50%);
  text-align: left;
  bottom: -50%;
}
.image-content{
    box-shadow: #062c0f;
    

}

.shadow-box{
    padding: 20px;
    background-color: #062c0f;
    box-shadow: 0 8px 10px rgba(4, 51, 30, 0.237);
    border-radius: 8px;
    max-width: 200px;
    text-align: center;
    color: rgb(217, 237, 223);
    


}
.container-box{
    display: flex;
    justify-content: space-between;
    gap: 10px;
}
.box{
    width: 900px;
    height: 800px;
    background-color: #053403;
    opacity: 0.5;
    align-items: center;
    justify-content: center;
    border-radius: 10px;
    color: rgba(30, 206, 59, 0.873);
    font-size: 45px;
    
    
}
.small-image{
    width: 200px;
    height: 150px;
   margin-left: 15px;
    margin-top: 25px;
    border-radius: 20px;
    align-items: center;


}
                

                
            
        </style>
        <body>
            <main>
                <h1> The Lime Light</h1>
                <div class="navbar">
                   <ul class="nav-links">
                    <li><a href="home.html">HOME</a></li> <br>
                    <li><a href="menu.html">MENU</a></li>
                    <li><a href="admin.html">ADMIN</a></li>
                    <li><a href="contact.html">CONTACT US</a></li>
                   </ul>
                
                
                </div>
            
               
                <div class="container">
                    <img src="photo.png">
                <div class="centered">
                    <h2>SPECIAL<br> WEEKEND <br>OFFER</h2>
                    <div class="image-content">
                        <p></p>
                    </div>
                </div>
                <div class="shadow-box">
                    <p> Enjoy the exclusive discounts offered this weekend</p>
                </div>
               <div class="container-box">
                <div class="box" align="center">
                    <img src="bashwanth.png.jpg">
                    <p>Bashwanth Raj</p>
                    <p>Chairman</p>
                </div>
                <div class="box" align="center">
                    <img src="reshma.png.jpg">
                    <p>Reshma.T</p>
                    <p>Managing Director,COO</p>
                </div>
                <div class="box" align="center">
                    <img src="jyopa.png.jpg">
                    <p>Jyoti Patel.G</p>
                    <P>Finance,CEO</P>
                </div>
                <div class="box" align="center">
                    <img src="magesh.png.jpg">
                    <p>Mageshwaran.T</p>
                    <p>Head Chef</p>

                </div>
                <div class="box" align="center">
                    <img src="indhu.png.jpg">
                    <p>Indhu Priya</p>
                    <P>Assisstant Chef</P>
                </div>
                <div class="box" align="center">
                    <img src="hema.png.jpg">
                    <p>Hema.M</p>
                    <p>Franchise Head</p>
                </div>
               </div>
                
                
                <hr>
                <h2 align="center">Designed and Developed by Indhu Priya</h2>
 

               
                </div>
            
            </main> 
          
        </body>
</html>

menu.html

<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width , initial-scale=1.0">
    </head>    
        <style type="text/css">
              *{
                padding: 0%;
                margin: 0%;
                
              }
              body
              {
                background-color: #4bc558;
              }
            h1{
                 background-color: rgb(9, 73, 9) ; 
                 text-align: center;
                text-indent: 5px;
                font-size: 55px;
                color: rgba(30, 206, 59, 0.873);
                height: 85px;
                padding: 55px;
                position: relative;  
            }
            
           
   
        .navbar{
            background-color: rgb(17, 44, 17) ;
            display: flex;
            width: 100%;
            padding: 14px 25px;
            align-items: center;
            justify-content: center;
             height: 15px;

        }
        .nav-links{
            list-style: none;
            display: flex;
            color:aquamarine;
                }
        .nav-links li{
            margin-top: 16px;
            padding: 80px 50px 68px 99px;
            color:  rgb(17, 44, 17);
        }
        .nav-links a {
    color: #1cb72b;
    text-decoration: none;
    font-size: 18px;
    font-family: 'Open Sans', sans-serif;
    font-weight: 600;
    transition: all 0.3s ease-in-out;
    padding: 10px 15px;
    border-radius: 5px;
}

.nav-links a:hover {
    color: #35ab4e; 
    background-color: #053403; 
    transform: scale(1.1); 
}

.nav-links a.active {
    color:  #35ab4e; ; 
    font-weight: 700;
    border-bottom: 2px solid #062c0f; 
}
.container
{
    position: relative;
}
img
{
    height: 450px;
    width: 100%;
    border-radius: 3;

}
.photo{
    
    
    margin-top: 20px;
   margin-bottom: 5px; 
   /* margin-left: 10px; */
   margin-right: 20px;
   width: 100%;
   height: 550px;
   background-image: url(photo.png);
   border-radius: 5%;
   z-index: 1;
}


.centered {
  font-size: 60px;
  color: rgb(217, 237, 223);
  top: 50%;
  left: 50%;
  right: -20%;
  position: absolute;
  transform: translate(-50%,-50%);
  text-align: left;
  bottom: -50%;
}
.image-content{
    box-shadow: #062c0f;
    

}

.shadow-box{
    padding: 20px;
    background-color: #062c0f;
    box-shadow: 0 8px 10px rgba(4, 51, 30, 0.237);
    border-radius: 8px;
    max-width: 200px;
    text-align: center;
    color: rgb(217, 237, 223);
    


}

.container-box{
    display: flex;
    justify-content: space-between;
    gap: 10px;
}
.box{
    width: 900px;
    height: 800px;
    background-color: #053403;
    opacity: 0.5;
    align-items: center;
    justify-content: center;
    border-radius: 10px;
    color: rgba(30, 206, 59, 0.873);
    font-size: 45px;
    
    
}
.small-image{
    width: 200px;
    height: 150px;
   margin-left: 15px;
    margin-top: 25px;
    border-radius: 20px;
    align-items: center;


}
                
            
        </style>
        <body>
            <main>
                <h1> The Lime Light</h1>
                <div class="navbar">
                   <ul class="nav-links">
                    <li><a href="home.html">HOME</a></li> <br>
                    <li><a href="menu.html">MENU</a></li>
                    <li><a href="admin.html">ADMIN</a></li>
                    <li><a href="contact.html">CONTACT US</a></li>
                   </ul>
                
                
                </div>
            
               
                <div class="container">
                    <img src="photo.png">
                <div class="centered">
                    <h2>SPECIAL<br> WEEKEND <br>OFFER</h2>
                    <div class="image-content">
                        <p></p>
                    </div>
                </div>
                <div class="shadow-box">
                    <p> Enjoy the exclusive discounts offered this weekend</p>
                </div>
               <div class="container-box">
                <div class="box" align="center">Grilled Paneer Skewers

                    <img src="panner.png" alt="Panner Image" class="small-image">
                    <p>Indian cottage cheese skewers with veggies, grilled and served with mint chutney.
                    </p>
                </div>
                

                <div class="box" align="center">Pesto Pasta
                    <img src="pasta.png" alt="Pasta Image" class="small-image">
                    <p>Penne pasta tossed in basil pesto sauce and topped with parmesan.
                    </p>
                </div>
               
                <div class="box" align="center">Banana Bread and Cream
                <img src="banana.png" alt="Banana Bread Image" class="small-image">
                <p>A slice of moist banana bread served warm with whipped butter.</p>
                </div>
                <div class="box" align="center"> Potato Fries
                <img src="potato.png" alt="Loaded Fries Image" class="small-image">
                <p>Sweet potato fries topped with sour cream, guacamole, and shredded cheese.</p>
                </div>
                <div class="box" align="center">Chicken Quesadilla
                <img src="chicken.png" alt="Chicken Quesadilla Image" class="small-image">
                <p>Grilled tortillas filled with chicken, cheese, and mild salsa.</p>
                </div>
                <div class="box" align="center">Nutella Crepes
                <img src="crepes.png" alt="Crepes Image" class="small-image">
                <p>Thin crepes filled with Nutella and topped with powdered sugar.</p>
                </div>
                <div class="box" align="center">Vanilla Iced Coffee
                <img src="vanilla.png" alt="Vannila Image" class="small-image">
                <p>Cold iced coffee with extra scoops of vanilla ice cream.</p>
                </div>
                <div class="box" align="center">Cucumber Mint Cooler
                <img src="cooler.png" alt="cooler image" class="small-image">
                <p>A refreshing drink filled with cucumber slices</p>
                </div>
                <div class="box" align="center">Honey Ginger Lemon Tea
                <img src="tea.png" alt="Ginger Tea Image" class="small-image">
                <p>Specially for the lemon tea lovers with a hit of ginger</p>
                </div>
                <div class="box" align="center">Cinnamon Sugar Donuts
                <img src="donuts.jpg" alt="Donut Image" class="small-image">
                <p>Freshly baked donuts rolled in cinnamon sugar.</p>
                </div>
                <div class="box" align="center" > Plain Cheesecake
                <img src="cheesecale.jpg" alt="Cheesecake Image" class="small-image">
                <p>Taste the goodness of plain cheesecake</p>
                </div>
                <div class="box" align="center">Salad Bowl
                <img src="bowl.jpg" alt="Fruit Bowl Image" class="small-image">
                <p>A bowl filled with freshly picked up fruits.</p>
                </div>
               </div>
                
                
                <hr>
                <h2 align="center">Designed and Developed by Indhu Priya</h2>



                </div>
            
            </main> 
          
        </body>
</html>

contact.html

<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width , initial-scale=1.0">
    </head>    
        <style type="text/css">
              *{
                padding: 0%;
                margin: 0%;
                
              }
              body
              {
                background-color: #4bc558;
              }
            h1{
                 background-color: rgb(9, 73, 9) ; 
                 text-align: center;
                text-indent: 5px;
                font-size: 55px;
                color: rgba(30, 206, 59, 0.873);
                height: 85px;
                padding: 55px;
                position: relative;  
            }
            
           
   
        .navbar{
            background-color: rgb(17, 44, 17) ;
            display: flex;
            width: 100%;
            padding: 14px 25px;
            align-items: center;
            justify-content: center;
             height: 15px;

        }
        .nav-links{
            list-style: none;
            display: flex;
            color:aquamarine;
                }
        .nav-links li{
            margin-top: 16px;
            padding: 80px 50px 68px 99px;
            color:  rgb(17, 44, 17);
        }
        .nav-links a {
    color: #1cb72b;
    text-decoration: none;
    font-size: 18px;
    font-family: 'Open Sans', sans-serif;
    font-weight: 600;
    transition: all 0.3s ease-in-out;
    padding: 10px 15px;
    border-radius: 5px;
}

.nav-links a:hover {
    color: #35ab4e; 
    background-color: #053403; 
    transform: scale(1.1); 
}

.nav-links a.active {
    color:  #35ab4e; ; 
    font-weight: 700;
    border-bottom: 2px solid #062c0f; 
}
.container
{
    position: relative;
}
img
{
    height: 450px;
    width: 100%;
    border-radius: 3;

}
.photo{
    
    
    margin-top: 20px;
   margin-bottom: 5px; 
   /* margin-left: 10px; */
   margin-right: 20px;
   width: 100%;
   height: 550px;
   background-image: url(photo.png);
   border-radius: 5%;
   z-index: 1;
}


.centered {
  font-size: 60px;
  color: rgb(217, 237, 223);
  top: 50%;
  left: 50%;
  right: -20%;
  position: absolute;
  transform: translate(-50%,-50%);
  text-align: left;
  bottom: -50%;
}
.image-content{
    box-shadow: #062c0f;
    

}

.shadow-box{
    padding: 20px;
    background-color: #062c0f;
    box-shadow: 0 8px 10px rgba(4, 51, 30, 0.237);
    border-radius: 8px;
    max-width: 200px;
    text-align: center;
    color: rgb(217, 237, 223);
    


}
.container-box{
    display: flex;
    justify-content: space-between;
    gap: 10px;
}
.box{
    width: 900px;
    height: 900px;
    background-color: #053403;
    opacity: 0.5;
    align-items: center;
    justify-content: center;
    border-radius: 10px;
    color: rgba(30, 206, 59, 0.873);
    font-size: 45px;
    margin-left: 1000px;
    
}



                
            
        </style>
        <body>
            <main>
                <h1> The Lime Light</h1>
                <div class="navbar">
                   <ul class="nav-links">
                    <li><a href="home.html">HOME</a></li> <br>
                    <li><a href="menu.html">MENU</a></li>
                    <li><a href="admin.html">ADMIN</a></li>
                    <li><a href="contact.html">CONTACT US</a></li>
                   </ul>
                
                
                </div>
            
               
                <div class="container">
                    <img src="photo.png">
                <div class="centered">
                    <h2>SPECIAL<br> WEEKEND <br>OFFER</h2>
                    <div class="image-content">
                        <p></p>
                    </div>
                </div>
                <div class="shadow-box">
                    <p> Enjoy the exclusive discounts offered this weekend</p>
                </div>
                <div class="container-box">
                    <div class="box">
                        <h2>CONTACTS</h2>
                        <br>
                        <br>
                        <p><b>For emergency purposes contact:9080287431</b></p>
                        <br>
                        <br>
                        <p>Do follow us on:</p>
                        <br>
                        <p>Instagram:@thelimelight</p>
                        <br>

                        <p>Youtube:The Lime Light</p>
                        <br>
                        <p>e-mail:thelimelight@gmail.com</p>

                    </div>
                </div>
               
                
                     
                <hr>
                <h2 align="center">Designed and Developed by Indhu Priya</h2>


                </div>
            
            </main> 
          
        </body>
</html>

```



## OUTPUT:
![alt text](<rest/restapp/static/Screenshot (42).png>)
![alt text](<rest/restapp/static/Screenshot (43).png>)
![alt text](<rest/restapp/static/Screenshot (44).png>)
![alt text](<rest/restapp/static/Screenshot (45).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
