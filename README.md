<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=i, initial-scale=1.0" />
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" />
  <script>
    https; //cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js
  </script>

  <title>Document</title>
  <style>
   back {
      width: 100%;
      height: 100%;
    }

nav {
  background-color: #333;
  color: white;
  padding: 25px 0;
  text-align: center; /* Align content in the center */
}

.container {
  max-width: 1200px;
  margin: 0 auto; /* Center the container horizontally */
  display: flex;
  justify-content: center; /* Center the flex items horizontally */
  align-items: center; /* Center the flex items vertically */
}



.nav-links {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

.nav-links li {
  display: inline;
  margin-left: 20px;
}

.nav-links li a {
  color: white;
  text-decoration: none;
  font-size: 18px;
}

.nav-links li a:hover {
  text-decoration: underline;
}
.profile-circle {
  width: 200px; /* Increase the size of the circle */
  height: 200px; /* Increase the size of the circle */
  border-radius: 50%; /* Creates a circular shape */
  overflow: hidden; /* Hide overflow content */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Adds a shadow effect */
  margin-bottom: 20px; /* Add spacing between the circle and other elements */
  display: flex; /* Use flexbox for centering */
  justify-content: center; /* Center horizontally */
  align-items: center; /* Center vertically */
}

.profile-circle img {
  width: auto; /* Set width to auto */
  height: 100%; /* Make the height fill the circle */
  display: block; /* Remove default whitespace */
  margin: 0 auto; /* Center the image horizontally */
}












    button {
      width: 3vh;
    }

    .back {
      width: 100%;
      height: 98vh;
    }

    .two {
      width: 100%;
      height: 98vh;
    }

    .logo {
      height: 40px;
      width: 100px;
    }

    .greenbox {
      width: 100%;
      height: 58vh;
    }

    .blackbox {
      width: 100%;
      height: 110vh;
    }

    .inblackbox {
      margin-left: 100px;
      margin-right: 100px;
      color: white;
      text-align: center;
    }

    .horizontal-nav {
      display: flex;
      /* Use flexbox for horizontal layout */
      justify-content: center;
      gap: 15px;
      /* Equal spacing between links */

      /* background-color: #f5f5f5; */
      /* border: 1px solid #ccc; Add a rectangular border */
      padding: 20px;
      /* Add padding to create space around the links */
      margin: 10px;
    }

    .inblack {
      color: white;
      text-align: start;
      margin-left: 40px;
      margin-right: 40px;
    }

    /* Style for each navigation link */
    .mynav-link {
      text-align: center;
      padding: 20px;
      /* Add padding to create a clickable area */
      border: 1px solid #ddd;
      /* Add a border around each link */
      text-decoration: none;
      color: white;
      border-radius: 20px;
      gap: 10px;
    }

    .nxtblack {
      background-color: white;
      width: 100%;
      height: 98vh;
      padding: 10px;

    }

    .firstnxtblack {
      text-align: center;
    }

    #pro {
      /* margin-left: 20vh; */
      text-align: center;
      display: flex 1;
      justify-content: center;
      align-items: center;
      gap: 30px;
      margin-top: 15px;
      margin-bottom: 20px;
    }

    .circle {
      /* float: center;
        border: 3px solid;
        border-radius: 115px; */
      width: 100px;
      height: 100px;
      background-color: #3a3a3b;
      /* Set the background color to your desired color */
      border-radius: 50%;
      /* This creates a circular shape */
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      /* Set the text color */
      font-size: 18px;
    }

    .green {
      background-color: rgb(115, 204, 115);
      margin-left: 10%;
      margin-right: 10%;
      width: 80%;
      height: 70vh;
      border-radius: 10px;

    }

    .last {
      width: 100%;
      height: 100vh;

    }

    .blacklast {
      width: 100%;
      height: 40vh;
      background-color: black;
      padding: 10px;
      padding-left: 10%;
      padding-right: 10%;
      color: white;
    }
    .button {
            position: relative;
            display: inline-block;
            padding: 10px 20px;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        /* Style for the hover message */
        .button .hover-message {
            position: absolute;
            top: -30px; 
            left: 50%;
            transform: translateX(-50%);
            background-color: #246429;
            color: #fff;
            padding: 5px;
            border-radius: 4px;
            opacity: 0;
            pointer-events: none; 
            transition: opacity 0.3s;
        }

        
        .button:hover .hover-message {
            opacity: 7;
        }
    

  </style>
</head>

<body>

  <div>
    <div style="background-color: white" class="back" id="home">
      <nav>
        <div class="container">
          <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#contact">Contact</a></li>
          </ul>
        </div>
      </nav>

      <br>
      <div style="margin-top: 2%;" class="green">
        <div class="row">
          <div style="margin-left: 5%; margin-top: 5%;" class="col-md-6">
            <h1 ><span style="color: white;">Hi</span>,There</h1>
            <h1>I AM <span style="color: white;">SACHIN R S</span> </h1>
            <h4>I Am A Web Developer</h4>
            <p style="font-size: 20px; color:white;">"As a web developer fresher, I'm actively pursuing openings in esteemed companies to kick-start my career journey. Ready to apply my skills and learn from experienced professionals in a dynamic environment."</p>
          
            <div class="justify-content-center" id="about">
              <button type="button"  style="background-color: white; color:  rgb(88, 158, 102); margin-left: 100px; margin-top: 60px; width: 200px" class="btn btn btn-lg">
              <bold>  About </bold> 
              </button>
            </div>
          </div>
      
          <div class="col-md-4">
            <div style="display: flex; justify-content: center; align-items: center; height: 100%;">
              <div class="profile-circle">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                </svg>
                
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>


    </div>









<div>

  


   <section id="about">
  <div class="two">
    <h1 style="text-align: center">
      <br />
      <br />
      <br />
      About
     
      <br />
      <br />
      <br />
    </h1>
    <br />
    <div class="row">
      <br />
      <br />
      <div class="col-md-2"></div>
      <div style="background-color: azure" class="col-md-8">
        <div class="justify-content-center">
          <img src="https://cdn1.iconfinder.com/data/icons/books-knowledge/512/hat_student_learn-64.png" alt="" />
          <h4>Get to know me better</h4>
          <div class="row">
            <div class="col-lg-12">
              <p style="font-size: 18px;">
                My name is R S SACHIN, and I'm currently a final year student at Karpagam College of Engineering. I completed my schooling at Vivekam Matric Higher Secondary School. With a passion for web development, I have acquired skills in HTML, CSS, Bootstrap, JavaScript, as well as additional experience with C and Java.
              </p>
              <p style="font-size: 18px;">
                I have pursued online certifications in Java to further enhance my programming skills. Additionally, I gained practical experience through a 2-month internship in web development. During this internship, I worked on real-world projects and collaborated with professionals in the field, solidifying my skills and understanding of web development principles.
              </p>
              <p style="font-size: 18px;">
                Throughout my academic and professional journey, I've remained committed to continuous learning and growth. I'm enthusiastic about leveraging my skills and experiences to contribute meaningfully to innovative projects and further develop my career in web development.
              </p>
            </div>
          </div>
        </div>
      </section>
        </div>
      </div>
     
        <div class="col-md-2"></div>
      </div>
    </div>
</div>
</section>   

    <br />
    <br />
    <br />
    <br />












    
    <br />
    <section id="portfolio"> 
    <div style="text-align: center">
      <h1>
        <span style="color: rgb(115, 204, 115)"><br />Portfolio </span>
      
      </h1>
    </div>
    <br />
    <br />
    <br />
    <div class="container">
  
    <div style="text-align: center;">
     <h4>Projects completed</h4>
     <p>"In the past, I have successfully completed several projects that demonstrate my proficiency in web development. These include:
      E-commerce Template: Developed an e-commerce template .
      Food Blog: Designed and implemented a captivating food blog featuring visually appealing content, interactive features, and user-friendly navigation.
      Cloned Company Website: Successfully replicated a company website during my internship, overcoming challenges and implementing improvements to enhance its functionality and design."</p>

     <div class="col-md-2"></div> 
     </div>
      </div>
      <br />
      <br />
      <br />
      <br />
    </div>
  </section>

    <br><br><br>



<section id="contact">
    
    <div class="blacklast">
      <div>
        <h3 style="text-align: center">

          <div style="text-align: center;">Contact</div> <br>
        </h3>
        <div class="row">
         
          <div style="text-align: center;" class="col-md-4 ">Contact details and other informations
          </div>
          <div  style="text-align: center;" class="col-md-2">Adderss <br>
            198/1,siruthuliavenue,<br>samichettipalayam,<br>coimbatore-641047.
          </div>
          <div  style="text-align: center;" class="col-md-2">phone number and e mail <br>8124793069<br>sachinshuttler2002@gmail.com  </div>
          <div  style="text-align: center; "class="col-md-3">linkedin/url <br>https://www.linkedin.com/in/sachin-r-s-aa9b31234? <br> utm_source=share&utm_campaign=share_via&ut  <br>m_content=profile&utm_medium=android_app</div>
         
        </div>
        <hr>
        <p>Copyright © 2024 sachinportfolio</p>
        <p></p>
      </div>


     
    </div>

  </section>




</body>

</html>
