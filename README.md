<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Winter Page</title>
    <style>
        body {
            text-align: center;
        }

        img {
            max-width: 100%;
            height: auto;
            transition: transform 0.5s ease-in-out;
        }

        img:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <h1>Welcome to the Winter Wonderland!</h1>
    <p>Hover over the image to see the magic happen!</p>
    
    <img id="winterImage" src="https://multiple-images-type.s3.amazonaws.com/6e12ae8667c8817234d8fbe4fe145c4e.png" alt="Winter Scene">

    <script>
        // JavaScript for changing the image source on click
        document.getElementById('winterImage').addEventListener('click', function() {
            // Change the image source to another winter image
            this.src = 'https://multiple-images-type.s3.amazonaws.com/another-winter-image.png';
        });
    </script>
</body>
</html>
