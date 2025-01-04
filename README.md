<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text Color and Animation</title> <!-- Only one <title> tag should be here -->
    <style>
        /* Define the blink animation */
        @keyframes blink {
            0% { opacity: 1; }
            50% { opacity: 0; }
            100% { opacity: 1; }
        }

        /* Define the scroll animation */
        @keyframes scroll {
            0% {
                transform: translateX(100%);
            }
            100% {
                transform: translateX(-50%);
            }
        }

        /* Set the background color for the entire page */
        body {
            background-color: lightgray; /* Background color applied to the body */
            margin: 0; /* Remove any default margin */
            font-family: Arial, sans-serif; /* Optional: Make the text more readable */
        }

        /* Apply both scrolling and blinking animation to the text */
        .scroll-blink {
            color: red;
            font-size: 36px;
            white-space: nowrap; /* Prevents text from wrapping */
            animation: blink 1s infinite, scroll 5s linear 1; /* Apply both animations */
        }
    </style>
</head>
<body>

    <!-- Blinking and scrolling text -->
    <h1 class="scroll-blink">Hello World!</h1>

    <!-- An image with a set width and height -->
    <img src="https://scontent.fosu2-1.fna.fbcdn.net/v/t39.30808-6/363440628_10231263865289524_1224367189268874357_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=833d8c&_nc_ohc=OrEK-w6nDWcQ7kNvgFWSvE5&_nc_zt=23&_nc_ht=scontent.fosu2-1.fna&_nc_gid=ASZxaYnT2GLOsh2-NM6-scY&oh=00_AYBEogK94jrBQBqG0QVkIsKc4fV7N5HbAL74oYjNAr5y0A&oe=677F912D" alt="WillStearn" width="500" height="500">

    <!-- Paragraphs with text -->
    <p style="font-size: 20px;">Thanks for visiting! On this website, you can view my resume, learn a little bit more about me, and view projects that I am working on or have completed.</p>

    <p style="font-size: 20px;">Currently I work full-time as a production supervisor at a performance chemicals company. I am also actively pursuing my BS in Computer Science with a concentration in Software Engineering. I want to create websites and apps to make people's jobs and lives better. I enjoy learning how things work and building them to be better.</p>

</body>
</html>



</body>

</html>
