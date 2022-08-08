# Quora-Login-Page
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href='https://fonts.googleapis.com/css2?family=Abhaya+Libre:wght@800&family=Edu+VIC+WA+NT+Beginner&display=swap' rel="stylesheet">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Abhaya+Libre:wght@800&family=Edu+VIC+WA+NT+Beginner&family=Roboto&display=swap">
    <title>Quora Login Page</title>
</head>
<style>
    body {
       background:url('images/quora\ artwork.jpg') no-repeat center center/cover;
    }
    
    .parent{
        
        width: 750;
        height: 500px;
        background-color: white;
        margin-left: 420;
        margin-top: 110;
        border-radius: 3px;
    }
    .title{
        color: rgb(185, 43, 39);
        font-size: 65px;
        font-family: 'Abhaya Libre', serif;
        position: absolute;
        left: 730px;
        top: 100px ;
    }
    .quote{
        font-weight: 1000;
        position: absolute;
        left: 610;
        top: 210;
       color: #555;
       font-family: 'Roboto', sans-serif;
    }
    .tnc{
        display: block;
        color: rgb(157, 155, 155);
        font-family: 'Roboto', sans-serif;
        font-size: 13px;
    }
    #first {
        position: absolute;
        left: 455px;
        top: 300px;
        
    }
    #second {
        position: absolute;
        left: 455px;
        top: 315px; 
        
    }
    
    .login{
        left: 850;
        position: absolute;
        top: 290;
        color: black;
        font-family: 'Roboto', sans-serif;
    }
    .rule{
        width: 300px;
    }
    .google {
        width: 330px;
        height: 40px;
        position: absolute;
        left: 455px;
        top: 355px;
        background-color: transparent;
        margin: 0%;
        border: 1px solid grey;
        border-radius: 3px;
        font-size: 17px;
        padding: 8px;
        cursor: pointer;
    }
    .google:hover{
        background-color: rgb(241, 240, 240);;
    }
    .google a {
        color: #ffff;
        text-decoration: none;
    }
    .facebook {
        width: 330px;
        height: 40px;
        position: absolute;
        left: 455px;
        top: 395px;
        background-color: transparent;
        margin: 0%;
        border: 1px solid grey;
        border-radius: 3px;
        font-size: 17px;
        display: block;
        margin-top: 7px;
        padding: 8px;
        cursor: pointer;
    }
    .facebook:hover{
        background-color: rgb(241, 240, 240);;
    }
    .facebook a {
        color: #ffff;
        text-decoration: none;
    }
    .signup{
        color: #787878;
        font-weight:600;
        background-color: transparent;
        border: none;
        position: absolute;
        left: 455px;
        top: 450px;
        width: 330px;
        height: 30px;
        font-size: 12.5;
    }
    .signup:hover{
        background-color: rgb(241, 240, 240);
        border-radius: 30px;
        
    }
   
    #Email {
        position: absolute;
        left: 850px;
        top: 360px;
        width: 300px;
        height: 40px;
        padding: 8px;
        
    }
    #Email:hover{
        border: 1px solid blue;
        border-radius: 2px;
    }
    
    .email {
        position: absolute;
        left: 850px;
        top: 340px;
        font-weight: bold;
        font-family:'Roboto', sans-serif;
        font-size: small;
        cursor: default;
    }
    .pass {
        position: absolute;
        left: 850px;
        top: 415px;
        font-weight: bold;
        font-family:'Roboto', sans-serif;
        font-size: small;
        cursor: default;
    }
    #passId {
        position: absolute;
        left: 850px;
        top: 435px;
        width: 300px;
        height: 40px;
        padding: 8px;
        
    }
    #passId:hover{
        border: 1px solid blue;
        border-radius: 2px;
    }
    .urltnc {
        color: #ffff;
        text-decoration: none;
    }
    .urlprivacy{
        color: #ffff;
        text-decoration: none;
    }
    .urltnc:hover{
        color:rgb(99, 95, 178);
        text-decoration: underline;
    }
    .urlprivacy:hover{
        color:rgb(99, 95, 178);
        text-decoration: underline;
    }
    .forgot{
        position: absolute;
        left: 845;
        top: 510;
        color: rgb(157, 155, 155);
        background-color: transparent;
        border: 0ch;
        cursor: pointer;
    }
    .forgot:hover{
        color: rgb(157, 155, 155);
        text-decoration: underline;
    }
    .loginButton{
        position: absolute;
        height: 40px;
        width: 75px;
        top: 510;
        left: 1075;
        background-color: rgb(151, 180, 255);
        border: 0ch;
        border-radius: 20px;
        color: white;
        font-weight: bold;

    }
    .imagea {
        height: 20px;
        width: 20px;
        position: absolute;
        top: 364px;
        left: 470;
        cursor: pointer;
    }
    .imageb {
        height: 30px;
        width: 30px;
        position: absolute;
        top: 406;
        left: 465;
        cursor: pointer;

}
    .ruleb{
        width: 500px;
    }
    
