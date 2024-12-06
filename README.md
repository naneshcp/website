# Ex.07 Restaurant Website
# Date:06/12/2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.vvvvvvvvvvv

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<html>
   
    <head>
        <title>P4 Restaurant  </title>
    </head>
    <style>
       
        h1,ul{
            display: inline;
            padding:20px;
            
           
        }
        h1{
            margin-left: 10px;
        }
        nav{
            
           padding: 20px;
           background-color: black;
          color: rgb(255, 0, 0);
        }
        li{
            
            display: inline;
            color: gray;
            
        }
        li:hover{

            color: red;
            cursor: pointer;
        }
        ul{
            margin-left: 80px;
           
        }
       
        .box{
            background-color:orange;
            color:grey;
            display: inline;
          
            margin-left:35px;
            font-size: large;}
        input{
            padding: 20px;
            width: 50%;
           
        }
        .searchbar{
            margin-left: 20%;
            padding: 15px;
       
        }
        h2{
            text-align: center;
            font-size: 40px;
        }
        .img{
            display: inline-block;
            width: 420px;
            border-width: 2px;
            border-color: orange;
            border-style: solid;
            margin-left: 30px;

        }
        .img:hover{
            background-color: orange;
            color: blueviolet;
        }
        .info{
            margin-left: 35%;
            margin-right: 45%;
            border-width: 2px;
            border-style: dashed;
            padding: 10px;
            margin-top: 20px;
            
        }
    

    </style>
    <body>
       

        <nav>
            <h3 > Opening time 🕥: 10.00 am - 11.00 pm</h3>
           <h1 style="font-size: 80px;"> P<sup>4</sup> Restaurant</h1><h5 style="display: inline;">&lpar;NONVEG&rpar;</h5>
            {% load static %}
           <img src={% static 'images/logo_restaurant.jpg' %} width="200px" height="170px" style="margin-left: 85px;" >
        
           
            <ul>
                
                <li>RATINGS |</li>
                <li>BLOG |</li>
                <li>HELP |</li>
              
                <a href="loginpage.html">SIGN IN </a>
              
                
                

            </ul>
           
            <a class="box" href='templates\ordernow.html'>ORDER NOW!!!</a>
           
        </nav><br>

        <hr><br><center>
              <div class="serchbar">
                <input placeholder="Search"> 
             </div></center>
        <div>
            <h2   >
                FOOD MENU
            </h2>
            
        </div>
        <div class="img">
           {% load static%}
        <img src={% static 'images/food_image1.jpg '%} width="420px" height="300px" ><br>
     
       <ol ><li style="word-spacing: 210px;">DISH                         PRICES</li><br>
           <li style="word-spacing: 145px;">Chicken_briyani                       200/-</li><br> 
           <li style="word-spacing: 152px;"> Mutton_briyani                       250/-</li><br> 
           <li style="word-spacing: 126px;">Chiken_Fried_rice                     150/-</li><br> 
           <li style="word-spacing: 145px;">Egg_Fried_rice                        120/-</li><br> 
           <li style="word-spacing: 170px;">Egg_briyani                           180/- </li><br> 
           <li style="word-spacing: 133px;">Chicken_Noodles                       150/-</li><br> 
           <li style="word-spacing: 160px;">Egg_Noodles                           120/-</li><br> 
           <li style="word-spacing: 120px;">Schezwan_Noodles                      130/-</li><br> 
           <li style="word-spacing: 157px;">Mutton_curry                          100/-</li><br> 
           <li style="word-spacing: 157px;">Chicken_curry                         90/-</li><br> 
           <li style="word-spacing: 183px;">Egg_curry                             70/-</li>
        </ol> 
       </div>
        <div class="img">
            {% load static%}
            <img src={% static "images/starter.jpg" %} width="420px" height="300px" ><br>
           
                   
        <ol>
            <li style="word-spacing: 200px;">STARTER                     PRICES</li><br>
           <li style="word-spacing: 150px;">Chicken_spring_roll                 100/-</li><br> 
           <li style="word-spacing: 195px;">Chilli_prawns                    130/-</li><br> 
           <li style="word-spacing: 140px;">Chicken_manuchurian                     110/-</li><br> 
           <li style="word-spacing: 222px;">Meatballs                     170/-</li><br> 
           <li style="word-spacing: 188px;">Mutton_keema                         180/- </li><br> 
           <li style="word-spacing: 215px;">Chicken_65                       80/-</li><br> 
           <li style="word-spacing: 212px;">Mutton_85                           180/-</li><br> 
           <li style="word-spacing: 211px;">sheek_kebab                      90/-</li><br> 
           <li style="word-spacing: 198px;">cheese_omelete                          70/-</li><br> 
           <li style="word-spacing: 139px;">Crispy_chicken_nuglets                        90/-</li><br> 
           <li style="word-spacing: 245px;">Egg_65                             60/-</li>
            
        </ol>
    </div> 
        <div class="img">
            {% load static%}
             <img src={% static "images/bevarages.jpg" %} width="420px" height="300px" ><br>
      
            <ol>
                <li style="word-spacing: 150px;">BEVARAGES                    PRICES</li><br>
           <li style="word-spacing: 175px;">Milkshakes                 100/-</li><br> 
           <li style="word-spacing: 225px;">Tea                  130/-</li><br> 
           <li style="word-spacing: 171px;">Cappuccino                     110/-</li><br> 
           <li style="word-spacing: 204px;">Mojito                     170/-</li><br> 
           <li style="word-spacing: 180px;">Lemonade                        180/- </li><br> 
           <li style="word-spacing: 188px;">Ice_cream                       80/-</li><br> 
           <li style="word-spacing: 172px;">Soft_drinks                           180/-</li><br> 
           <li style="word-spacing: 185px;">Rose_milk                     90/-</li><br> 
           <li style="word-spacing: 183px;">Fresh_juice                         70/-</li><br> 
           <li style="word-spacing: 193px;">Mocktails                        90/-</li><br> 
           <li style="word-spacing: 202px;">Desserts                            60/-</li>

            </ol>

    </div> 
        <br><br>
        <hr><br>
