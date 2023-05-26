# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :

## Home.html:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title> Home </title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"> pavi private limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 pavi Private Limited, Developed by pavithra.
      </div>
    </div>
  </body>
</html>
```
## Product.html;
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title> Products </title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"> pavi Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 pavi Private Limited, Developed by pavithra.
      </div>
    </div>
  </body>
</html>
```
## People.html:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            People
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
        <style>
        .home{
            height: 3000px;
            width: 85%;
            border: 12px solid purple;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:cyan;
        }
        .text{
        color:whitesmoke;
        font-family:'Lucida sans';
        font-size: 30px;
        text-align:center;
        
        }
        .content{
            border:2px solid green;
            background-color:purple;
            width:98%;
            height:2690px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ceoph{
            background-image: url(/static/img/1.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:3px solid black;
            height:280px;
            width:18%;
            position:relative;
            left: 0px;
            margin-left:auto;
            margin-right: auto;
        }
        .ceo{
            color:cyan;
            position:relative;
            text-align:center;
            
            
        }
        .manph1{
            background-image: url(/static/img/7.jpeg);
             background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:3px solid black;
            height:280px;
            width:18%;
            position:relative;
            margin-left:auto;
            margin-right:auto;            
        }
        .man1{
            color:cyan;
            position:relative;
            text-align:center;
            
        }
        .manph2{
            background-image: url(/static/img/8.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:3px solid black;
            height:280px;
            width:18%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .man2{
            color:cyan;
            position:relative;
            text-align:center;
        }
        
        .amph1{
            background-image: url(/static/img/4.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:3px solid black;
            height:280px;
            width:18%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am1{
            color:cyan;
            position:relative;
            text-align:center;
        }

        .amph2{
            background-image: url(/static/img/5.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:3px solid black;
            height:280px;
            width:18%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am2{
            color:cyan;
            position:relative;
            text-align:center;
        }
        .amph3{
            background-image: url(/static/img/6.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:3px solid black;
            height:280px;
            width:18%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am3{
            color:cyan;
            position:relative;
            text-align:center;
        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color:darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color: darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color: darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>People</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>Board Members</p>
                    <h4><u>Chairman</u></h4>
                    </div>
                    <div class="ceoph"></div>
                    <div class="ceo"><p align="center"><b><h2> jeniha anto </h2></b></div>
                    <br>
                    <div class="text">
                        <p><b><u>Head executives</u></b></p><br>
                    </div>
                    <div class="manph1"></div>
                    <div class="man1"><p align="center"><b>abrin nisha<h2>  </h2></b></p></div>
                    <div class="manph2"></div>
                    <div class="man2"><p><b><h2> yogabharathi </h2></b></p></div>
                    <br>
                    <div class="text"><p><b><u>Managers</u></b></p></div><br>
                    <div class="amph1"></div>
                    <div class="am1"><p align="center"><b> neha <h2> </h2></b></p></div>
                    <div class="amph2"></div>
                    <div class="am2"><p align="center"><b><h2> pavithra </h2></b></p></div>
                    <div class="amph3"></div>
                    <div class="am3"><p align="center"><b><h2> vaishi</h2></b></p></div><br>
                    <div class="text">Thank you so much for your kind support!<br>Hope our products had made you more B-E-A-U-T-I-F-U-L!</div>
                </div>
                <div class="footer">
                <footer style="color:black">
                Copyright &copy;2023 Developed by pavithra</footer></div>
            </div>
        </div>
    </body>
</html>
```
## Contact.html:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Contact Us
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
        
    .content{
            border:2px solid green;
            background-color:purple;
            width:98%;
            height:500px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
    }
    
    .text{
        color:whitesmoke;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    
    
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Contact Us</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p><b>Here are the details about us
                    <h5>Do contact us for any need</h5></b></p>
                    
                    </div>
                    <b><h2>Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                        No:14, old Street, east Tambaram, Chennai.
                    </p>
                    <ul>
                        <li><b>Landline:</b> 9078654321 </li>
                        <li><b>Mobile</b>: 9876543210</li>
                        <li><b>Facebook</b>: fb/pavitally</li>
                        <li><b>Email Id:</b>pavi@fancyuniv.com</li>
                    </ul>
                    <div style="text-align: center;color:violet;font-size:20px;"><b>Use Our Services and Beautify Yourself!</b></div>

                </div>
                <div class="footer">
                <footer style="color:black">
                Copyright &copy;2023 Developed by pavithra</footer></div>
            </div>
        </div>
    </body>
</html>
```
## OUTPUT:

### Home Page:

![home page](https://github.com/22008686/productcompanywebsite/assets/118916413/928c860f-a75e-466a-8f86-8c412a7e010d)

## Poduct Page:

![product page 1](https://github.com/22008686/productcompanywebsite/assets/118916413/1de7c949-f4e3-4105-a2b8-cc3394d7f4f7)

![product page 2](https://github.com/22008686/productcompanywebsite/assets/118916413/beb5de5f-5a22-40ed-bd29-b995b058a491)

## People Page:

![people 1](https://github.com/22008686/productcompanywebsite/assets/118916413/68f6fb20-5402-4937-bdf6-17ddf59014e3)

![people 2](https://github.com/22008686/productcompanywebsite/assets/118916413/294f678d-2711-40d6-aece-a8a03dd59454)

![people 3](https://github.com/22008686/productcompanywebsite/assets/118916413/bd9fdaf2-f955-4dbc-b13c-25d0c43f5b2b)

![people 4](https://github.com/22008686/productcompanywebsite/assets/118916413/5f8020cd-2ca1-4f80-975a-496fe098b3d4)

![Uploading people 5.png…]()























## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