</style>
<script lang="javascript" type="text/javascript">
        function loginColorChange() {
            document.getElementById('colorChange').style.backgroundColor= "rgb(46,105,255)";
            document.getElementById('colorChange').style.cursor="pointer";
        }
</script>
<script lang="javascript" type="text/javascript">
        function fn() {
            document.getElementById('Email').style.borderColor = "blue";
            document.getElementById('passId').style.borderColor = "blue";
        }
</script>

<body>
       
        
        <div class="parent">
        <h1 class="title">Quora</h1>
        <p class="quote">A place to share knowledge and better understand the world</p>
        <span class="tnc" id="first">By continuing you indicate that you agree to </span>
        <span class="tnc" id="second"> Quora’s <span> <a class="urltnc" href="https://www.quora.com/about/tos" target="_blank" style="color:rgb(99, 95, 178);">Terms of Service</a> </span> and <span > <a class="urlprivacy" href="https://www.quora.com/about/privacy" target="_blank" style="color:rgb(99, 95, 178);">Privacy Policy</a> </span>.  </span>
        <div class="leftButton">
            <button class="google"> <a href="https://accounts.google.com/o/oauth2/v2/auth/oauthchooseaccount?access_type=online&approval_prompt=auto&client_id=917071888555.apps.googleusercontent.com&redirect_uri=https%3A%2F%2Fwww.quora.com%2Fgoogle_%2Fcallback&response_type=code&scope=email%20profile&state=eyJwZXJtcyI6ICJub19jb250YWN0cyIsICJjc3JmIjogIjQxMGIzOWM3ZDVmMDhhMTAyYjQ0Yjg5MmYxNTY0MGY5IiwgInBsYXRmb3JtIjogImRlc2t0b3AiLCAidGFyZ2V0IjogInNpZ251cCJ9&flowName=GeneralOAuthFlow" style="color:#000000d4; position: absolute;
            left: 46; top: 9;">Continue with Google</a> </button>
            <button class="facebook"> <a href="https://www.facebook.com/login.php?skip_api_login=1&api_key=136609459636&kid_directed_site=0&app_id=136609459636&signed_next=1&next=https%3A%2F%2Fwww.facebook.com%2Fv13.0%2Fdialog%2Foauth%3Fclient_id%3D136609459636%26redirect_uri%3Dhttps%253A%252F%252Fwww.quora.com%252Ffacebook%252Fcallback%26response_type%3Dcode%26scope%3Demail%26state%3DeyJwZXJtcyI6ICJlbWFpbCIsICJjc3JmIjogIjQxMGIzOWM3ZDVmMDhhMTAyYjQ0Yjg5MmYxNTY0MGY5IiwgInBsYXRmb3JtIjogImRlc2t0b3AiLCAidGFyZ2V0IjogInNpZ251cCJ9%26ret%3Dlogin%26fbapp_pres%3D0%26logger_id%3D662a4d7e-d9e8-4cdc-83d7-3f250ff2b34e%26tp%3Dunspecified&cancel_url=https%3A%2F%2Fwww.quora.com%2Ffacebook%2Fcallback%3Ferror%3Daccess_denied%26error_code%3D200%26error_description%3DPermissions%2Berror%26error_reason%3Duser_denied%26state%3DeyJwZXJtcyI6ICJlbWFpbCIsICJjc3JmIjogIjQxMGIzOWM3ZDVmMDhhMTAyYjQ0Yjg5MmYxNTY0MGY5IiwgInBsYXRmb3JtIjogImRlc2t0b3AiLCAidGFyZ2V0IjogInNpZ251cCJ9%23_%3D_&display=page&locale=en_GB&pl_dbl=0" style="color:#000000d4; position: absolute; left: 46; top: 9px;">Continue with Facebook</a></button>
            <button class="signup" onclick="">Sign up with email</button>
            
        </div>
        <div>
            <span class="login">Login <hr class="rule"></span>
            <span class="email">Email</span>
            <label for="Email"></label>
            <input type="email" id="Email" placeholder="Your email">
            <span class="pass">Password</span>
            <label for="passId"></label>
            <input type="password" name="" id="passId" placeholder="Your password" oninput="loginColorChange()">
        </div>
        <div>
            <button class="forgot">Forgot password?</button>
            <button class="loginButton" id="colorChange">Login </button>
            
        </div>
        <div>
            <img src="images/google.jpg" alt="" class="imagea">
            <img src="images/facebook-icon.jpg" alt="" class="imageb">
        </div>
        
        </div>
        
    
</body>
</html>
