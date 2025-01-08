<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flashing Splash Screen</title> 
    <style>
        #splash-screen {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: black;
            color: white; 
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 100;
            font-size: 5em; 
        }
body {
            background-color: lightgray;
            margin: 0;
            font-family: Arial, sans-serif;
        }
#sidebar {
        width: 250px; 
        height:100%;
        background-color: black;
        position: fixed;
        top:0;   
        left:0;
         color: white; 
        padding-top:10px;  
        padding-left:10px;
        box-sizing: border-box;       
        }
  #sidebar a {
       color: white;
       text-decoration: none;
       display: block;
       margin: 10px 0; 
       font-size: 1.5em;
       }            
 .image-text-container  {
        display: flex; 
       flex-direction: row;
        align-items: center; 
        justify-content: space-between;
        margin: 20px;
        margin-left: 270px; 
        }
  .image-text-container img {
            width: 300px !important  ;  
            height: 300px !important ; 
            border-radius: 50%;
            object-fit: cover;
            margin-right: 20px; 
            margin-left: 20px;
        }
.text-content {
        font-size: 18px;
            font-family: Arial, sans-serif;
            max-width:45%;
            text-align: center;
        }
   
 @media(min-width: 600px) {
    #sidebar {
    width:250px;
    position: fixed;
    height: 100%;
    }
 
 .image-text-container img {
    width:120px;
    height:120px;
    }
 
 .image-text-container {
    flex-direction: row;
    margin-left: 270px;
    }
  
  .text-content{
    text-align: center;
    font-size:16px;
    margin:10px;
    }
  }
   @media(max-width: 600px) {
            body {
            display: flex;
             flex-direction: column; 
            margin-left: 0;
            }

   #sidebar {
              width: 100%;
              position: relative; 
               height: auto;
              padding: 10px;
             box-sizing: border-box;
            }

 .image-text-container {
                flex-direction: column;
                margin-left: 0; 
            }

 .image-text-container img {
                width: 100px;
                height: 100px;
            }

 .text-content {
                font-size: 14px;
                text-align: center;
            }
    }
    
    
    
    
    
    
    
    
    
    
    
 </style>
</head>
<body>
    <div id="splash-screen">Hello World!</div> 
   
  <script>
        setTimeout(function() {
            document.getElementById('splash-screen').style.display = 'none';
        }, 3000); 
    </script>

 <div id="sidebar">
    <a href = "https://linkedin.com/in/william-s-4120a0254" target="_blank"> Check out my LinkedIn Profile! </a>
    <a href = "https://docs.google.com/document/d/1hT3L5L15tXU9I19EtVc4c99L4t3DAc9u/edit?usp=sharing&ouid=101206748234661541234&rtpof=true&sd=true" target="_blank"> Link to my resume! </a>
    <a href = "https://github.com/Wls170?tab=repositories" target= "_blank"> Projects </a>
        </div>
   
   <p style="font-size: 20px;"> Thank you for taking the time to visit my website! I hope you find everything you were looking for. 
    Feel free to explore more about my projects (this is my first), experiences, and connect with me. If you have any questions 
    or would like to collaborate, don't hesitate to reach out. Your feedback and support are greatly appreciated! </p>

<div class="image-text-container">
    <div class = "text-content">
      <h2> Skills: </h2>
        <p><b> Effective Communication </b> </p>
        <p><b> Microsoft Products  </b> </p>
        <p><b> Leadership  </b> </p>
        <p><b> Python  </b> </p>
    </div>
    
<div class = "image-text-container">
    <img src="https://scontent.fosu2-1.fna.fbcdn.net/v/t39.30808-6/363440628_10231263865289524_1224367189268874357_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=833d8c&_nc_ohc=OrEK-w6nDWcQ7kNvgFWSvE5&_nc_zt=23&_nc_ht=scontent.fosu2-1.fna&_nc_gid=ASZxaYnT2GLOsh2-NM6-scY&oh=00_AYBEogK94jrBQBqG0QVkIsKc4fV7N5HbAL74oYjNAr5y0A&oe=677F912D" alt="WillStearn"> 
 <div class= "text-content">
    <h2> Details: </h2>
<p><b> Name: William Stearn </b> </p>
<p><b> Age: 35  </b></p>
<p><b> Location: Barberton, Ohio </b></p>
<p><b> Email: Wls170@icloud.com </b></p>
    </div>
</div>      
   
    <h3> About me: </h3>
    <p style="font-size: 22px;"> Currently I work full-time as a Production Supervisor at a Synthomer. Synthomer supplies highly specialized polymers to multiple industries worldwide. I have been with them since 2018 starting from an entry level worker and progressively working my way up to supervisor. I am also pursuing my BS in Computer Science at Southern New Hampshire University (SNHU). I am taking classes geared towards Software Engineering with an expected completion date of early 2027. In  my free time I enjoy spending time with my family, practicing my coding skill, checking out new spots around town and gaming. </p>




</body>

</html>
