# Customised-login-page
<!-- A customised login page using HTML, CSS, Javascript -->

<!-- HTML Code -->
<html>
    <head>
        <title>Animated Login Form</title>
        <link rel="stylesheet" href="style.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    </head>
    <body>
        <div class="container">
            <div class="dog">
                <div class="ear-left"></div>
                <div class="ear-right"></div>
                <div class="eye-left">
                </div>
                <div id="eye-hide-left" class="eye-hide-left">
                </div>
                <div class="eye-right">
                </div>
                <div id="eye-hide-right" class="eye-hide-right">
                </div>
                <div class="nose">
                </div>
                <div class="mouth">
                </div>
            </div>
                <div class="hand-left">
                    <div class="h1-left"></div>
                    <div class="h2-left"></div>
                    <div class="h3-left"></div>
                </div>
                <div class="hand-right">
                    <div class="h1-right"></div>
                    <div class="h2-right"></div>
                    <div class="h3-right"></div>
                </div>
            <div class="form">
                <input placeholder="User Name">
                <input id="pwd" type="password" placeholder="Password">
                <input id="btn" type="submit" value="Login">
                <div class="orDiv">
                    <hr>
                     <b class="txt">Or</b>
                    <hr>
                </div>
                <div class="btns">
                    <i class="rotated_btn fa fa-facebook-f	"></i>
                    <i class="rotated_btn fa fa-twitter	"></i>
                    <i class="rotated_btn fa fa-instagram	"></i>
                    <i class="rotated_btn fa fa-google	"></i>
                </div>
            </div>
        </div>
        <script src="https://code.jquery.com/jquery-3.5.0.js" ></script>
        <script src="script.js"></script>
    </body>
</html>
