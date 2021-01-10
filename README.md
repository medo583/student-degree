<? 
session_start();
?>
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title> admin - add students degree </title>
	<link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
	<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Changa:wght@300&display=swap" rel="stylesheet">
	<link rel="stylesheet" type="text/css" href="css/style.css">
</head>

<body>
<div class="container">
	<div class="row">
		<div class="col-lg-6 center">
			<? 
			if(isset($_SESSION['admin'])) { ?>
			<h1>my result</h1>
			<hr>
			<a href="view.php" class="btn btn-block btn-primary btn-lg"> view - students result </a>
					<br />
						<a href="admin.php" class="btn btn-block btn-primary btn-lg">admin - add students degree  </a>
			<? }else{ ?>
			<h1> log in</h1>
			<hr>
		<input type="text" required name="username" class="form-control" placeholder="user name">
		<br>
		<input type="password" required name="password" class="form-control" placeholder="password">
		<br>
		<button type="submit" class="btn btn-block btn-primary" ></button>
			<? } ?>
		</div>
	</div>
</div>
</body>
</html>