<footer>
        <nav>
        <div style="margin-left: 37%;">
            Contact us : More information<br>  </div>
           
         <div class="info">   
            📞 +91 1234567890<br>
            🌐 www.P<sup>4</sup>Restaurant.com<br>
            📍 00,Any st,Any city,123.
         </div>
         <p style="margin-left: 70%;">
            &copy;COPYRIGHT BY ----NANESHVARAN
         </p>

    </nav>
</footer>
        


    </body>
</html>

LOGINPAGE:
<html>
    <head>
        <title>
            Login Page
        </title>
    </head>
    <style>
        nav{
            
            padding: 20px;
            background-color: black;
           color: rgb(255, 0, 0);
         }
         h1,h3{
            display: inline;

         }
         img{
            width: 150px;
            height: 100px;
            
        }
        .title{
            font-size: 200px;

        }
        footer{
            /* background-color: black; */
            color: rgb(255, 0, 0);
        }
        body {
           
        background-color:purple;

    }
        
    </style>
    <body>
      
        <nav>
            
             {% load static %}
            <img src={% static "images/logo_restaurant.jpg" %}  >
            <h1 style="margin-left: 100px;" class="title">P<sup>4</sup>Restaurant</h1>
            <h3 style="margin-left: 10px;"> Opening time 🕥: 10.00 am - 11.00 pm</h3>
        </nav><br>
        <br>
        <hr>
        <br>
        
