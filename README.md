# zehrafzm.github.io
<html lang="en">
<head>
    <script src="jquery.js" ></script>
    <link rel="stylesheet" href="me.css">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zehra</title>
</head>
<body >
    <div  style="text-align: center">
        <p style="font-size: 70px ;color: rgb(246, 255, 240) ; " >Hi,</p> 
        <ul >
            <li class="main"><a href="https://github.com/zehrafzm/zehrafzm.github.io/blob/f8bfebfc4ec2478be9859b47c39c6fcbab5b9d87/assets/css/CV%20(7)%20(1).pdf" target="_blank">formal cv (boring***) </a></li>
            <li class="main">See the <a href="illust.html" target="_blank">creations made by Inkspace & Krita</a>  (free Adobe Illustrator & Sketch alternative) </li>
        </ul>  
        wanna leave some note
        <input id="message">
        <p>
            <ul class="message">
                <span id="usersays" ></span>
            </ul>
        </p>
            
    </div>

    
    
    <style>
        body {
            background-image:  url('![butter](https://user-images.githubusercontent.com/105994419/169718296-9f2920f8-985e-478c-873f-c013fcf20e73.png)');
            background-repeat: repeat-x;
            background-size: contain;
        }
    </style>
    <script>
        function UserSays(e) {
            if (e.keyCode == 13) {
                $('#usersays').append('<li>'+ $('#message').val()  +'</li>');
                $('#message').val('');
            }   

        }
        $('#message').keyup(UserSays) ; 
    </script>
</body>
</html>
