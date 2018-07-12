# Prueba-bosstrap
Maquetacion responsiva usando boostrap
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Prueba</title>
	<meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
	<link rel="stylesheet" href="css/bootstrap.min.css">
	
</head>
<body>
	<div class="container">
		<div class="row">
			<div class="col-12 text-center bg-primary text-white">
				<h1>Hola mundo!</h1>
			</div>
		</div>
	</div>
	<br>

<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Navbar</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Dropdown
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#">Disabled</a>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>


	
	<main>
		<div class="container text-justify">
			<div class="row">
				<div class="col1 col-xs-12 col-md-6 col-lg-4 bg-success text-white">
					<p><span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione omnis illum dolorum quae nobis, aliquam, ipsa maxime reprehenderit laborum cumque in autem, optio magnam odio beatae voluptates placeat consequatur fugit.</span>
					</p>
				</div>

				<div class="col2 col-xs-12 col-md-6 col-lg-4 bg-warning text-white">
					<p><span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione omnis illum dolorum quae nobis, aliquam, ipsa maxime reprehenderit laborum cumque in autem, optio magnam odio beatae voluptates placeat consequatur fugit.</span>
					</p>
				</div>

				<div class="col3 col-xs-12 col-md-12 col-lg-4 bg-danger text-white">
					<p><span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione omnis illum dolorum quae nobis, aliquam, ipsa maxime reprehenderit laborum cumque in autem, optio magnam odio beatae voluptates placeat consequatur fugit.</span>
					</p>
				</div>
			</div>
		</div>
	</main>
	<br>

	<div class="container">
		<form>
	  <div class="form-row">
	    <div class="col-md-4 mb-3">
	      <label for="validationDefault01">First name</label>
	      <input type="text" class="form-control" id="validationDefault01" placeholder="First name" value="Mark" required>
	    </div>
	    <div class="col-md-4 mb-3">
	      <label for="validationDefault02">Last name</label>
	      <input type="text" class="form-control" id="validationDefault02" placeholder="Last name" value="Otto" required>
	    </div>
	    <div class="col-md-4 mb-3">
	      <label for="validationDefaultUsername">Username</label>
	      <div class="input-group">
	        <div class="input-group-prepend">
	          <span class="input-group-text" id="inputGroupPrepend2">@</span>
	        </div>
	        <input type="text" class="form-control" id="validationDefaultUsername" placeholder="Username" aria-describedby="inputGroupPrepend2" required>
	      </div>
	    </div>
	  </div>
	  <div class="form-row">
	    <div class="col-md-6 mb-3">
	      <label for="validationDefault03">City</label>
	      <input type="text" class="form-control" id="validationDefault03" placeholder="City" required>
	    </div>
	    <div class="col-md-3 mb-3">
	      <label for="validationDefault04">State</label>
	      <input type="text" class="form-control" id="validationDefault04" placeholder="State" required>
	    </div>
	    <div class="col-md-3 mb-3">
	      <label for="validationDefault05">Zip</label>
	      <input type="text" class="form-control" id="validationDefault05" placeholder="Zip" required>
	    </div>
	  </div>
	  <div class="form-group">
	    <div class="form-check">
	      <input class="form-check-input" type="checkbox" value="" id="invalidCheck2" required>
	      <label class="form-check-label" for="invalidCheck2">
	        Agree to terms and conditions
	      </label>
	    </div>
	  </div>
	  <button class="btn btn-primary" type="submit">Submit form</button>
	</form>
</div>	

<div class="card text-center">
  <div class="card-header">
    Featured
  </div>
  <div class="card-body">
    <h5 class="card-title">Special title treatment</h5>
    <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
  <div class="card-footer text-muted">
    2 days ago
  </div>
</div>



	<link rel="stylesheet" href="js/jquery-3.3.1.slim.min.js">
	<link rel="stylesheet" href="js/popper.min.js">
	<link rel="stylesheet" href="js/bootstrap.min.js">
	
</body>
</html>
