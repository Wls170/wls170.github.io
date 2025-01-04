
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
   <h2> Thanks for visiting!.  I made this website to showcase my resume, an about me section, projects and for more experience with html and css </h2>
   
</body>
</html>
