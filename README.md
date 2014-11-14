<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Galerie imagini</title>

    <!-- Bootstrap -->
    <link href="http://madalinul.github.io/css/bootstrap.min.css" rel="stylesheet">
	<link href="http://madalinul.github.io/css/galerie.css" rel="stylesheet">
    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>
  <body>
    <div class="jumbotron">
		<div class="container">
		<div class="content">
		<h1>O galerie misto!</h1>
		<p>Cum poate sa arate un site modern cu ajutorul librarii bootrsrap bla bla bla</p>
		</div>
		</div>
	</div>
	
	<div class="gallery">
		<div class="container">
			<div class="gallery-images">
			<hr>
				<div class="row">
					<div class="col-md-4 col-sm-6">
					<div class="thumbnail">
						<img src="http://info.russian-women.net/russian-women/Beach/pictures/Russian-women-Beach-pictures-44.jpg">
					</div>
					</div>
					<div class="col-md-4 col-sm-6">
					<div class="thumbnail">
						<img src="https://lh3.googleusercontent.com/-U7o13DjOAZM/T6RZUumoYoI/AAAAAAABRyc/iP-pKDt0QBE/s1600-d/women%20beach%20sexy%201680x1050%20wallpaper_www.wallfox_net_84.jpg">
					</div>
					</div>
					<div class="col-md-4 col-sm-6">
					<div class="thumbnail">
						<img src="http://anguillaexpo.com/wp-content/uploads/2013/10/women-beach-sand-sexy-models-smiles-swimsuits-stephanie-mcmichael-2560x1600-wallpaper_www.wallfox_net_42.jpg">
					</div>
					</div>
					<hr>
					<div class="col-md-4 col-sm-6">
					<div class="thumbnail">
						<img src="https://lh3.googleusercontent.com/-wZsQRt9OvWs/T6bWK1jlN-I/AAAAAAABZeo/2N4L_0L5Ob8/s1920-d/women%20bikini%20beach%20miranda%20kerr%20sexy%20models%201920x1200%20wallpaper_www.wallfox_net_60.jpg">
					</div>
					</div>
					
					<div class="col-md-4 col-sm-6">
					<div class="thumbnail">
						
						<img src="http://erp.atcpics.com/ltimages/hkparcels/JJJ-1008-1406/JJJ-1008-1406_c.jpg">
					</div>
					</div>
					
					<div class="col-md-4 col-sm-6">
					<div class="thumbnail">
						<img src="http://i.imgur.com/j745Bra.jpg">
					</div>
					</div>
					
				</div>
			</div>
			<hr>
		</div>
	</div>
	
	<footer>
	<div class="container">
		<div class="fcontent">
		<div class="pull-left">
		<h2> madalinulBoss@gmail.com</h2>
		</div>
		
		<div class="pull-right">
		<h2> &copy; 2014</h2>
		</div>
		</div>
		</div>
	</footer>
    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="http://madalinul.github.io/js/bootstrap.min.js"></script>
	<script>
	
		<!-- Functie ce inlocuieste src-ul unei imagini cand se duce cursorul desupra acesteia dute ba>?! esti prost?-->
		var shrek = function() {
			$('img').mouseenter(function() {
				$(this).data('targetsrc',$(this).attr('src'));
				$(this).attr('src',"http://i.imgur.com/Phxark9.jpg");
			});
			$('img').mouseleave(function() {
				$(this).attr('src',$(this).data('targetsrc'));
			});
			};
		
		$(document).ready(shrek);
	</script>
  </body>
</html>
