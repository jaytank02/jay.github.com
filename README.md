# jay.github.com
<html>
	<head>
		<title>Login Page</title>
	</head>
	
	<body>
		<style>
			body{
				background-color:black;
			}
			h2{
				color:white;
				font-size:80px;
				margin:50px;
			}
			form{
				font-family:verdana;
				color:white;
			}
			table{
				border:1px solid white;
				padding:10px;
				border-radius:5px;
				margin:4px;
			}
			.cen1{
				 text-align: center;
				 padding:5px;
				 margin:4px;
				 cursor:text;
				 border:0px;
				 border-radius:5px;
			}
			.cen2{
				 text-align: center;
				 padding:5px;
				 margin:6px;
				 cursor:text;
				 border:0px;
				 border-radius:5px;
			}
			.cen3{
				 text-align: left;
				 padding:8px 135px;
				 margin:30px;
				 color:white;
				 background-color:#1E90FF;
				 display:inline-block;
				 border:0;
			}
			.cen3:hover,.cen3:active{
				background-color:blue;
				cursor:pointer;
			}
			p{
				font-size:10px;
			}
			a{
				color:#66FF33;
				text-align:;
			}
		</style>
		
		<center>
			<form method="POST" action="" >
				<table>
					<h2>LOG IN</h2>
					<tr>
						<td align="left">User Name</td>
						<td align="left"><input type="text" name="unm" placeholder="Enter Name" value="" id="uname" class="cen1" required><br></td>
					</tr>
					
					<tr>
						<td align="left">Password</td>
						<td align="left"><input type="password" name="password" placeholder="Enter Password" value="" id="password" class="cen2" required><br></td>
					</tr>	
				</table>
					<a href="homepage.php"><input type="submit" name="login" value="Log in" id="loginbtn" class="cen3"></a>
					<P>Forgate <a href="forgetpage.php">Password?</a></p>
					<p>Create New Account? <a href="signuppage.php">Sign in</a></p>
			</form>
		</center>
	</body>
</html>
