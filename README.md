<!DOCTYPE html>
<html lang="en">
    
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>dash loading animation | ahelpme_coder</title>
    <style>
        /* Global Styles */

        * {
          box-sizing: border-box;
          margin: 0;
          padding: 0;
        }

        body {
          font-family: Arial, sans-serif;
          background-color: #f0f0f0;
        }

        .container {
          width: 100px;
          height: 100px;
          position: relative;
          margin: 40px auto;
        }

        .dash {
          width: 20px;
          height: 20px;
          background-color: #333;
          border-radius: 50%;
          position: absolute;
          top: 40px;
          left: 40px;
          animation: dash 2s linear infinite;
        }

        .uno {
          transform: rotate(0deg);
        }

        .dos {
          transform: rotate(90deg);
        }

        .tres {
          transform: rotate(180deg);
        }

        .cuatro {
          transform: rotate(270deg);
        }

        @keyframes dash {
          0% {
            transform: scale(1);
          }
          50% {
            transform: scale(1.5);
          }
          100% {
            transform: scale(1);
          }
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="dash uno"></div>
        <div class="dash dos"></div>
        <div class="dash tres"></div>
        <div class="dash cuatro"></div>
    </div>
</body>
</html>
