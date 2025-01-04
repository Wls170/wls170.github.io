<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text Color and Animation</title>    
    
    <style>
       
        @keyframes blink {
            0% { opacity: 1; }
            50% { opacity: 0; }
            100% { opacity: 1; }
        }

       
        @keyframes scroll {
            0% {
                transform: translateX(100%);
            }
            100% {
                transform: translateX(-100%);
            }
        }

     
        .scroll-blink {
            color: red;
            font-size: 36px;
            white-space: nowrap; 
            animation: blink 1s infinite, scroll 5s linear 0;
        }
    </style>
</head>
<body>
    <h1 class="scroll-blink">Hello World!</h1>

    <img src="https://scontent.fosu2-1.fna.fbcdn.net/v/t39.30808-6/363440628_10231263865289524_1224367189268874357_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=833d8c&_nc_ohc=OrEK-w6nDWcQ7kNvgFWSvE5&_nc_zt=23&_nc_ht=scontent.fosu2-1.fna&_nc_gid=ASZxaYnT2GLOsh2-NM6-scY&oh=00_AYBEogK94jrBQBqG0QVkIsKc4fV7N5HbAL74oYjNAr5y0A&oe=677F912D" alt="WillStearn" width="500" height="500">

    <h2 style="font-size: 15px;">Thanks for visiting! On this website, you can view my resume, learn a little bit more about me, and view projects that I am working on or have completed.</h2>




    <p1> 


</body>

</html>
