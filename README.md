<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
      *{
    padding: 0px;
    margin: 0px;
    box-sizing: border-box;
}

#wrapper{
    width: 100vw;
    height: 100vh;
    overflow-x: hidden;
    overflow-y: auto;
}

.container{
    
    height: 100%;
    max-width: 1200px;
    margin: 0px auto;
    padding: 20px;
}
#img{
    height: 10%;
    width: 50%;
    animation-name: tejas;
    animation-timing-function: ease-in;
    animation-duration: 3s;
    animation-iteration-count: infinite;
    animation-fill-mode: backwards;
    display: block;
    width: 50%;
    margin-left: auto;
    margin-right: auto;
}


@keyframes tejas {
    0%{
        transform: scale(1);
    }
    25%{
        transform: scale(1.02);
    }

    50%{
        transform: scale(1.025);
    }

    75%{
        transform: scale(1.02);
    }
    
    100%{
        transform: scale(1);
    }
}
    </style>
</head>
<body>
    <div class="wrapper" id="wrapper">
        <div class="container" id="container">

            <div class="d1" id="d1">
            <h1 align="center">Hi 👋, I'm Tejas Pachgade</h1>
            <h3 align="center">I'm an Electronics Engineer Passionate about Programming and Development.</h3>
            </div>

            <div class="d2" id="d2">
            <img id="img"  alt="Coding" src="http://neodigitech.com/front-end/assets/vb_dotnet/vb-dotnet1.png">
            </div>
           
        </div>
    </div>
</body>
</html>
