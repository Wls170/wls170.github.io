
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blinking Red Text</title>
    <title> Text Color</title>    
 
    <style>
        
        @keyframes blink {
            0% { opacity: 1; }
            50% { opacity: 0; }
            100% { opacity: 1; }
        }

        /* Apply the animation to the blinking text */
        .blink {
            color: red;
            animation: blink 1s infinite; /* 1 second duration, infinite loop */
        }

       
        
    
    
    
    </style>
</head>
<body>

    <h1 class="blink"> Hello World! </h1>
   <h2 style="font-zixe:  20 px;"> Thanks for visiting!.  On this page you can view my resume, learn a little bit more about me and view projects that I am working on or that I have completed.</h2>
</body>
</html>
