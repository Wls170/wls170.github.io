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
            height: 100%;
            background-color: black;
            position: fixed;
            top: 0;   
            left: 0;
            color: white; 
            padding-top: 10px;  
            padding-left: 10px;
            box-sizing: border-box;       
        }

        #sidebar a {
            color: white;
            text-decoration: none;
            display: block;
            margin: 10px 0; 
            font-size: 1.5em;
        }

        
        .main-container {
            display: flex;
            justify-content: space-between;
            margin-left: 10px;
            margin-top: 30px;
            flex-wrap: wrap; 
        }

      
        .skills-section {
            width: 30%;
            text-align: center;
            margin-bottom: 20px;
        }

        .skills-section h2 {
            font-size: 24px;
        }

        .skills-section p {
            font-size: 18px;
        }

       
        .image-text-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            margin: 20px;
            width: 30%;
            text-align: center;
        }

        .image-text-container img {
            width: 300px !important; 
            height: 300px !important;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 20px;
        }

     
        .details-section {
            width: 30%;
            text-align: center;
            margin-bottom: 20px;
        }

        .details-section h2 {
            font-size: 24px;
        }

        .details-section p {
            font-size: 18px;
        }

        
        @media (min-width: 600px) {
               .image-text-container img {
                width: 120px;
                height: 120px;
            }

           
            .main-container {
                flex-wrap: nowrap;
            }
        }

        @media (max-width: 600px) {
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

            .main-container {
                flex-direction: column; /* Stack sections vertically */
                margin-left: 0;
            }

            .skills-section, .image-text-container, .details-section {
                width: 100%;
                text-align: center;
            }

            .image-text-container img {
                width: 100px;
                height: 100px;
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
        <a href="https://linkedin.com/in/william-s-4120a0254" target="_blank">Check out my LinkedIn Profile!</a>
        <a href="https://docs.google.com/document/d/1hT3L5L15tXU9I19EtVc4c99L4t3DAc9u/edit?usp=sharing&ouid=101206748234661541234&rtpof=true&sd=true" target="_blank">Link to my resume!</a>
        <a href="https://github.com/Wls170?tab=repositories" target="_blank">Projects</a>
    </div>

   
    <p style="font-size: 20px;">Thank you for taking the time to visit my website! I hope you find everything you were looking for. Feel free to explore more about my projects (this is my first), experiences, and connect with me. If you have any questions or would like to collaborate, don't hesitate to reach out. Your feedback and support are greatly appreciated!</p>

    
    <div class="main-container">
            <div class="skills-section">
            <h2>Skills:</h2>
            <p><b>Effective Communication</b></p>
            <p><b>Microsoft Products</b></p>
            <p><b>Leadership</b></p>
            <p><b>Python</b></p>
        </div>

        
        <div class="image-text-container">
            <!-- Replace this URL with your actual image URL -->
            <img src="https://www.facebook.com/photo/?fbid=10229830880185792&set=a.1557853795875" alt="WillStearn"> 
        </div>

       
        <div class="details-section">
            <h2>Details:</h2>
            <p><b>Name: William Stearn</b></p>
            <p><b>Age: 35</b></p>
            <p><b>Location: Barberton, Ohio</b></p>
            <p><b>Email: Wls170@icloud.com</b></p>
        </div>
    </div>     

  
    <h3>About me:</h3>
    <p style="font-size: 22px;">Currently I work full-time as a Production Supervisor at Synthomer. Synthomer supplies highly specialized polymers to multiple industries worldwide. I have been with them since 2018 starting from an entry-level worker and progressively working my way up to supervisor. I am also pursuing my BS in Computer Science at Southern New Hampshire University (SNHU). I am taking classes geared towards Software Engineering with an expected completion date of early 2027. In my free time, I enjoy spending time with my family, practicing my coding skills, checking out new spots around town, and gaming.</p>
</body>
</html>


