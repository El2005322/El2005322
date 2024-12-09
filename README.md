<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Eye of the Storm</title>
<link rel="icon" type="image/png" href="logofinalna.png">

<style>
/*BODY STYLE*/
body  {
            margin: 0;
            padding: 0;
            width: 100%;   
            height: 100%;
            overflow-x: hidden; 
            box-sizing: border-box; 
            background-color: #fcfcfc;
            }
      
/*NAVIGATIONS*/

    .topnav-container {
        position:fixed;
        top: 0;
        z-index: 1000; 
        width: 100%;
        }

        .topnav {
           position: sticky;
            top: 0;
            z-index:1000;
            display: flex;
            justify-content: space-between;
            align-items: right;
            padding: 10px 20px;
            }
      
        .topnav a {
            color: #000000;
            text-align: center;
            padding: 10px 10px;
            text-decoration: none;
            font-size: 15px;
            font-family:'Candara', sans-serif;
            }
      
        .topnav a:hover {
            background-color: #ddd;
            color: black;
            }
      
        .topnav a.active {
            color: rgb(0, 0, 0);
            background-color: #868686;
            }        

/* LOGO */

.topnav img {
    height: 50px; 
    width: auto;
}

/*CONTACT US*/

.container {
            display: flex;
            flex-wrap: wrap;
            width: 80%;
            margin: 0 auto;
            margin-top: 100px;
            margin-bottom: 10px;;
            padding: 0 15px;
            background-color: #fff;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            justify-content: center; 
            align-items: left;
            flex-direction: column;
            height: 100vh;
            box-sizing: border-box;
    }

        h1 {
            flex: 1 1 calc(33.333% - 30px);
            margin: 10px; 
            text-align: center;
            color: #333;
            font-size: 30px;
            font-family:'Franklin Gothic Medium', sans-serif;
        }

        p {
            text-align: left;
            margin-left: 20px;
            margin-top: 50px;
            margin-bottom: 0;
            font-size: 18px;
            font-family:'Lucida Sans', sans-serif;

        }

        ul {
            list-style-type: none;  
         }

        p2 {
            text-align: left;
            margin-left: 20px;
            margin-top: 10px;
            font-size: 15px;
            font-family: 'Lucida Sans Regular', sans-serif;
        }

        h2    {
            text-align: left;
            margin-left: 20px;
            margin-top: 40px;
            font-size: 18px;
            font-family:'Lucida Grande', sans-serif;
        }

    .p3 {
    text-align: left; 
    margin-left: 50px;; 
    margin-top: 20px; 
    font-size: 15px;
    font-family: 'Lucida Sans Regular', sans-serif;
    columns: 100px 3;
    }

ul {
    margin-left: 50px; 
    padding-left: 0;
    margin-top: 5px;
}

ul li {
    font-size: 14px;
    margin-bottom: 8px; 
}

ul li a {
    color: #294fda;
    text-decoration: none; 
}

ul li a:hover {
    text-decoration: underline;
}

/*Footer Styling*/

.footer-container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  height: 100%;
  width: 100%;
  box-sizing: border-box;
  background-color:rgb(145, 133, 133)
  }
        
        .icon-container {
            bottom: 60px;              
            gap: 10px;    
            align-items: center;   
            padding-bottom: 20px;    
            margin-bottom: 20px;
            margin-top: 10px;   
        }

    .fa {
        font-size: 100px;
        text-align: center;
        text-decoration: none;
        margin-right: 10px; 
        }

.fa:hover {
    opacity: 0.7;
}

.fa-facebook {
  color: rgb(6, 0, 0);
}

.fa-instagram {
  color: rgb(6, 0, 0);
}

.fa-envelope {
    color: rgb(6,0,0);  
}

@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}

@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}

</style>
</head>

<!--END OF STYLE-->

<body>
<header>

  <!-- NAVIGATION-->
  
          <div class="topnav-container">
              <div class="topnav">
                      <img src="logofinalna.png" alt="Website Logo">
                  <div class="nav-links">
                      <a href="/.html/website.html">Home</a>
                      <a href="#news">Topics</a>
                      <a href="/.html/about.html">About Us</a>
                      <a class="active" href="/.html/contact.html">Contact Us</a>
                  </div>
              </div>
          </div>
</header>

<!--CONTACT CONTAINER-->

<div class="container">
    <section id="contact-us">
        <h1>Contact Us</h1>
        <p><b>If you have any questions, feel free to reach out to us:</b></p>
        
        <p2>
        <ul>
            <li><strong>Email: </strong><a href="https://mail.google.com/mail/u/2/?view=cm&fs=1&to=joycelodana.llorera24@bicol-u.edu.ph">joycelodana.llorera24@bicol-u.edu.ph</a></li>
            <li><strong>Phone: </strong>+63 968 349 3378</li>
            <li><strong>Address: </strong>Legazpi City, Albay </li>
        </ul>
        </p2>

        <h2>Follow Us on Social Media</h2>

        <p class="p3">Facebook:</p>
        <ul>
            <li><a href="https://www.facebook.com/lovelyjoy.kelly?mibextid=ZbWKwL">Lovely Kelly</a></li>
            <li><a href="https://www.facebook.com/share/19qdRu43pS/?mibextid=LQQJ4d">Joyce Llorera</a></li>
            <li><a href="https://www.facebook.com/elen.jean.lolo.2024?mibextid=ZbWKwL">Elen Jean Lolo</a></li>
            <li><a href="https://www.facebook.com/jessa.mancera.54?mibextid=ZbWKwL">Jessa Mancera</a></li>
        </ul>

        <p class="p3">Instagram:</p>
        <ul>
            <li><a href="https://www.instagram.com/ellovyyyy?igsh=MW8yeWRrMzZ2ZGowOA==">Lovely Kelly</a></li>
            <li><a href="https://www.instagram.com/joyce_e4e?igsh=enNtNmY0cmN2YXMw">Joyce Llorera</a></li>
        </ul>
 
    </section>
</div>

<!-- FOOTER -->
    
<footer>
    <div class="footer-container">
    <p style="color:rgb(179, 0, 0)">&copy; 2024. Eye of the Storm. All rights reserved.</p>

    <div class="icon-container">
    <!--FACEBOOK ICON-->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <a class="fa fa-facebook" href="https://www.facebook.com/share/19qdRu43pS/?mibextid=LQQJ4d" 
    style="font-size:30px;"></a>

    <!--IG ICON-->
    <a class="fa fa-instagram" href="https://www.instagram.com/ellovyyyy?igsh=MW8yeWRrMzZ2ZGowOA==" style="font-size:30px;"></a>
    
     <!--EMAIL ICON-->
    <a class="fa fa-envelope" href="https://mail.google.com/mail/u/2/?view=cm&fs=1&to=joycelodana.llorera24@bicol-u.edu.ph" style="font-size:30px;"></a>

    </div>

</footer>
</body>
</html>