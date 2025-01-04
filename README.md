
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blinking Text</title>
    <style>
        
        @keyframes blink {
            0% { opacity: 1; }
            50% { opacity: 0; }
            100% { opacity: 1; }
        }

        /* Apply the animation to the blinking text */
        .blink {
            animation: blink 1s infinite; /* 1 second duration, infinite loop */
        }
    </style>
</head>
<body>

    <h1 class="blink"> Hello World! </h1>

</body>
</html>
