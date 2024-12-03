<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE-edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<!-- font awesome cdn link -->
<link rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
<!-- custom css file link -->
<link rel="stylesheet" href="login.css">
<title>Login & Register Form</title>
</head>
<body>
<div class="wrapper">
<div class="form-box login">
<h2>Login</h2>
<form action="#">
<div class="input-box">
<span class="icon"><i class="fas fa-user"></i></span>
<input type="text" required>
<label>Username</label>
</div>
<div class="input-box">
<span class="icon"><i class="fas fa-lock"></i></span>
<input type="password" required>
<label>Password</label>
</div>
<div class="remember-forgot">
<label><input type="checkbox"> Remember me</label>
</div>
<a href="index1.html" class="btn">Login</a>
<div class="login-register">
<p>Don't have an account?<a href="#" class="register-link"> Register</a></p>
</div>
</form>
</div>
<div class="form-box register">
<h2>Registration</h2>
<form action="#">
  <div class="input-box">
<span class="icon"><i class="fas fa-user"></i></span>
<input type="text" required>
<label>Username</label>
</div>
<div class="input-box">
<span class="icon"><i class="fas fa-envelope"></i></span>
<input type="email" required>
<label>Email</label>
</div>
<div class="input-box">
<span class="icon"><i class="fas fa-lock"></i></span>
<input type="password" required>
<label>Password</label>
</div>
<div class="input-box">
<span class="icon"><i class="fas fa-lock"></i></span>
<input type="password" required>
<label>Confirm password</label>
</div>
<div class="remember-forgot">
<label><input type="checkbox"> I agree to the terms and conditions</label>
</div>
<a href="index1.html" class="btn">Register</a>
<div class="login-register">
<p>Already have an account?<a href="#" class="login-link"> Login</a></p>
</div>
</form>
</div>
</div>
<!-- custom js file link -->
<script src="login.js"></script>
</body>
</html>
