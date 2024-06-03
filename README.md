<!DOCTYPE html>
<html>

<head>
	<meta charset="utf-8">
	<title>Los Amantes del Ecuador</title>
	<!-- Description, Keywords and Author -->
	<meta name="description" content="Your description">
	<meta name="keywords" content="Your,Keywords">
	<meta name="author" content="HimanshuGupta">

	<meta name="viewport" content="width=device-width, initial-scale=1.0">

	<!-- Styles -->
	<!-- Bootstrap CSS -->
	<link href="css/bootstrap.min.css" rel="stylesheet">
	<!-- Animate CSS -->
	<link href="css/animate.min.css" rel="stylesheet">
	<!-- Basic stylesheet -->
	<link rel="stylesheet" href="css/owl.carousel.css">
	<!-- Font awesome CSS -->
	<link href="css/font-awesome.min.css" rel="stylesheet">
	<!-- Custom CSS -->
	<link href="css/style.css" rel="stylesheet">
	<link href="css/style-color.css" rel="stylesheet">

	<!-- Favicon -->
	<link rel="shortcut icon" href="img/logo/guitarra.png">
</head>

<body>

	<!-- modal for booking ticket form -->
	<div class="modal fade" id="bookTicket" tabindex="-1" role="dialog" aria-labelledby="BookTicket">
		<div class="modal-dialog" role="document">
			<div class="modal-content">
				<div class="modal-header">
					<button type="button" class="close" data-dismiss="modal" aria-label="Close"><span
							aria-hidden="true">&times;</span></button>
					<h4 class="modal-title" id="myModalLabel">- Concierto Los Amantes del Ecuador - &nbsp; <small><span
								class="label label-success">Disponible</span> &nbsp; </small></h4>
				</div>
				<!-- form for events ticket booking -->
				<form>
					<div class="modal-body">
						<div class="form-group">
							<label for="exampleInputEmail1">Email</label>
							<input type="email" class="form-control" id="exampleInputEmail1"
								placeholder="example@mail.com">
						</div>
						<div class="form-group">
							<label for="exampleInputContact">Contacto</label>
							<input type="text" class="form-control" id="exampleInputContact"
								placeholder="+91 55 5555 5555">
						</div>
						<div class="form-group">
							<label for="exampleInputSeats">Numero de Boletos</label>
							<select class="form-control" id="exampleInputSeats">
								<option>1</option>
								<option>2</option>
								<option>3</option>
								<option>4</option>
								<option>5</option>
							</select>
						</div>
						<div class="checkbox">
							<label>
								<input type="checkbox"> Acepto los terminos de Servicio
							</label>
						</div>
					</div>
					<div class="modal-footer">
						<button type="button" class="btn btn-default" data-dismiss="modal">Cerrar</button>
						<!-- link to payment gatway here -->
						<button type="button" class="btn btn-primary">Comprar Ahora</button>
					</div>
				</form>
			</div>
		</div>
	</div>

	<!-- wrapper -->
	<div class="wrapper" id="home">

		<!-- header area -->
		<header>
			<!-- secondary menu -->
			<nav class="secondary-menu">
				<div class="container">
					<!-- secondary menu left link area -->
					<div class="sm-left">
						<strong>Telf.</strong>:&nbsp; <a href="#">0994788951 / 0987179619</a>&nbsp;&nbsp;&nbsp;&nbsp;
						<strong>E-mail</strong>:&nbsp; <a href="#">amantesecu@gmail.com</a>
					</div>
					<!-- secondary menu right link area -->
					<div class="sm-right">
						<!-- social link -->
						<div class="sm-social-link">
							<a class="h-facebook" href="#"><i class="fa fa-facebook"></i></a>
							<a class="h-whatsapp" href="#"><i class="fa fa-whatsapp"></i></a>
							<a class="h-google" href="#"><i class="fa fa-google-plus"></i></a>
							<a class="h-youtube" href="#"><i class="fa fa-youtube-play"></i></a>
						</div>
					</div>
					<div class="clearfix"></div>
				</div>
			</nav>
			<!-- primary menu -->
			<nav class="navbar navbar-fixed-top navbar-default">
				<div class="container">
					<!-- Brand and toggle get grouped for better mobile display -->
					<div class="navbar-header">
						<button type="button" class="navbar-toggle collapsed" data-toggle="collapse"
							data-target="#bs-example-navbar-collapse-1">
							<span class="sr-only">Toggle navigation</span>
							<span class="icon-bar"></span>
							<span class="icon-bar"></span>
							<span class="icon-bar"></span>
						</button>
						<!-- logo area -->
						<a class="navbar-brand" href="#home">
							<!-- logo image -->
							<img class="img-responsive" src="img/logo/logo.png" alt="" />
						</a>
					</div>

					<!-- Collect the nav links, forms, and other content for toggling -->
					<div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
						<ul class="nav navbar-nav navbar-right">
							<li><a href="#latestalbum">Ultimo Disco</a></li>
							<li><a href="#featuredalbum">Discografia</a></li>
							<!--<li><a href="#joinus">Empleo</a></li> -->
							<li><a href="#portfolio">Portafolio</a></li>
							<li><a href="#events">Conciertos</a></li>
							<li><a href="#team">Equipo</a></li>
							<li><a href="#contact">Contactos</a></li>
						</ul>
					</div><!-- /.navbar-collapse -->
				</div><!-- /.container-fluid -->
			</nav>
		</header>
		<!--/ header end -->

		<!-- banner area -->
		<div class="banner">
			<div id="carousel-example-generic" class="carousel slide" data-ride="carousel">
				<!-- Wrapper for slides -->
				<div class="carousel-inner" role="listbox">
					<div class="item active">
						<img src="img/banner/b1.jpg" alt="...">
						<div class="container">
							<!-- banner caption -->
							<div class="carousel-caption slide-one">
								<!-- heading -->
								<h2 class="animated fadeInLeftBig"><i class="fa fa-music"></i> Los Amantes del Ecuador!
								</h2>
								<!-- paragraph -->
								<h3 class="animated fadeInRightBig">Musica Nacional Ecuatoriana &amp; Latinoamericana.
								</h3>
								<!-- button -->
								<a href="#" class="animated fadeIn btn btn-theme">Descargas</a>
							</div>
						</div>
					</div>
					<div class="item">
						<img src="img/banner/b2.jpg" alt="...">
						<div class="container">
							<!-- banner caption -->
							<div class="carousel-caption slide-two">
								<!-- heading -->
								<h2 class="animated fadeInLeftBig"><i class="fa fa-headphones"></i> Escúchanos...</h2>
								<!-- paragraph -->
								<h3 class="animated fadeInRightBig">En todas las plataforma digitales a nivel mundial.
								</h3>
								<!-- button -->
								<a href="#" class="animated fadeIn btn btn-theme">Ahora</a>
							</div>
						</div>
					</div>
				</div>

				<!-- Controls -->
				<a class="left carousel-control" href="#carousel-example-generic" role="button" data-slide="prev">
					<span class="fa fa-arrow-left" aria-hidden="true"></span>
				</a>
				<a class="right carousel-control" href="#carousel-example-generic" role="button" data-slide="next">
					<span class="fa fa-arrow-right" aria-hidden="true"></span>
				</a>
			</div>
		</div>
		<!--/ banner end -->

		<!-- block for animate navigation menu -->
		<div class="nav-animate"></div>

		<!-- Hero block area -->
		<div id="latestalbum" class="hero pad">
			<div class="container">
				<!-- hero content -->
				<div class="hero-content ">
					<!-- heading -->
					<h2>Último Disco</h2>
					<hr>
					<!-- paragraph -->
					<p>Se incentiva la <strong class="theme-color">difusión</strong> de todo nuestro material <strong
							class="theme-color">discográfico</strong>.</p>
				</div>
				<!-- hero play list -->
				<div class="hero-playlist">
					<div class="row">
						<div class="col-md-6 col-sm-6">
							<!-- music album image -->
							<div class="figure">
								<!-- image -->
								<img class="img-responsive" src="img/album/1.jpeg" alt="" />
								<!-- disk image -->
								<img class="img-responsive disk" src="img/album/disk.png" alt="" />
							</div>
							<!-- album details -->
							<div class="album-details">
								<!-- title -->
								<h4>TEMA: BANDIDA</h4>
								<!-- composed by -->
								<h5>By Los Amantes del Ecuador</h5>
								<!-- paragraph -->
								<p>Grabado en el 2023, en los estudios de ADE-Producciones en la bella ciudad de Quito
									-Ecuador.</p>
								<!-- button -->
								<a href="#" class="btn btn-lg btn-theme" id="playNowBtn"><i
										class="fa fa-play"></i>&nbsp; Play</a>
								

							</div>
						</div>
						<div class="col-md-6 col-sm-6">
							<!-- play list -->
							<div class="playlist-content">
								<ul class="list-unstyled">
									<li class="playlist-number">
										<!-- song information -->
										<div class="song-info">
											<!-- song title -->
											<h4>Carnaval de Guaranda</h4>
											<p><strong>Album</strong>: Carnaval 2024 &nbsp;|&nbsp; <strong>Type</strong>: Danzante
												&nbsp;|&nbsp; <strong>Singer</strong>: Andres S.
												
											</p>

												
											</div>
										<!-- music icon -->
										
										<div class="music-icon">
											<a href="#"><i class="fa fa-play"></i></a>
											<a href="#"><i class="fa fa-pause"></i></a>
										</div>
										
										
										<div class="clearfix"></div>
									</li>
									<li class="playlist-number">
										<!-- song information -->
										<div class="song-info">
											<!-- song title -->
											<h4>Whyskisito</h4>
											<p><strong>Album</strong>: Nacional &nbsp;|&nbsp; <strong>Type</strong>: Sanjuanito
												&nbsp;|&nbsp; <strong>Singer</strong>: Andres S.</p>
										</div>
										<!-- music icon -->
										<div class="music-icon">
											<a href="#"><i class="fa fa-play"></i></a>
											<a href="#"><i class="fa fa-pause"></i></a>
										</div>
										<div class="clearfix"></div>
									</li>
									<li class="playlist-number">
										<!-- song information -->
										<div class="song-info">
											<!-- song title -->
											<h4>Chucta Carajo</h4>
											<p><strong>Album</strong>: Nacional &nbsp;|&nbsp; <strong>Type</strong>: Sanjuanito
												&nbsp;|&nbsp; <strong>Singer</strong>: Andres S.</p>
										</div>
										<!-- music icon -->
										<div class="music-icon">
											<a href="#"><i class="fa fa-play"></i></a>
											<a href="#"><i class="fa fa-pause"></i></a>
										</div>
										<div class="clearfix"></div>
									</li>
									<li class="playlist-number">
										<!-- song information -->
										<div class="song-info">
											<!-- song title -->
											<h4>Ayer te Marchaste</h4>
											<p><strong>Album</strong>: Ayer te Marchaste &nbsp;|&nbsp; <strong>Type</strong>: Bailable
												&nbsp;|&nbsp; <strong>Singer</strong>: Andres S.</p>
										</div>
										<!-- music icon -->
										<div class="music-icon">
											<a href="#"><i class="fa fa-play"></i></a>
											<a href="#"><i class="fa fa-pause"></i></a>
										</div>
										<div class="clearfix"></div>
									</li>
									<li class="playlist-number">
										<!-- song information -->
										<div class="song-info">
											<!-- song title -->
											<h4>Cariñito</h4>
											<p><strong>Album</strong>: Nacional &nbsp;|&nbsp; <strong>Type</strong>: Sanjuanito
												&nbsp;|&nbsp; <strong>Singer</strong>: Andres S.</p>
										</div>
										<!-- music icon -->
										<div class="music-icon">
											<a href="#"><i class="fa fa-play"></i></a>
											<a href="#"><i class="fa fa-pause"></i></a>
										</div>
										<div class="clearfix"></div>
									</li>
									<li class="playlist-number">
										<!-- song information -->
										<div class="song-info">
											<!-- song title -->
											<h4>Lápida Imborrable</h4>
											<p><strong>Album</strong>: Imborrable &nbsp;|&nbsp; <strong>Type</strong>: Bailable
												&nbsp;|&nbsp; <strong>Singer</strong>: Andres S.</p>
										</div>
										<!-- music icon -->
										<div class="music-icon">
											<a href="#"><i class="fa fa-play"></i></a>
											<a href="#"><i class="fa fa-pause"></i></a>
										</div>
										<div class="clearfix"></div>
									</li>
									<li class="playlist-number">
										<!-- song information -->
										<div class="song-info">
											<!-- song title -->
											<h4>Cayambeño</h4>
											<p><strong>Album</strong>: Nacional &nbsp;|&nbsp; <strong>Type</strong>: Cayambeño
												&nbsp;|&nbsp; <strong>Singer</strong>: Andres S.</p>
										</div>
										<!-- music icon -->
										<div class="music-icon">
											<a href="#"><i class="fa fa-play"></i></a>
											<a href="#"><i class="fa fa-pause"></i></a>
										</div>
										<div class="clearfix"></div>
									</li>
									<li class="playlist-number">
										<!-- song information -->
										<div class="song-info">
											<!-- song title -->
											<h4>El Canelazo</h4>
											<p><strong>Album</strong>: Nacional &nbsp;|&nbsp; <strong>Type</strong>: Sanjuanito
												&nbsp;|&nbsp; <strong>Singer</strong>: Andres S.</p>
										</div>
										<!-- music icon -->
										<div class="music-icon">
											<a href="#"><i class="fa fa-play"></i></a>
											<a href="#"><i class="fa fa-pause"></i></a>
										</div>
										<div class="clearfix"></div>
									</li>
									<li class="playlist-number">
										<!-- song information -->
										<div class="song-info">
											<!-- song title -->
											<h4>Lo Siento</h4>
											<p><strong>Album</strong>: Nacional &nbsp;|&nbsp; <strong>Type</strong>: Bomba
												&nbsp;|&nbsp; <strong>Singer</strong>: Andres S.</p>
										</div>
										<!-- music icon -->
										<div class="music-icon">
											<a href="#"><i class="fa fa-play"></i></a>
											<a href="#"><i class="fa fa-pause"></i></a>
										</div>
										<div class="clearfix"></div>
									</li>
									<li class="playlist-number">
										<!-- song information -->
										<div class="song-info">
											<!-- song title -->
											<h4>Carpuela</h4>
											<p><strong>Album</strong>: Nacional &nbsp;|&nbsp; <strong>Type</strong>: Bomba
												&nbsp;|&nbsp; <strong>Singer</strong>: Andres S.</p>
										</div>
										<!-- music icon -->
										<div class="music-icon">
											<a href="#"><i class="fa fa-play"></i></a>
											<a href="#"><i class="fa fa-pause"></i></a>
										</div>
										<div class="clearfix"></div>
									</li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!--/ hero end -->

		<!-- promo -->
		<div class="promo parallax-one pad">
			<div class="container">
				<!-- promo element -->
				<div class="promo-element ">
					<!-- heading -->
					<h3>Música...</h3>
					<!-- paragraph -->
					<p>Es una de las llamadas <strong>Bellas Artes</strong>, es decir, a un género artístico, que
						consiste en conseguir efectos estéticos a través de la manipulación de sonidos vocales o
						instrumentales, conforme a estándares culturales de
						<strong>ritmo, armonía y melodía.</strong>.
					</p>
					<!-- link -->
					<a class="promo-link" href="#"><i class="fa fa-play-circle"></i></a>
				</div>
			</div>
		</div>
		<!--/ promo end -->

		<!-- featured abbum -->
		<div class="featured pad" id="featuredalbum">
			<div class="container">
				<!-- default heading -->
				<div class="default-heading">
					<!-- heading -->
					<h2>Discografía</h2>
				</div>
				<!-- featured album elements -->
				<div class="featured-element">
					<div class="row">
						<div class="col-md-4 col-sm-6">
							<!-- featured item -->
							<div class="featured-item ">
								<!-- image container -->
								<div class="figure">
									<!-- image -->
									<img class="img-responsive" src="img/featured/1.jpeg" alt="" />
									<!-- paragraph -->
									<p>Disco grabado en el 2023, en los estudios de ADE-Producciones en la bella ciudad de Quito -Ecuador,
									que reune el recorrido, por el pentagrama nacional.</p>
								</div>
								<!-- featured information -->
								<div class="featured-item-info">
									<!-- featured title -->
									<h4>BANDIDA</h4>
									<!-- horizontal line -->
									<hr />
									<!-- some responce from social medial or web likes -->
									<p>1024+ <span class="label label-theme">Like</span> &nbsp;&nbsp; 825+ <span
											class="label label-theme">Love</span></p>
								</div>
							</div>
						</div>
						<div class="col-md-4 col-sm-6">
							<!-- featured item -->
							<div class="featured-item ">
								<!-- image container -->
								<div class="figure">
									<!-- image -->
									<img class="img-responsive" src="img/featured/AF_02.png" alt="" />
									<!-- paragraph -->
									<p>Mosaico Nacional 100% chichero, grabado en el 2019, en los estudios de ADE-Producciones
										 en la bella ciudad de Quito -Ecuador, que reune un compilatorio de musica nacional bailable.</p>
									
								</div>
								<!-- featured information -->
								<div class="featured-item-info">
									<!-- featured title -->
									<h4>MOSAICO CHICHERITO</h4>
									<!-- horizontal line -->
									<hr />
									<!-- some responce from social medial or web likes -->
									<p>1024+ <span class="label label-theme">Like</span> &nbsp;&nbsp; 825+ <span
											class="label label-theme">Love</span></p>
								</div>
							</div>
						</div>
						<div class="col-md-4 col-sm-6">
							<!-- featured item -->
							<div class="featured-item ">
								<!-- image container -->
								<div class="figure">
									<!-- image -->
									<img class="img-responsive" src="img/featured/AF_03.png" alt="" />
									<!-- paragraph -->
									<p>CD Solo Carnavales V3, grabado en el 2022, en los estudios de ADE-Producciones
										en la bella ciudad de Quito -Ecuador, que reune un compilatorio de musica Bolivarense.</p>
								</div>
								<!-- featured information -->
								<div class="featured-item-info">
									<!-- featured title -->
									<h4>SOLO CARNAVALES V3</h4>
									<!-- horizontal line -->
									<hr />
									<!-- some responce from social medial or web likes -->
									<p>1024+ <span class="label label-theme">Like</span> &nbsp;&nbsp; 825+ <span
											class="label label-theme">Love</span></p>
								</div>
							</div>
						</div>
						<div class="col-md-4 col-sm-6">
							<!-- featured item -->
							<div class="featured-item ">
								<!-- image container -->
								<div class="figure">
									<!-- image -->
									<img class="img-responsive" src="img/featured/AF_04.png" alt="" />
									<!-- paragraph -->
									<p>CD Solo Carnavales V2, grabado en el 2021, en los estudios de ADE-Producciones
										en la bella ciudad de Quito -Ecuador, que reune un compilatorio de musica Bolivarense.</p>
								</div>
								<!-- featured information -->
								<div class="featured-item-info">
									<!-- featured title -->
									<h4>SOLO CARNAVALES V2</h4>
									<!-- horizontal line -->
									<hr />
									<!-- some responce from social medial or web likes -->
									<p>1024+ <span class="label label-theme">Like</span> &nbsp;&nbsp; 825+ <span
											class="label label-theme">Love</span></p>
								</div>
							</div>
						</div>
						<div class="col-md-4 col-sm-6">
							<!-- featured item -->
							<div class="featured-item ">
								<!-- image container -->
								<div class="figure">
									<!-- image -->
									<img class="img-responsive" src="img/featured/AF_05.png" alt="" />
									<!-- paragraph -->
									<p>CD Solo Carnavales V1, grabado en el 2020, en los estudios de ADE-Producciones
										en la bella ciudad de Quito -Ecuador, que reune un compilatorio de musica Bolivarense.</p>
								</div>
								<!-- featured information -->
								<div class="featured-item-info">
									<!-- featured title -->
									<h4>SOLO CARNAVALES V1</h4>
									<!-- horizontal line -->
									<hr />
									<!-- some responce from social medial or web likes -->
									<p>1024+ <span class="label label-theme">Like</span> &nbsp;&nbsp; 825+ <span
											class="label label-theme">Love</span></p>
								</div>
							</div>
						</div>
						<div class="col-md-4 col-sm-6">
							<!-- featured item -->
							<div class="featured-item ">
								<!-- image container -->
								<div class="figure">
									<!-- image -->
									<img class="img-responsive" src="img/featured/AF_06.png" alt="" />
									<!-- paragraph -->
									<p>CD Nacional Compilatorio, grabado en el 2019, en los estudios de ADE-Producciones
										en la bella ciudad de Quito -Ecuador, que reune un compilatorio de musica nacional Ecuatoriana.</p>
								</div>
								<!-- featured information -->
								<div class="featured-item-info">
									<!-- featured title -->
									<h4>Nacional Compilatorio</h4>
									<!-- horizontal line -->
									<hr />
									<!-- some responce from social medial or web likes -->
									<p>1024+ <span class="label label-theme">Like</span> &nbsp;&nbsp; 825+ <span
											class="label label-theme">Love</span></p>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- features end -->

		<!-- call to action -->
		<div class="cta parallax-one pad">
			<div class="container">
				<!-- cta element -->
				<div class="cta-element ">
					<div class="row">
						<div class="col-md-9 col-sm-8">
							<!-- heading -->
							<h3>Los Amantes del Ecuador</h3>
							<!-- paragraph -->
							<p>Agrupación de música nacional Ecuatoriana, formada en el 2015 en la bella ciudad de
								Quito - Ecuador, con raices bolivarenses, que transmite una fusión de ritmos tradicionales
								y arreglos modernos.</p>
						</div>
						<div class="col-md-3 col-sm-4">
							<div class="cta-btn text-center">
								<!-- purchase now button -->
								<a href="https://www.youtube.com/@losamantesdelecuador6935" class="btn btn-default btn-lg">Descargas</a>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!--/ cta end -->

		<!-- work with us -->
		<div class="work-with-us pad" id="joinus">
			<div class="container">
				<!-- default heading -->
				<div class="default-heading">
					<!-- heading -->
					<h2>Trabaja con Nosotros</h2>
				</div>
				<!-- why work with us content -->
				<div class="why-content">
					<!-- paragraph -->
					<p class="why-message">Si lo tuyo es interpretar un instrumento musical, escribenos 
						llevamos tu talento a otro nivel.</p>
					<div class="row">
						<div class="col-md-3 col-sm-6">
							<!-- why work with us item -->
							<div class="why-item  delay-one">
								<span class="why-number">1</span>
								<!-- paragraph -->
								<p><strong>Trabajo en equipo.- </strong>
									Debes estar consciente de que las personas tienen diferentes estilos de trabajo y formas de ser, 
									pero varios talentos trabajando juntos para un objetivo común genera grandes resultados.</p>
							</div>
						</div>
						<div class="col-md-3 col-sm-6">
							<!-- why work with us item -->
							<div class="why-item  delay-two">
								<span class="why-number">2</span>
								<!-- paragraph -->
								<p><strong>Concentración.-</strong> es importante cuando participas con otros músicos: de esta forma
									 puedes enfocarte en tu propia ejecución sin perder de vista la interpretación de los demás en 
									 conjunto.</p>
							</div>
						</div>
						<div class="col-md-3 col-sm-6">
							<!-- why work with us item -->
							<div class="why-item  delay-three">
								<span class="why-number">3</span>
								<!-- paragraph -->
								<p><strong>Adaptabilidad.-</strong> Como músico, siempre tendrás un estilo favorito o una manera de 
									producir tu trabajo. Sin embargo, actualmente la industria evoluciona tal rapidez, que se vuelve 
									necesario que seas flexible y abierto a estos cambios.</p>
							</div>
						</div>
						<div class="col-md-3 col-sm-6">
							<!-- why work with us item -->
							<div class="why-item  delay-four">
								<span class="why-number">4</span>
								<!-- paragraph -->
								<p><strong>Disciplina.-</strong> Practicar todos los días es la mejor manera de convertirte en 
									un mejor músico. Ensayar una canción hasta que puedas interpretarla a la perfección te 
									dará confianza al momento de subir al escenario.</p>
							</div>
						</div>
					</div>

					
					<!-- apply button -->
					<div class="apply-btn">
						
						<!-- button line -->
						<a class="btn btn-lg btn-theme" href="https://www.facebook.com/LosAmantesdelEcuador">Trabaja ahora</a>
					</div>
				</div>
			</div>
		</div>
		<!--/ end work with us -->

		<!-- news letter -->
		<div class="news-letter">
			<div class="container">
				<!-- news letter inner content -->
				<div class="news-content ">
					<!-- heading -->
					<h3>Suscribete</h3>
					<!-- paragraph -->
					<p><strong>Contáctanos</strong> y recibe lo mas nuevo en la discografía
						de tu grupo amigo, <strong>Los Amantes del Ecuador.</strong></p>
					<!-- subscribe form -->
					<form>
						<div class="input-group">
							<input type="text" class="form-control input-lg" placeholder="Email">
							<span class="input-group-btn">
								<button class="btn btn-default btn-lg" type="button">Subscribe</button>
							</span>
						</div><!-- /input-group -->
					</form>
				</div>
			</div>
		</div>
		<!-- news letter end -->

		<div class="portfolio pad" id="portfolio">
			<div>
				<!-- default heading -->
				<div class="default-heading">
					<!-- heading -->
					<h2>Galeria</h2>
				</div>
			</div>
			<!-- portfolio -->
			<div class="portfolio-content" id="portfolioOwl">
				<div class="item">
					<!-- item image -->
					<img class="img-responsive" src="img/portfolio/P_01.png" alt="">
					<!-- transparent background -->
					<div class="p-transparent"></div>
					<!-- on mouse hover details -->
					<div class="p-hover">
						<!-- heading /title -->
						<h3>Los Amantes <br>en vivo</h3>
						<hr>
						<!-- project details -->
						<p>Concierto 100% Musica Nacional.</p>
						<!-- icon -->
						<a href="#"><i class="fa fa-share"></i></a>
					</div>
				</div>
				<div class="item">
					<!-- item image -->
					<img class="img-responsive" src="img/portfolio/P_02.png" alt="">
					<!-- transparent background -->
					<div class="p-transparent"></div>
					<!-- on mouse hover details -->
					<div class="p-hover">
						<!-- heading /title -->
						<h3>Los Amantes <br>en vivo</h3>
						<hr>
						<!-- project details -->
						<p>Concierto 100% Musica Nacional.</p>
						<!-- icon -->
						<a href="#"><i class="fa fa-share"></i></a>
					</div>
				</div>
				<div class="item">
					<!-- item image -->
					<img class="img-responsive" src="img/portfolio/P_03.png" alt="">
					<!-- transparent background -->
					<div class="p-transparent"></div>
					<!-- on mouse hover details -->
					<div class="p-hover">
						<!-- heading /title -->
						<h3>Los Amantes <br>en vivo</h3>
						<hr>
						<!-- project details -->
						<p>Concierto 100% Musica Nacional.</p>
						<!-- icon -->
						<a href="#"><i class="fa fa-share"></i></a>
					</div>
				</div>
				<div class="item">
					<!-- item image -->
					<img class="img-responsive" src="img/portfolio/P_04.png" alt="">
					<!-- transparent background -->
					<div class="p-transparent"></div>
					<!-- on mouse hover details -->
					<div class="p-hover">
						<!-- heading /title -->
						<h3>Los Amantes <br>en vivo</h3>
						<hr>
						<!-- project details -->
						<p>Concierto 100% Musica Nacional.</p>
						<!-- icon -->
						<a href="#"><i class="fa fa-share"></i></a>
					</div>
				</div>
				<div class="item">
					<!-- item image -->
					<img class="img-responsive" src="img/portfolio/P_05.png" alt="">
					<!-- transparent background -->
					<div class="p-transparent"></div>
					<!-- on mouse hover details -->
					<div class="p-hover">
						<!-- heading /title -->
						<h3>Los Amantes <br>en vivo</h3>
						<hr>
						<!-- project details -->
						<p>Concierto 100% Musica Nacional.</p>
						<!-- icon -->
						<a href="#"><i class="fa fa-share"></i></a>
					</div>
				</div>
				<div class="item">
					<!-- item image -->
					<img class="img-responsive" src="img/portfolio/P_06.png" alt="">
					<!-- transparent background -->
					<div class="p-transparent"></div>
					<!-- on mouse hover details -->
					<div class="p-hover">
						<!-- heading /title -->
						<h3>Los Amantes <br>en vivo</h3>
						<hr>
						<!-- project details -->
						<p>Concierto 100% Musica Nacional.</p>
						<!-- icon -->
						<a href="#"><i class="fa fa-share"></i></a>
					</div>
				</div>
				<div class="item">
					<!-- item image -->
					<img class="img-responsive" src="img/portfolio/P_07.png" alt="">
					<!-- transparent background -->
					<div class="p-transparent"></div>
					<!-- on mouse hover details -->
					<div class="p-hover">
						<!-- heading /title -->
						<h3>Los Amantes <br>en vivo</h3>
						<hr>
						<!-- project details -->
						<p>Concierto 100% Musica Nacional.</p>
						<!-- icon -->
						<a href="#"><i class="fa fa-share"></i></a>
					</div>
				</div>
				<div class="item">
					<!-- item image -->
					<img class="img-responsive" src="img/portfolio/P_08.png" alt="">
					<!-- transparent background -->
					<div class="p-transparent"></div>
					<!-- on mouse hover details -->
					<div class="p-hover">
						<!-- heading /title -->
						<h3>Los Amantes <br>en vivo</h3>
						<hr>
						<!-- project details -->
						<p>Concierto 100% Musica Nacional.</p>
						<!-- icon -->
						<a href="#"><i class="fa fa-share"></i></a>
					</div>
				</div>
			</div>

			<!-- portfolio end -->
		</div>
		<!-- work with us end -->

		<!-- events -->
		<div class="events parallax-three pad" id="events">
			<div class="container">
				<!-- default heading -->
				<div class="default-heading-shadow">
					<!-- heading -->
					<h2>Conciertos - Eventos</h2>
				</div>
				<!-- events element -->
				<div class="events-element">
					<div class="row">
						<div class="col-md-6 col-sm-6">
							<!-- event item -->
							<div class="events-item ">
								<!-- image container -->
								<div class="figure">
									<!-- event date -->
									<div class="event-date">
										22 <span class="emonth">Jun</span>
										<div class="clearfix"></div>
										<!-- time -->
										<span class="etime">06:00 pm</span>
									</div>
									<!-- event location -->
									<span class="event-location"><i class="fa fa-map-marker"></i>Sta. Rosa</span>
									<!-- image -->
									<img class="img-responsive" src="img/event/1.png" alt="" />
									<!-- image hover -->
									<div class="img-hover">
										<!-- hover icon -->
										<a href="#"><i class="fa fa-play-circle"></i></a>
									</div>
								</div>
								<!-- event information -->
								<div class="event-info">
									<!-- event title -->
									<h3>Evento Privado</h3>
									<!-- horizontal line -->
									<hr />
									<!-- paragraph -->
									<p>El Festival Musical, es una muestra representativa que resalta con la participación 
										de agrupaciones locales, nacionales e internacionales el valor artístico y cultural 
										de la música . . .</p>
									<!-- buy ticket button link -->
									<button href="#bookTicket" class="btn btn-lg btn-theme" data-toggle="modal">Boletos
									</button>
								</div>
							</div>
						</div>
						<div class="col-md-6 col-sm-6">
							<!-- event item -->
							<div class="events-item ">
								<!-- image container -->
								<div class="figure">
									<!-- event date -->
									<div class="event-date">
										08 <span class="emonth">Jul</span>
										<div class="clearfix"></div>
										<!-- time -->
										<span class="etime">09:45 pm</span>
									</div>
									<!-- event location -->
									<span class="event-location"><i class="fa fa-map-marker"></i> Cusubamba</span>
									<!-- image -->
									<img class="img-responsive" src="img/event/2.jpeg" alt="" />
									<!-- image hover -->
									<div class="img-hover">
										<!-- hover icon -->
										<a href="#"><i class="fa fa-play-circle"></i></a>
									</div>
								</div>
								<!-- event information -->
								<div class="event-info">
									<!-- event title -->
									<h3>Festival Privado</h3>
									<!-- horizontal line -->
									<hr />
									<!-- paragraph -->
									<p>El Festival Musical, es una muestra representativa que resalta con la participación 
										de agrupaciones locales, nacionales e internacionales el valor artístico y cultural 
										de la música . . .</p>
									<!-- buy ticket button link -->
									<button href="#bookTicket" class="btn btn-lg btn-theme" data-toggle="modal">Boletos
									</button>
								</div>
							</div>
						</div>
						<div class="col-md-6 col-sm-6">
							<!-- event item -->
							<div class="events-item ">
								<!-- image container -->
								<div class="figure">
									<!-- event date -->
									<div class="event-date">
										14 <span class="emonth">Dic</span>
										<div class="clearfix"></div>
										<!-- time -->
										<span class="etime">10:30 pm</span>
									</div>
									<!-- event location -->
									<span class="event-location"><i class="fa fa-map-marker"></i> Bucay</span>
									<!-- image -->
									<img class="img-responsive" src="img/event/3.png" alt="" />
									<!-- image hover -->
									<div class="img-hover">
										<!-- hover icon -->
										<a href="#"><i class="fa fa-play-circle"></i></a>
									</div>
								</div>
								<!-- event information -->
								<div class="event-info">
									<!-- event title -->
									<h3>Fiestas Canton Bucay </h3>
									<!-- horizontal line -->
									<hr />
									<!-- paragraph -->
									<p>El Festival Musical, es una muestra representativa que resalta con la participación 
										de agrupaciones locales, nacionales e internacionales el valor artístico y cultural 
										de la música . . .</p>
									<!-- buy ticket button link -->
									<button href="#bookTicket" class="btn btn-lg btn-theme" data-toggle="modal">Boletos
									</button>
								</div>
							</div>
						</div>
						<div class="col-md-6 col-sm-6">
							<!-- event item -->
							<div class="events-item ">
								<!-- image container -->
								<div class="figure">
									<!-- event date -->
									<div class="event-date">
										10 <span class="emonth">Nov</span>
										<div class="clearfix"></div>
										<!-- time -->
										<span class="etime">10:00 am</span>
									</div>
									<!-- event location -->
									<span class="event-location"><i class="fa fa-map-marker"></i> Quito</span>
									<!-- image -->
									<img class="img-responsive" src="img/event/4.png" alt="" />
									<!-- image hover -->
									<div class="img-hover">
										<!-- hover icon -->
										<a href="#"><i class="fa fa-play-circle"></i></a>
									</div>
								</div>
								<!-- event information -->
								<div class="event-info">
									<!-- event title -->
									<h3>Festival Artístico</h3>
									<!-- horizontal line -->
									<hr />
									<!-- paragraph -->
									<p>El Festival Musical, es una muestra representativa que resalta con la participación 
										de agrupaciones locales, nacionales e internacionales el valor artístico y cultural 
										de la música . . .</p>
									<!-- buy ticket button link -->
									<button href="#bookTicket" class="btn btn-lg btn-theme" data-toggle="modal">Boletos
									</button>
								</div>
							</div>
						</div>
						
						<div class="col-md-6 col-sm-6">
							<!-- event item -->
							<div class="events-item ">
								<!-- image container -->
								<div class="figure">
									<!-- event date -->
									<div class="event-date">
										23 <span class="emonth">Jun</span>
										<div class="clearfix"></div>
										<!-- time -->
										<span class="etime">14:00 </span>
									</div>
									<!-- event location -->
									<span class="event-location"><i class="fa fa-map-marker"></i> Argelia</span>
									<!-- image -->
									<img class="img-responsive" src="img/event/5.png" alt="" />
									<!-- image hover -->
									<div class="img-hover">
										<!-- hover icon -->
										<a href="#"><i class="fa fa-play-circle"></i></a>
									</div>
								</div>
								<!-- event information -->
								<div class="event-info">
									<!-- event title -->
									<h3>INTY RAYMI</h3>
									<!-- horizontal line -->
									<hr />
									<!-- paragraph -->
									<p>El Festival Musical, es una muestra representativa que resalta con la participación 
										de agrupaciones locales, nacionales e internacionales el valor artístico y cultural 
										de la música . . .</p>
									<!-- buy ticket button link -->
									<button href="#bookTicket" class="btn btn-lg btn-theme" data-toggle="modal">Boletos
									</button>
								</div>
							</div>
						</div>


						<div class="col-md-6 col-sm-6">
							<!-- event item -->
							<div class="events-item ">
								<!-- image container -->
								<div class="figure">
									<!-- event date -->
									<div class="event-date">
										23 <span class="emonth">Feb</span>
										<div class="clearfix"></div>
										<!-- time -->
										<span class="etime">09:00</span>
									</div>
									<!-- event location -->
									<span class="event-location"><i class="fa fa-map-marker"></i> Santo Tomas</span>
									<!-- image -->
									<img class="img-responsive" src="img/event/66.png" alt="" />
									<!-- image hover -->
									<div class="img-hover">
										<!-- hover icon -->
										<a href="#"><i class="fa fa-play-circle"></i></a>
									</div>
								</div>
								<!-- event information -->
								<div class="event-info">
									<!-- event title -->
									<h3>CARNAVAL EN QUITO</h3>
									<!-- horizontal line -->
									<hr />
									<!-- paragraph -->
									<p>El Festival Musical, es una muestra representativa que resalta con la participación 
										de agrupaciones locales, nacionales e internacionales el valor artístico y cultural 
										de la música . . .</p>
									<!-- buy ticket button link -->
									<button href="#bookTicket" class="btn btn-lg btn-theme" data-toggle="modal">Boletos
									</button>
								</div>
							</div>
						</div>


						<div class="col-md-6 col-sm-6">
							<!-- event item -->
							<div class="events-item ">
								<!-- image container -->
								<div class="figure">
									<!-- event date -->
									<div class="event-date">
										01 <span class="emonth">Mar</span>
										<div class="clearfix"></div>
										<!-- time -->
										<span class="etime">20:00</span>
									</div>
									<!-- event location -->
									<span class="event-location"><i class="fa fa-map-marker"></i> Chillanes</span>
									<!-- image -->
									<img class="img-responsive" src="img/event/8.png" alt="" />
									<!-- image hover -->
									<div class="img-hover">
										<!-- hover icon -->
										<a href="#"><i class="fa fa-play-circle"></i></a>
									</div>
								</div>
								<!-- event information -->
								<div class="event-info">
									<!-- event title -->
									<h3>CARNAVAL DE GUARANDA</h3>
									<!-- horizontal line -->
									<hr />
									<!-- paragraph -->
									<p>El Festival Musical, es una muestra representativa que resalta con la participación 
										de agrupaciones locales, nacionales e internacionales el valor artístico y cultural 
										de la música . . .</p>
									<!-- buy ticket button link -->
									<button href="#bookTicket" class="btn btn-lg btn-theme" data-toggle="modal">Boletos
									</button>
								</div>
							</div>
						</div>


						<div class="col-md-6 col-sm-6">
							<!-- event item -->
							<div class="events-item ">
								<!-- image container -->
								<div class="figure">
									<!-- event date -->
									<div class="event-date">
										31 <span class="emonth">Mar</span>
										<div class="clearfix"></div>
										<!-- time -->
										<span class="etime">19:00</span>
									</div>
									<!-- event location -->
									<span class="event-location"><i class="fa fa-map-marker"></i> Bolivar</span>
									<!-- image -->
									<img class="img-responsive" src="img/event/9.png" alt="" />
									<!-- image hover -->
									<div class="img-hover">
										<!-- hover icon -->
										<a href="#"><i class="fa fa-play-circle"></i></a>
									</div>
								</div>
								<!-- event information -->
								<div class="event-info">
									<!-- event title -->
									<h3>FESTIVAL ARTISTICO</h3>
									<!-- horizontal line -->
									<hr />
									<!-- paragraph -->
									<p>El Festival Musical, es una muestra representativa que resalta con la participación 
										de agrupaciones locales, nacionales e internacionales el valor artístico y cultural 
										de la música . . .</p>
									 
									<!-- buy ticket button link -->
									<button href="#bookTicket" class="btn btn-lg btn-theme" data-toggle="modal">Boletos</button>
								</div>
							</div>
						</div>


					
					</div>
				</div>
			</div>
		</div>
		<!-- events end -->

		<!-- about -->
		<div class="about" id="team">
			<div class="container">
				<!-- default heading -->
				<div class="default-heading">
					<!-- heading -->
					<h2>Quienes somos</h2>
				</div>
				<!-- about what we are like content -->
				<div class="about-what-we">
					<div class="row">
						<div class="col-md-4 col-sm-4">
							<div class="what-we-item ">
								<!-- heading with icon -->
								<center>
									<h3><i class="fa fa-heartbeat"></i> Que música interpretamos?</h3>
								</center>
								
								<!-- paragraph -->
								<center>
									<p>Somos una agrupación de musica nacional Ecuatoriana, realizamos todo tipo  
										de musica, entre los géneros mas relevantes se encuentran: Bomba,
										Sanjuanito, Pasacalle, Tonada, Pasillo, Banda, Cumbia.</p>

								</center>
								
							</div>
						</div>
						<div class="col-md-4 col-sm-4">
							<div class="what-we-item ">
								<!-- heading with icon -->
								<center>
								<h3><i class="fa fa-hand-o-up"></i> Porque elegirnos?</h3>
								</center>
								<!-- paragraph -->
								<center>
									<p>Realizamos la fusión de los ritmos tradicionales con sonidos mas frescos
										y juveniles, llevando asi el estandarte de la musica Nacional Ecuatoriana 
										por todos los rincones de la patria.</p>

								</center>
								
							</div>
						</div>
						<div class="col-md-4 col-sm-4">
							
								<div class="what-we-item ">
									<!-- heading with icon -->
									<center>
										<h3><i class="fa fa-map-marker"></i> Donde nos ubicamos?</h3>
									<!-- paragraph -->
									</center>
									
									<center>
										<p>Residimos al sur de la ciudad de Quito-Ecuador y segun los 
											requerimientos nos trasladamos por todo el pais, llevando
											la cultura musical Ecuatoriana a mas lugares.</p>

									</center>
								</div>

								
							
						</div>
					</div>
				</div>
			</div>
			<!-- our team -->
			<div class="team">
				<div class="container">
					<!-- Team Member's Details -->
					<div class="team-content">
						<div class="row">
							<div class="col-md-3 col-sm-6">
								<!-- Team Member -->
								<div class="team-member  delay-one">
									<!-- Image Hover Block -->
									<div class="member-img">
										<!-- Image  -->
										<img class="img-responsive" src="img/user/U_01.png" alt="" />
										<!-- Hover block -->
										<div class="social text-center">
											<a href="https://www.facebook.com/LosAmantesdelEcuador"><i class="fa fa-facebook"></i></a>
											<a href="https://mail.google.com/mail/"><i class="fa fa-google-plus"></i></a>
											<a href="https://web.whatsapp.com/"><i class="fa fa-whatsapp"></i></a>
											<a href="https://www.youtube.com/@losamantesdelecuador6935"><i class="fa fa-youtube"></i></a>
										</div>
									</div>
									<!-- Member Details -->
									<h3>Andres Salazar</h3>
									<span class="designation">Requinto - 1ra Vos</span>
								</div>
							</div>
							<div class="col-md-3 col-sm-6">
								<!-- Team Member -->
								<div class="team-member  delay-two">
									<!-- Image Hover Block -->
									<div class="member-img">
										<!-- Image  -->
										<img class="img-responsive" src="img/user/U_02.png" alt="" />
										<!-- Hover block -->
										<div class="social text-center">
											<a href="https://www.facebook.com/LosAmantesdelEcuador"><i class="fa fa-facebook"></i></a>
											<a href="https://mail.google.com/mail/"><i class="fa fa-google-plus"></i></a>
											<a href="https://web.whatsapp.com/"><i class="fa fa-whatsapp"></i></a>
											<a href="https://www.youtube.com/@losamantesdelecuador6935"><i class="fa fa-youtube"></i></a>
										</div>
									</div>
									<!-- Member Details -->
									<h3>Bagner Ramos</h3>
									<span class="designation">Guitarra - 2da Vos</span>
								</div>
							</div>
							<div class="col-md-3 col-sm-6">
								<!-- Team Member -->
								<div class="team-member  delay-three">
									<!-- Image Hover Block -->
									<div class="member-img">
										<!-- Image  -->
										<img class="img-responsive" src="img/user/U_03.png" alt="" />
										<!-- Hover block -->
										<div class="social text-center">
											<a href="https://www.facebook.com/LosAmantesdelEcuador"><i class="fa fa-facebook"></i></a>
											<a href="https://mail.google.com/mail/"><i class="fa fa-google-plus"></i></a>
											<a href="https://web.whatsapp.com/"><i class="fa fa-whatsapp"></i></a>
											<a href="https://www.youtube.com/@losamantesdelecuador6935"><i class="fa fa-youtube"></i></a>
										</div>
									</div>
									<!-- Member Details -->
									<h3>Darwin Bonilla</h3>
									<span class="designation">Bajo - 3ra Vos</span>
								</div>
							</div>
							<div class="col-md-3 col-sm-6">
								<!-- Team Member -->
								<div class="team-member  delay-four">
									<!-- Image Hover Block -->
									<div class="member-img">
										<!-- Image  -->
										<img class="img-responsive" src="img/user/U_04.png" alt="" />
										<!-- Hover block -->
										<div class="social text-center">
											<a href="https://www.facebook.com/LosAmantesdelEcuador"><i class="fa fa-facebook"></i></a>
											<a href="https://mail.google.com/mail/"><i class="fa fa-google-plus"></i></a>
											<a href="https://web.whatsapp.com/"><i class="fa fa-whatsapp"></i></a>
											<a href="https://www.youtube.com/@losamantesdelecuador6935"><i class="fa fa-youtube"></i></a>
										</div>
									</div>
									<!-- Member Details -->
									<h3>Mauricio Machado</h3>
									<span class="designation">Tecladista</span>
								</div>
							</div>
							
							<div class="col-md-3 col-sm-6">
								<!-- Team Member -->
								<div class="team-member  delay-four">
									<!-- Image Hover Block -->
									<div class="member-img">
										<!-- Image  -->
										<img class="img-responsive" src="img/user/U_05.png" alt="" />
										<!-- Hover block -->
										<div class="social text-center">
											<a href="https://www.facebook.com/LosAmantesdelEcuador"><i class="fa fa-facebook"></i></a>
											<a href="https://mail.google.com/mail/"><i class="fa fa-google-plus"></i></a>
											<a href="https://web.whatsapp.com/"><i class="fa fa-whatsapp"></i></a>
											<a href="https://www.youtube.com/@losamantesdelecuador6935"><i class="fa fa-youtube"></i></a>
										</div>
									</div>
									<!-- Member Details -->
									<h3>Khriz Sandoya</h3>
									<span class="designation">Guiro - Animación</span>
								</div>
							</div>
							
							<div class="col-md-3 col-sm-6">
								<!-- Team Member -->
								<div class="team-member  delay-four">
									<!-- Image Hover Block -->
									<div class="member-img">
										<!-- Image  -->
										<img class="img-responsive" src="img/user/U_06.png" alt="" />
										<!-- Hover block -->
										<div class="social text-center">
											<a href="https://www.facebook.com/LosAmantesdelEcuador"><i class="fa fa-facebook"></i></a>
											<a href="https://mail.google.com/mail/"><i class="fa fa-google-plus"></i></a>
											<a href="https://web.whatsapp.com/"><i class="fa fa-whatsapp"></i></a>
											<a href="https://www.youtube.com/@losamantesdelecuador6935"><i class="fa fa-youtube"></i></a>
										</div>
									</div>
									<!-- Member Details -->
									<h3>Edgar Morales</h3>
									<span class="designation">Percusión Mayor</span>
								</div>
							</div>

							



						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- about end -->

		<!-- meet -->
		<div class="meet parallax-four pad" id="meet">
			<div class="container">
				<!-- default heading -->
				<div class="default-heading-shadow">
					<h2>Primero lo Nuestro</h2>
				</div>
				<!-- meet location image -->
				<div class="meet-map">
					<img class="img-responsive img-map" src="img/flat/map_ec.png" alt="" />

				</div>
			</div>
		</div>
		<!-- meet end -->

		<!-- contact -->
		<div class="contact pad" id="contact">
			<div class="container">
				<!-- default heading -->
				<div class="default-heading">
					<!-- heading -->
					<h2>CONTACTOS</h2>
				</div>
				<div class="row">
					<div class="col-md-4 col-sm-4">
						<!-- contact item -->
						<div class="contact-item ">
							<!-- big icon -->
							<i class="fa fa-street-view"></i>
							<!-- contact details  -->
							<span class="contact-details">Calle A, Pasaje 1, Sector Sur, Quito - Ecuador</span>
						</div>
					</div>
					<div class="col-md-4 col-sm-4">
						<!-- contact item -->
						<div class="contact-item ">
							<!-- big icon -->
							<i class="fa fa-wifi"></i>
							<!-- contact details  -->
							<span class="contact-details">amantesecu@gmail.com</span>
						</div>
					</div>
					<div class="col-md-4 col-sm-4">
						<!-- contact item -->
						<div class="contact-item ">
							<!-- big icon -->
							<i class="fa fa-phone"></i>
							<!-- contact details  -->
							<span class="contact-details">0994788951 / 09871796919</span>
						</div>
					</div>
				</div>
				<!-- form content -->
				<div class="form-content ">
					<!-- paragraph -->
					<p>Si deseas <strong class="theme-color">contactarte</strong> con nuestro equipo de <strong
							class="theme-color">trabajo</strong>.</p>

					<form role="form" id="contactForm" method="post">
						<div class="row">
							<div class="col-md-6 col-sm-6">
								<div class="form-group">
									<label for="name">Nombres</label>
									<input type="text" class="form-control" id="name" name="name"
										placeholder="Ingrese sus nombres">
								</div>
								<div class="form-group">
									<label for="email">Email</label>
									<input type="email" class="form-control" id="email" name="email"
										placeholder="Ingrese su email">
								</div>
								<div class="form-group">
									<label for="phone">Número</label>
									<input type="text" class="form-control" id="phone" name="phone"
										placeholder="Ingrese su Telf.">
								</div>
							</div>
							<div class="col-md-6 col-sm-6">
								<div class="form-group">
									<label for="message">Mensaje</label>
									<textarea class="form-control" id="message" name="message" rows="9"
										placeholder="Escriba su messaje"></textarea>
								</div>
							</div>
						</div>
						<div class="text-center">
							<a class="btn btn-lg btn-theme"
								href="https://www.facebook.com/LosAmantesdelEcuador">Escribenos</a>
						</div>
					</form>

				</div>

			</div>
		</div>
		<!-- contact end -->

		<!-- footer -->
		<footer>
			<div class="container">
				<!-- social media links -->
				<div class="social">
					<a class="h-facebook" href="https://www.facebook.com/LosAmantesdelEcuador"><i class="fa fa-facebook"></i></a>
					<a class="h-google" href="https://mail.google.com/mail/"><i class="fa fa-google-plus"></i></a>
					<a class="h-whatsapp" href="https://web.whatsapp.com/"><i class="fa fa-whatsapp"></i></a>
					<a class="h-youtube" href="https://www.youtube.com/@losamantesdelecuador6935"><i class="fa fa-youtube-square"></i></a>
				</div>
				<!-- copy right -->
				<p class="copy-right">&copy; Copyright 2024, Todos los derechos reservados | Los Amantes del Ecuador.
				</p>
			</div>
		</footer>
		<!-- footer end -->

		<!-- Scroll to top -->
		<span class="totop"><a href="#"><i class="fa fa-chevron-up"></i></a></span>

	</div>

	<!-- Javascript files -->
	<!-- jQuery -->
	<script src="js/jquery.js"></script>
	<!-- Bootstrap JS -->
	<script src="js/bootstrap.min.js"></script>
	<!-- WayPoints JS -->
	<script src="js/waypoints.min.js"></script>
	<!-- Include js plugin -->
	<script src="js/owl.carousel.min.js"></script>
	<!-- One Page Nav -->
	<script src="js/jquery.nav.js"></script>
	<!-- Respond JS for IE8 -->
	<script src="js/respond.min.js"></script>
	<!-- HTML5 Support for IE -->
	<script src="js/html5shiv.js"></script>
	<!-- Custom JS -->
	<script src="js/custom.js"></script>
</body>

</html>
