<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="utf-8">

    <meta name="robots" content="noindex, nofollow">



    <title>SMA NEGERI 2 BOYOLALI </title>

<link rel="icon" type="image/png" sizes="16x16" href="logo.png">

      <meta name="viewport" content="width=device-width, initial-scale=1">

    <link href="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">

    <link href="css/login.css" rel="stylesheet" id="bootstrap-css">

    <script src="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>

   <style>

   .container-login100 {

   background-image: radial-gradient( circle farthest-corner at 10% 20%,  rgba(14,174,87,1) 0%, rgba(12,116,117,1) 90% );   }.login100-form-btn {

    font-family: Montserrat-Bold;

    font-size: 15px;

    line-height: 1.5;

    color: #fff;

    text-transform: uppercase;

    width: 100%;

    height: 50px;

    border-radius: 25px;

    background: #FFC107;

    display: -webkit-box;

    display: -webkit-flex;

    display: -moz-box;

    display: -ms-flexbox;

    display: flex;

    justify-content: center;

    align-items: center;

    padding: 0 25px;

    -webkit-transition: all 0.4s;

    -o-transition: all 0.4s;

    -moz-transition: all 0.4s;

    transition: all 0.4s;

}

.input100 {

    font-family: Poppins-Medium;

    font-size: 15px;

    line-height: 1.5;

    color: #666666;

    display: block;

    width: 100%;

    background: #ffffff;

    height: 50px;

    border-radius: 25px;

    padding: 0 30px 0 68px;

}



   </style>

</head>

<body>

    <div class="limiter">

		<div class="container-login100">

	

<form class="form-signin" method="post" action="inc/proses">

    						<span class="login100-form-title" style="color:#fff">

										<img src="logo.png" width="150px"><br>



					PEMBELAJARAN ONLINE <br> SMA NEGERI 2 BOYOLALI 					</span>



					<div class="wrap-input100 validate-input" data-validate = "Valid email is required: ex@abc.xyz">

						<input class="input100" type="text" name="username" placeholder="Username" required>

						<span class="focus-input100"></span>

						<span class="symbol-input100">

							<i class="fa fa-user" aria-hidden="true"></i>

						</span>

					</div>



					<div class="wrap-input100 validate-input" data-validate = "Password is required">

					<span toggle="#password-field" class="fa fa-fw fa-eye field-icon toggle-password" style="margin-left: 246px;

    margin-top: 15px;

    position: absolute;"></span>



						<input class="input100" type="password" id="password-field" name="password" placeholder="Password" required>



						<span class="focus-input100"></span>

						<span class="symbol-input100">

							<i class="fa fa-lock" aria-hidden="true"></i>

						</span>

					</div>



					<div class="container-login100-form-btn">

						<button class="login100-form-btn">

							Login

						</button>

					</div>



				

					

				</form>

			</div>

		</div>

	</div>

	

</body>

</html>

<script src="plugins/jquery/jquery.min.js"></script>



      <script>

	$(".toggle-password").click(function() {

  $(this).toggleClass("fa-eye fa-eye-slash");

  var input = $($(this).attr("toggle"));

  if (input.attr("type") == "password") {

    input.attr("type", "text");

  } else {

    input.attr("type", "password");

  }

});

window.setTimeout(function() {

    $(".alert").fadeTo(500, 0).slideUp(500, function(){

        $(this).remove(); 

    });

}, 5000);



</script>


 