<center>
        <h1>L O G I N  P A G E</h1><br><br><hr>

        <form>
            <table>
                <tr>
                    <td>Name :</td> <td><input type="text" placeholder=" Enter your name"></td><br>
                    
                </tr>
                
                <tr>
                    <td>Mobile number :</td> <td><input type="number" placeholder="Enter your mobile number"></td><br>
                    
                </tr>

                <tr>
                    <td>Email :</td> <td><input type="email" placeholder="Enetr your email id"></td><br>
                    
                </tr>
                <tr>
                    <td>OTP :</td> <td><input type="number" placeholder="Enter your OTP"></td>
                    
                </tr>
            </table>
        </form>
            <br>
        <br>
        <footer>
            ✅ SUCCESSFULLY LOGGED IN...!!
            WELCOME TO P<sup>4</sup>;RESTAURANT..😇
           </footer>
</center><br><br>
<hr>
    

    </body>
</html>

ORDERPAGE:
<html>
    <head>
        <title>
            Ordering Page
        </title>
    </head>
    <style>
        h1,h3{
            display: inline;
        }
        
        img{
            width: 150px;
            height: 100px;
            display: inline;
            
        }
        .img{
            display: inline-block;
            width: 375px;
            height: 240px;
            margin-top: 30px;
            margin-left: 200px;
            margin-bottom: 30px;
         

        }
        .img2{
            display: inline-block;
            width: 375px;
            height: 240px;
            margin-left: 800px;
            margin-top: 10px; 
            margin-bottom: 30px;

        }
        .title{
            font-size: 200px;}
        nav{
            padding: 20px;
            background-color: black;
           color: rgb(255, 0, 0);
        }
        .choice{
            font-size: 40px;
            margin-left: 40px;
            color:green;

        }
        div{
            text-align: center;
            font-size: 20px;
            
           margin-left: 850px;
           display: inline;

        }
        span{
            text-align: center;
            font-size: 20px;
            
           margin-left: 280px;
           display: inline;
        }
        footer{
            background-color: black;
            color: rgb(255, 0, 0);
        }
        button:hover{
            background-color: red;
            color: black;
            cursor: pointer;
        }
        body{
            /* background-image: url("C:\Users\admin\Pictures\Saved Pictures\biriyani.jpg");
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center; */
            background-color:orange;

        }
    </style>
    <body>

            <nav>
            
          {% load static%}
                <img src={% static "images/logo_restaurant.jpg" %}  >
                <h1 style="margin-left: 100px;" class="title">P<sup>4</sup>Restaurant</h1>
                <h3 style="margin-left: 10px;"> Opening time 🕥: 10.00 am - 11.00 pm</h3>
            </nav><br>
      <br>
      <hr>
       <center> <h1>ORDERING PAGE:</h1></center><br><br>
        
       <div class="choice">Order your Main Course:</div> <br>
       {% load static%}
       <img src={% static "images/biriyani.jpg" %} class="img" ><br>
    
           <span > <input type="radio">Chicken_briyani --- 200/-</span><br>
            <span>  <input type="radio">Mutton_briyani ---250/-</span><br>
            <span> <input type="radio"> Egg_briyani-------180/-</span><br>
             {%load static%}
            <img src={% static "images/friedrice.jpg" %} class="img2"  ><br>
           
            <div><input type="radio">Chiken_Fried_rice---150/-</div><br> 
            <div><input type="radio">Special_Fried_rice---160/-</div>
          
            <div> <input type="radio"> Egg_Fried_rice-------120/-</div>
         
 
         
           {%load static%}
            <img src ={%static "images/noodles.jpg" %} class="img" ><br>
            <span><input type="radio"> Chicken_Noodles-----150/-</span><br>
            
            <span>   <input type="radio"> Egg_Noodles-----120/-</span><br>
          
            <span>  <input type="radio"> Schezwan_Noodles------130/-</span>
            {%load static%}
            <img src={% static "images/mutton_curry.jpg" %} class="img2"  ><br>
            <div>  <input type="radio">   Mutton_curry-------100/-</div><br>
        

            <div>  <input type="radio">Chicken_curry---90/-</div><br>
            
         


            <div>  <input type="radio">Egg_curry---70/-</div><br>
          
           
            
          
        <br><br>
        <div class="choice">Order your Starters:</div> <br>
        {%load static%}
       <img src=  {% static "images/muttonkeemA.jpg" %} class="img" ><br>
       <span>  <input type="radio">Meatballs ---170/-</span><br>      
       <span>   <input type="radio">Mutton_keema ---180/-</span><br>
       <span><input type="radio">chicken_chukka---160/-</span>
  
       {%load static%}
       <img src={% static "images/manchurian.jpg" %}  class="img2"><br>
        <div>
            <input type="radio"> Chicken_spring_roll--- 100/- </div><br>
        <div>   <input type="radio"> Chilli_prawns---130/-</div><br>
        <div>   <input type="radio"> Chicken_manuchurian --- 110/-</div><br>  
        {%load static%}
        <img src=  {% static "images/friedchciken.jpg" %} class="img"  ><br>
        <span>  <input type="radio">Chicken_65  --- 80/-</span><br>      
        <span>  <input type="radio"> Mutton_85 ---180/-</span><br>
        <span><input type="radio">sheek_kebab---90/-</span><br> 
        {%load static%}
        <img src={% static "images/cheese_omelete.jpg" %} class="img2"><br>     
        <div><input type="radio">cheese_omelete--- 70/-</div><br>      
        <div><input type="radio" > Crispy_chicken_nuglets ---90/-</div><br>
        <div>   <input type="radio" >Egg_65--- 60/-</div>
        <br><br>
        <div class="choice">Order your Bevarages:</div> 
         <br> 
         {%load static%}
         <img src= {% static "images/bevarages.jpg" %} class="img"><br>
         <span> <input type="radio">Mojito---170/-</span><br> 
        <span> <input type="radio">Lemonade---180/-</span><br> 
        <span> <input type="radio">Soft_drinks---180/-</span><br>
        {%load static%}
         <img src= {% static "images/milkshakes.jpg" %}  class="img2"><br>
         <div> <input type="radio"> Milkshakes---100/-</div><br>
         <div> <input type="radio">Rose_milk---90/-</div><br> 
         <div> <input type="radio">Fresh_juice---70/-</div><br>  
         {%load static%}
         <img src= {% static "images/mocktails.jpg" %} class="img"><br>
         
    
         
        <span><input type="radio">cocktails--100/-</span><br>
        <span> <input type="radio">Mocktails---90/-</span><br> 
        <span> <input type="radio">Desserts---60/-</span><br><br>
        {%load static%}
         <img src= {% static "images/tea.jpg" %} class="img2"><br>
    
        <div> <input type="radio">Tea---30/-</div><br> 
        <div> <input type="radio">Cappuccino---70/-</div><br>
        <div> <input type="radio">Ice_cream---80/-</div><br>  
        
    

      <center>  <button >PLACE ORDER</button>    <button>DELETE  ORDER</button></center>
    
    <footer><center>
        ✅ SUCCESSFULLY ORDERED...!!
        THANK YOU..🙏 
    </center> </footer>
<hr>  </body><br>
    
</html>
```
# OUTPUT:
![output07(web)i](https://github.com/user-attachments/assets/19c2b713-f8ba-45b5-9663-8e41275689a0)
![output07(web)ii](https://github.com/user-attachments/assets/fe9e98ad-9705-46fa-9c8d-bffabff6fbba)
![output07(web)log](https://github.com/user-attachments/assets/26b3b8ff-6f02-42a8-982f-75a48e404d12)
![output07(ordering)i](https://github.com/user-attachments/assets/61714b23-7746-41fa-a556-8970a7ff2842)
![output07(ordering)ii](https://github.com/user-attachments/assets/2273e2c5-a93c-4634-b76f-cf573c91754e)


# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
