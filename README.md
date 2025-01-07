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
    #circle-crop {
    width: 200px;
    height: 200px;
    overflow: hidden;
   border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
        }
      #circle-crop img {
    width: 100%;
    height:100%;
    object-fit: cover;
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
    <a href = "#"> Projects </a>
    <a href = "#"> Contact </a>
     </div>
 

<div id = "circle-crop">
    <img src="https://scontent.fosu2-1.fna.fbcdn.net/v/t39.30808-6/363440628_10231263865289524_1224367189268874357_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=833d8c&_nc_ohc=OrEK-w6nDWcQ7kNvgFWSvE5&_nc_zt=23&_nc_ht=scontent.fosu2-1.fna&_nc_gid=ASZxaYnT2GLOsh2-NM6-scY&oh=00_AYBEogK94jrBQBqG0QVkIsKc4fV7N5HbAL74oYjNAr5y0A&oe=677F912D" alt="WillStearn">
 
    <p style="font-size: 20px;">Thanks for visiting! On this website, you can view my resume, learn a little bit more about me, view projects that I am working on (this is my first!) or have completed, check out my LinkedIn and find my contact info! </p>

    <p style="font-size: 22px;"> Currently I work full-time as a Production Supervisor at a Synthomer. Synthomer supplies highly specialized polymers to multiple industries worldwide. I have been with them since 2018 starting from an entry level worker and progressively working my way up to supervisor. I am also pursuing my BS in Computer Science at Southern New Hampshire University (SNHU). I am taking classes geared towards Software Engineering with an expected completion date of early 2027. In  my free time I enjoy spending time with my family, practicing my coding skill, checking out new spots around town and gaming. </p>




</body>

</html>
