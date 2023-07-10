# login-page-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login Page</title>

  <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="center">

      <div class="container">
        <div class="text">
          Login Form
        </div>

        <form action="#">
          <div class="data">
            <label>Email or Phone</label>
            <input type="text" required>
          </div>
          <div class="data">
            <label>Password</label>
            <input type="password" required>
          </div>

          <div class="forgot-pass">
            <a href="#">Forgot Password?</a>
          </div>

          <div class="btn">
            <div class="inner"> 
              <button type="submit">LOGIN</button>
            </div>
          </div>

          <div class="signup-link">
            Not a member? 
            <a href="#">Signup now</a>
          </div>
           </form>

      </div>
    </div>
</body>
</html>
 
@import url('https://fonts.googleapis.com/css?family=Poppins:400,500,600,700&display=swap');
*{
  margin: 0;
  padding: 0;
  outline: none;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}
.center{
  height: 100vh;
  width: 100%;
  background-image: url(wall.jpg);
  background-position: center;
  background-size: cover;
  padding-left: 5%;
  padding-right: 5%;
  box-sizing: border-box;
  position: relative;
}

 .container{
  position:relative;
  top: 20%;
  left: 30%;
  opacity: 0.8;
  background:white;
  width: 410px;
  padding: 30px;
  box-shadow: 0 0 18px rgba(0, 0, 0, 0.904);
  cursor: pointer;
}

.container .text{
  font-size: 35px;
  font-weight: 500;
  text-align: center;
}

.container form{
  margin-top: -20px;
}

.container form .data{
  height: 45px;
  width: 100%;
  margin: 40px 0;
}

form .data label{
  font-size: 18px;
}

form .data input{
  height: 100%;
  width: 100%;
  padding-left: 10px;
  font-size: 17px;
  border: 1px solid silver;
}

form .data input:focus{
  border-color: black;
  border-bottom-width: 1.5px;
}

form .forgot-pass{
  margin-top: -8px;
}

form .forgot-pass a{
  margin-top: -8px;
  color: #0062a3;
  text-decoration: none;
}

form .forgot-pass a:hover{
  text-decoration: underline;
}

form .btn{
  margin: 30px 0;
  height: 45px;
  width: 100%;
  position: relative;
  overflow: hidden;
}

form .btn .inner{
  height: 100%;
  width: 300%;
  position: absolute;
  left: -100%;
  background: rgb(87, 83, 83);
}

form .btn button{
  height: 100%;
  width: 100%;
  background: none;
  border: none;
  color: white;
  font-size: 18px;
  letter-spacing: 1px;
  cursor: pointer;
}

form .signup-link{
  text-align: center;
}
form .signup-link a{
  color: #0062a3;
  text-decoration: none;
}
form .signup-link a:hover{
  text-decoration: underline;
}
