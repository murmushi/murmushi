-
<!DOCTYPE html>
<html lang="en">
<head>
<meta http-equiv="content-type" content="text/html; charset=utf-8">
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portal Home | Portal | Hassan Usman Katsina Polytechnic (HUK)</title>
<link rel="icon" type="image/x-icon" href="https://portal.hukpoly.edu.ng/assets/img/favicon.ico">
<meta name="keyword" content="portal, staff, student, login, exams, Hassan Usman Katsina Polytechnic, hukpoly.edu.ng">
<meta name="description" content="Official Staff and Students portal for Hassan Usman Katsina Polytechnic">
<meta name="author" content="Suleiman Umar (www.steadfast.com.ng)">
<link rel="stylesheet" href="https://portal.hukpoly.edu.ng/assets/cdn/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="https://portal.hukpoly.edu.ng/assets/css/Footer-Clean.css">
<link rel="stylesheet" href="https://portal.hukpoly.edu.ng/assets/css/Navigation-Clean1.css">
<link rel="stylesheet" href="https://portal.hukpoly.edu.ng/assets/css/Navigation-with-Button1.css">
<script src="https://portal.hukpoly.edu.ng/assets/cdn/jquery/3.3.1/jquery.min.js"></script>
<script src="https://portal.hukpoly.edu.ng/assets/cdn/jquery/migrate/jquery-migrate-1.4.1.min.js"></script>
<link rel="stylesheet" href="https://portal.hukpoly.edu.ng/assets/cdn/font-awesome/4.7.0/css/font-awesome.min.css"><link rel="stylesheet" href="https://portal.hukpoly.edu.ng/assets/css/Registration-Form-with-Photo.css"><link rel="stylesheet" href="https://portal.hukpoly.edu.ng/assets/cdn/bootstrap-float-label/bs3/bootstrap-float-label.min.css">
<script type="text/javascript" src="https://portal.hukpoly.edu.ng/assets/cdn/jquery-validation/1.17.0/dist/jquery.validation.min.js"></script></head><body><div>
<nav class="navbar navbar-default navigation-clean-button">
<div class="container">
<div class="navbar-header"><a class="navbar-brand navbar-link" href="https://portal.hukpoly.edu.ng/"><img class="img-responsive" src="https://portal.hukpoly.edu.ng/assets/img/logo_w_name_283x53_tablet.png" /></a>
<button class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navcol-1"><span class="sr-only">Toggle navigation</span><span class="icon-bar"></span><span class="icon-bar"></span><span class="icon-bar"></span></button>
</div>
<div class="collapse navbar-collapse" id="navcol-1">
<ul class="nav navbar-nav">
<li role="presentation"><a href="https://portal.hukpoly.edu.ng/instructions" title="Application and Registration Guidelines">Instructions</a></li>
<li role="presentation"><a href="https://portal.hukpoly.edu.ng/apply-indirect" title="UTME Applicants">UTME Application</a></li>
<li role="presentation"><a href="https://portal.hukpoly.edu.ng/apply" title="Create an Account and Start Application">New Application</a></li>
<li role="presentation"><a href="https://portal.hukpoly.edu.ng/applicantLogin" title="Returning Applicant">Continue Application</a></li>
<li role="presentation"><a href="https://portal.hukpoly.edu.ng/register" title="Fresh Registration">Registration</a></li>
<li role="presentation"><a href="https://portal.hukpoly.edu.ng/admission-checker" title="Admitted applicants">Admissions</a></li>
</ul>
<p class="navbar-text navbar-right actions"><a class="btn btn-default action-button" role="button" href="https://portal.hukpoly.edu.ng/">Portal Home</a></p>
</div>
</div>
</nav>
</div> <div class="register-photo">
<div class="form-container">
<div class="image-holder hidden-xs col-md-offset-1 col-lg-offset-1" style="border-radius: 3px; padding-left: 20px; background-repeat: no-repeat; background-image: linear-gradient(rgb(255,255,255),rgb(238,238,238));">
<div class="row">
<h3 class="text-success">Welcome back!</h3>
</div>
</div>
<form action="https://portal.hukpoly.edu.ng/" id="portalLogin" name="portalLogin" autocomplete="on" method="post" accept-charset="utf-8">
<h2 class="text-center"><strong>Portal</strong> Login</h2>
<div class="form-group">
<span class="has-float-label">
<input class="form-control" type="text" name="username" id="username" placeholder="" maxlength="45" autofocus="" value="" required>
<label for="username">Username</label>
</span>
</div>
<div class="form-group">
<span class="has-float-label">
<input class="form-control" type="password" name="pwd" id="pwd" placeholder="" required>
<label for="pwd">Password</label>
</span>
</div>
<div class="form-group">
&nbsp;
</div>
<div class="form-group">
<input class="btn btn-primary btn-block" type="submit" name="submit" value="Sign In">
</div></form>
</div>
</div>
<script type="text/javascript">
		/* $.validator.setDefaults( {
			submitHandler: function () {
				alert( "submitted!" );
			}
		} ); */

		$( document ).ready( function () {

			$( "#portalLogin" ).validate( {
				rules: {
					username: {
						required: true
					},
					pwd: {
						required: true
					}
				},
				messages: {
					username: {
						required: "Username is required"
					},
					pwd: {
						required: "Password is required"
					}
				},
				errorElement: "em",
				errorPlacement: function ( error, element ) {
					// Add the `help-block` class to the error element
					error.addClass( "help-block" );

					if ( element.prop( "type" ) === "checkbox" ) {
						error.insertAfter( element.parent( "label" ) );
					} else {
						error.insertAfter( element );
					}
				},
				highlight: function ( element, errorClass, validClass ) {
					$( element ).parents( ".form-group" ).addClass( "has-error" ).removeClass( "has-success" );
				},
				unhighlight: function (element, errorClass, validClass) {
					$( element ).parents( ".form-group" ).addClass( "has-success" ).removeClass( "has-error" );
				}
			} );
		} );
	</script>
<div class="footer-clean">
<footer>
<div class="container">
<div class="row">
<div class="col-xs-10 text-center">
<p class="copyright">Hassan Usman Katsina Polytechnic &copy; 2019 | All Rights Reserved<br />For assistance, contact <a href="tel:+2347031601940 ">(+234) 07031601940</a> &nbsp;&nbsp;<a href="tel:+2348156083664">(+234) 08156083664</a> &nbsp;&nbsp;<a href="tel:+2348099177276">(+234) 08099177276</a> &nbsp;&nbsp;<a href="tel:+2348133110752">(+234) 08133110752</a><br /><br />
Powered by <a href="http://steadfast.com.ng" target="_blank" title="Visit Steadfast Tech Website" rel="noopener noreferrer">Steadfast Tech</a> </p>
</div>
</div>
</div>
</footer>
</div>
<script src="https://portal.hukpoly.edu.ng/assets/cdn/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script src="https://portal.hukpoly.edu.ng/assets/cdn/bootstrap/3.3.7/js/ie10-viewport-bug-workaround.js"></script>

<script async src="https://www.googletagmanager.com/gtag/js?id=UA-103103907-2"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}  gtag('js', new Date());

  gtag('config', 'UA-103103907-2');
</script>
</body></html>
