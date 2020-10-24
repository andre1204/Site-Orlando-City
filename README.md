# Site-Orlando-City
Desenvolvimento web com Html, Css, JavaScript e Bootstrap.


<!DOCTYPE html>
<html ng-app="shop">
	<head>

		<meta charset="utf-8">
		<meta name="viewport" content="width:device-width, initial-scale=1">
		<title>Orlando City</title>
		<link rel="stylesheet" href="lib/bootstrap/css/bootstrap.min.css">
		<link rel="stylesheet" href="lib/owl.carousel/owl-carousel/owl.carousel.css">
		<link rel="stylesheet" href="fonts/font-awesome/css/font-awesome.min.css">
		<link rel="stylesheet" href="lib/raty/lib/jquery.raty.css">
		<link rel="stylesheet" href="css/orlando.css">
		<link rel="stylesheet" href="css/orlando-mobile.css">

		<script src="lib/angularjs/angular.min.js"></script>

	</head>
	<body>

		<header>
			
			<div id="menu-mobile-mask" class="visible-xs"></div>

			<div id="menu-mobile" class="visible-xs">
				
				<ul class="list-unstyled">
					<li><a href="videos">Videos</a></li>
					<li><a href="#">Tickets</a></li>
					<li><a href="#">News</a></li>
					<li><a href="#">Schedule</a></li>
				</ul>

				<div class="bar-close">
					<button type="button" class="btn btn-close"><i class="fa fa-close"></i></button>
				</div>

			</div>
			
			<div class="container">
				<img id="logotipo" src="img/orlando-logo.png" alt="Logotipo">
			</div>

			<div class="header-black">
				
				<div class="container">

					<input type="search" id="input-search-mobile" class="visible-xs" placeholder="search...">
				
					<button id="btn-bars" type="button"><i class="fa fa-bars"></i></button>
					<button id="btn-search" type="button"><i class="fa fa-search"></i></button>

					<ul class="pull-right">
						<li class="club-01"><a href="#"></a></li>
						<li class="club-02"><a href="#"></a></li>
						<li class="club-03"><a href="#"></a></li>
						<li class="club-04"><a href="#"></a></li>
						<li class="club-05"><a href="#"></a></li>
						<li class="club-06"><a href="#"></a></li>
						<li class="club-07"><a href="#"></a></li>
						<li class="club-08"><a href="#"></a></li>
						<li class="club-09"><a href="#"></a></li>
						<li class="club-10"><a href="#"></a></li>
						<li class="club-11"><a href="#"></a></li>
						<li class="club-12"><a href="#"></a></li>
						<li class="club-13"><a href="#"></a></li>
						<li class="club-14"><a href="#"></a></li>
						<li class="club-15"><a href="#"></a></li>
						<li class="club-16"><a href="#"></a></li>
						<li class="club-17"><a href="#"></a></li>
						<li class="club-18"><a href="#"></a></li>
						<li class="club-19"><a href="#"></a></li>
						<li class="club-20"><a href="#"></a></li>
						<li class="club-21"><a href="#"></a></li>
						<li class="club-22"><a href="#"></a></li>
					</ul>

				</div>

			</div>

			<div class="container">
				
				<div class="row">
					
					<nav id="menu" class="pull-right">
						<ul>
							<li><a href="index.php">Home</a></li>
							<li><a href="videos">Videos</a></li>
							<li><a href="#">Tickets</a></li>
							<li><a href="#">News</a></li>
							<li><a href="#">Schedule</a></li>
							<li class="search">
								<div class="input-group">
							      <input type="search" placeholder="search" id="input-search">
							      <span class="input-group-btn">
							        <button type="button"><i class="fa fa-search"></i></button>
							      </span>
							    </div><!-- /input-group -->
							</li>
						</ul>
					</nav>

				</div>

			</div>			

		</header>








<?php include_once("header.php");?>

		<section>
			
			<div id="banner">
				
				<h1>Orlando City<small>Orlando City Soccer Club</small></h1>

			</div>

			<div id="news" class="container">
				
				<div class="row text-center">
					<h2>Latest News</h2>
					<hr>	
				</div>				
				
				<button type="button" id="btn-news-prev"><i class="fa fa-angle-left"></i></button>
				<button type="button" id="btn-news-next"><i class="fa fa-angle-right"></i></button>

				<div class="row thumbnails">
					<div class="item">
						<div class="item-inner">
							<img src="img/noticia-thumb.jpg" alt="Noticia">
							<h3>Orlando City Acquires Goalkeeper Joe Bendik from Toronto FC</h3>
							<time>December 21, 2015</time>
						</div>chevron
					</div>
					<div class="item">
						<div class="item-inner">
							<img src="img/noticia-thumb.jpg" alt="Noticia">
							<h3>Orlando City Acquires Goalkeeper Joe Bendik from Toronto FC</h3>
							<time>December 21, 2015</time>
						</div>
					</div>
					<div class="item">
						<div class="item-inner">
							<img src="img/noticia-thumb.jpg" alt="Noticia">
							<h3>Orlando City Acquires Goalkeeper Joe Bendik from Toronto FC</h3>
							<time>December 21, 2015</time>
						</div>
					</div>
					<div class="item">
						<div class="item-inner">
							<img src="img/noticia-thumb.jpg" alt="Noticia">
							<h3>Orlando City Acquires Goalkeeper Joe Bendik from Toronto FC</h3>
							<time>December 21, 2015</time>
						</div>
					</div>
					<div class="item">
						<div class="item-inner">
							<img src="img/noticia-thumb.jpg" alt="Noticia">
							<h3>Orlando City Acquires Goalkeeper Joe Bendik from Toronto FC</h3>
							<time>December 21, 2015</time>
						</div>
					</div>
					<div class="item">
						<div class="item-inner">
							<img src="img/noticia-thumb.jpg" alt="Noticia">
							<h3>Orlando City Acquires Goalkeeper Joe Bendik from Toronto FC</h3>
							<time>December 21, 2015</time>
						</div>
					</div>
					<div class="item">
						<div class="item-inner">
							<img src="img/noticia-thumb.jpg" alt="Noticia">
							<h3>Orlando City Acquires Goalkeeper Joe Bendik from Toronto FC</h3>
							<time>December 21, 2015</time>
						</div>
					</div>
					<div class="item">
						<div class="item-inner">
							<img src="img/noticia-thumb.jpg" alt="Noticia">
							<h3>Orlando City Acquires Goalkeeper Joe Bendik from Toronto FC</h3>
							<time>December 21, 2015</time>
						</div>
					</div>
				</div>

			</div>

			<div id="estatisticas">
				
				<div class="container">
					<div class="row">
						<div class="col-md-4">
							<p>61348<small>Stadium Capacity</small></p>
						</div>
						<div class="col-md-4">
							<p>2010<small>Founded</small></p>
						</div>
						<div class="col-md-4">
							<p>7th<small>Eastern Conference</small></p>
						</div>
					</div>
				</div>

			</div>

			<div id="call-to-action">
				
				<div class="container">

					<div class="row text-center">
						<h2>American club number one in Brazil</h2>
						<hr>	
					</div>

					<div class="row">
						
						<p>Adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat volup tatem. Uteni ad minima veniam, quis nostrum sed quia non numquam eius modi tempora incidunt ut. quia non numquam eius numquam eius modi temp modi tempora incidunt ut labore et dolore m.</p>

					</div>
					
					<div class="text-center">
						<div class="row row-max-400">
							
							<div class="col-xs-6">
								<a href="shop" class="btn btn-roxo">Shop</a>
							</div>
							<div class="col-xs-6">
								<a href="#" class="btn btn-amarelo">Register</a>
							</div>

						</div>
					</div>

				</div>

			</div>

		</section>

<?php include_once("footer.php");?>










<?php

require 'inc/configuration.php';
require 'inc/Slim-2.x/Slim/Slim.php';

\Slim\Slim::registerAutoloader();

$app = new \Slim\Slim();

// GET route
$app->get(
    '/',
    function () {

        require_once("view/index.php");
        
    }
);

$app->get(
    '/videos',
    function () {
        
        require_once("view/videos.php");
        
    }
);

$app->get(
    '/shop',
    function () {
        
        require_once("view/shop.php");
        
    }
);

$app->get('/produtos', function(){

    $sql = new Sql();

    $data = $sql->select("SELECT * FROM tb_produtos where preco_promorcional > 0 order by preco_promorcional desc limit 3;");

    foreach ($data as &$produto) {
        $preco = $produto['preco'];
        $centavos = explode(".", $preco);
        $produto['preco'] = number_format($preco, 0, ",", ".");
        $produto['centavos'] = end($centavos);
        $produto['parcelas'] = 10;
        $produto['parcela'] = number_format($preco/$produto['parcelas'], 2, ",", ".");
        $produto['total'] = number_format($preco, 2, ",", ".");
    }

    echo json_encode($data);

});

$app->get('/produtos-mais-buscados', function(){

    $sql = new Sql();

    $data = $sql->select("
        SELECT 
        tb_produtos.id_prod,
        tb_produtos.nome_prod_curto,
        tb_produtos.nome_prod_longo,
        tb_produtos.codigo_interno,
        tb_produtos.id_cat,
        tb_produtos.preco,
        tb_produtos.peso,
        tb_produtos.largura_centimetro,
        tb_produtos.altura_centimetro,
        tb_produtos.quantidade_estoque,
        tb_produtos.preco_promorcional,
        tb_produtos.foto_principal,
        tb_produtos.visivel,
        cast(avg(review) as dec(10,2)) as media, 
        count(id_prod) as total_reviews
        FROM tb_produtos 
        INNER JOIN tb_reviews USING(id_prod) 
        GROUP BY 
        tb_produtos.id_prod,
        tb_produtos.nome_prod_curto,
        tb_produtos.nome_prod_longo,
        tb_produtos.codigo_interno,
        tb_produtos.id_cat,
        tb_produtos.preco,
        tb_produtos.peso,
        tb_produtos.largura_centimetro,
        tb_produtos.altura_centimetro,
        tb_produtos.quantidade_estoque,
        tb_produtos.preco_promorcional,
        tb_produtos.foto_principal,
        tb_produtos.visivel
        LIMIT 4;
    ");

    foreach ($data as &$produto) {
        $preco = $produto['preco'];
        $centavos = explode(".", $preco);
        $produto['preco'] = number_format($preco, 0, ",", ".");
        $produto['centavos'] = end($centavos);
        $produto['parcelas'] = 10;
        $produto['parcela'] = number_format($preco/$produto['parcelas'], 2, ",", ".");
        $produto['total'] = number_format($preco, 2, ",", ".");
    }

    echo json_encode($data);

});

$app->get("/produto-:id_prod", function($id_prod){

    $sql = new Sql();

    $produtos = $sql->select("SELECT * FROM tb_produtos WHERE id_prod = $id_prod");

    $produto = $produtos[0];

    $preco = $produto['preco'];
    $centavos = explode(".", $preco);
    $produto['preco'] = number_format($preco, 0, ",", ".");
    $produto['centavos'] = end($centavos);
    $produto['parcelas'] = 10;
    $produto['parcela'] = number_format($preco/$produto['parcelas'], 2, ",", ".");
    $produto['total'] = number_format($preco, 2, ",", ".");

    require_once("view/shop-produto.php");

});

$app->get(
    '/cart',
    function () {
        
        require_once("view/cart.php");
        
    }
);

$app->get('/carrinho-dados', function(){

    $sql = new Sql();

    $result = $sql->select("CALL sp_carrinhos_get('".session_id()."')");

    $carrinho = $result[0];

    $sql = new Sql();

    $carrinho['produtos'] = $sql->select("CALL sp_carrinhosprodutos_list(".$carrinho['id_car'].")");

    $carrinho['total_car'] = number_format((float)$carrinho['total_car'], 2, ',', '.');
    $carrinho['subtotal_car'] = number_format((float)$carrinho['subtotal_car'], 2, ',', '.');
    $carrinho['frete_car'] = number_format((float)$carrinho['frete_car'], 2, ',', '.');

    echo json_encode($carrinho);

});

$app->get('/carrinhoAdd-:id_prod', function($id_prod){

    $sql = new Sql();

    $result = $sql->select("CALL sp_carrinhos_get('".session_id()."')");

    $carrinho = $result[0];

    $sql = new Sql();

    $sql->query("CALL sp_carrinhosprodutos_add(".$carrinho['id_car'].", ".$id_prod.")");

    header("location: cart");
    exit;

});

$app->delete("/carrinhoRemoveAll-:id_prod", function($id_prod){

    $sql = new Sql();

    $result = $sql->select("CALL sp_carrinhos_get('".session_id()."')");

    $carrinho = $result[0];

    $sql = new Sql();

    $sql->query("CALL sp_carrinhosprodutostodos_rem(".$carrinho['id_car'].", ".$id_prod.")");

    echo json_encode(array(
        "success"=>true
    ));

});

$app->post("/carrinho-produto", function(){

    $data = json_decode(file_get_contents("php://input"), true);

    $sql = new Sql();

    $result = $sql->select("CALL sp_carrinhos_get('".session_id()."')");

    $carrinho = $result[0];

    $sql = new Sql();

    $sql->query("CALL sp_carrinhosprodutos_add(".$carrinho['id_car'].", ".$data['id_prod'].")");

    echo json_encode(array(
        "success"=>true
    ));

});

$app->delete("/carrinho-produto", function(){

    $data = json_decode(file_get_contents("php://input"), true);

    $sql = new Sql();

    $result = $sql->select("CALL sp_carrinhos_get('".session_id()."')");

    $carrinho = $result[0];

    $sql = new Sql();

    $sql->query("CALL sp_carrinhosprodutos_rem(".$carrinho['id_car'].", ".$data['id_prod'].")");

    echo json_encode(array(
        "success"=>true
    ));

});

$app->get("/calcular-frete-:cep", function($cep){

    require_once("inc/php-calculo-frete-master/frete.php");

    $sql = new Sql();

    $result = $sql->select("CALL sp_carrinhos_get('".session_id()."')");

    $carrinho = $result[0];

    $sql = new Sql();

    $produtos = $sql->select("CALL sp_carrinhosprodutosfrete_list(".$carrinho['id_car'].")");

    $peso = 0; 
    $comprimento = 0;
    $altura = 0;
    $largura = 0;
    $valor = 0;

    foreach ($produtos as $produto) {
        $peso =+ $produto['peso'];
        $comprimento =+ $produto['comprimento'];
        $altura =+ $produto['altura'];
        $largura =+ $produto['largura'];
        $valor =+ $produto['preco'];
    }

    $cep = trim(str_replace('-', '', $cep));

    $frete = new Frete(
        $cepDeOrigem = '01418100', 
        $cepDeDestino = $cep, 
        $peso, 
        $comprimento, 
        $altura, 
        $largura, 
        $valor
    );

    $sql = new Sql();

    $sql->query("
        UPDATE tb_carrinhos 
        SET 
            cep_car = '".$cep."', 
            frete_car = ".$frete->getValor().",
            prazo_car = ".$frete->getPrazoEntrega()."
        WHERE id_car = ".$carrinho['id_car']
    );

    echo json_encode(array(
        'success'=>true
    ));

});

$app->run();










@font-face {
	font-family: 'OpenSans';
	src: url("../fonts/Open_Sans/OpenSans-Regular.ttf");
	font-size: 1em;
}
@font-face {
	font-family: 'OpenSans-Light';
	src: url("../fonts/Open_Sans/OpenSans-Light.ttf");
	font-size: 1em;
}
header {
	width: 100%;
	height: 150px;
	background-color: rgba(94, 41, 154, .8);
	z-index: 2;
    position: relative;
}
header .container {
	position: relative;
}
header .header-black {
	background-color: #000;
	height: 40px;
}
header .header-black li {
	background-image: url("../img/clubs.png");
	background-repeat: no-repeat;
	display: inline-block;
	margin: 4px;
}
header .header-black li.club-01 {
	background-position: 0px 0px;
}
header .header-black li.club-02 {
	background-position: -48px 0px;
}
header .header-black li.club-03 {
	background-position: -95px 0px;
}
header .header-black li.club-04 {
	background-position: -140px 0px;
}
header .header-black li.club-05 {
	background-position: -189px 0px;
}
header .header-black li.club-06 {
	background-position: -239px 0px;
}
header .header-black li.club-07 {
	background-position: -288px 0px;
}
header .header-black li.club-08 {
	background-position: -334px 0px;
}
header .header-black li.club-09 {
	background-position: -381px 0px;
}
header .header-black li.club-10 {
	background-position: -429px 0px;
}
header .header-black li.club-11 {
	background-position: -478px 0px;
}
header .header-black li.club-12 {
	background-position: -527px 0px;
}
header .header-black li.club-13 {
	background-position: -579px 0px;
}
header .header-black li.club-14 {
	background-position: -629px 0px;
}
header .header-black li.club-15 {
	background-position: -671px 0px;
}
header .header-black li.club-16 {
	background-position: -719px 0px;
}
header .header-black li.club-17 {
	background-position: -763px 0px;
}
header .header-black li.club-18 {
	background-position: -808px 0px;
}
header .header-black li.club-19 {
	background-position: -853px 0px;
}
header .header-black li.club-20 {
	background-position: -900px 0px;
}
header .header-black li.club-21 {
	background-position: -950px 0px;
}
header .header-black li.club-22 {
	background-position: -1000px 0px;
}
header .header-black li a {
	width: 32px;
	height: 32px;
	display: block;
}
header #logotipo {
	position: absolute;
	top: 20px;
	z-index: 3;
}
#banner h1.efeito {
	color:red;
	font-size:12em;
}
#menu {
	margin: 12px 0;
}
#menu li {
	display: inline-block;
	font-family: "OpenSans";
}
#menu li.search {
	width: 182px;
	transition-timing-function: cubic-bezier(1,-.91,.91,1);
	transition-duration: 1s;
}
#menu li.search.ativo {
	width: 300px;
}
#menu li.search input {
	background-color: #5C2D90;
	color: #fff;
	border: none;
	height: 30px;
	line-height: 30px;
	padding-left: 8px;
}
#menu li.search.ativo input {
	width: 300px;
}
#menu li.search ::-webkit-input-placeholder {
	color: #fff;	
}
#menu li.search button {
	background: none;
	border: none;
	position: absolute;
    right: 3px;
    top: 7px;
}
#menu li.search button i {
	font-size: 14px;
	color: rgba(255, 255, 255, .5);
}
#menu li a {
	color: #FFF;
	font-size: 16px;
	padding: 10px 25px;
	font-weight: bold;
}
#menu li.search .input-group {
	top: 8px;
}
#banner {
	width: 100%;
	height: 728px;
	position: relative;
	background: url("../img/banner.jpg") no-repeat;
	background-position: 0px -100px;
	top: -130px;
}
#banner h1 {
	transition:1s;
	color: #fff;
	top: 300px;
	position: relative;
	font-size: 92px;
	text-shadow:2px 2px 2px rgba(0, 0, 0, .45);
	font-family: 'OpenSans-Light';
	margin-left: 50px;
}
#banner h1 small {
	font-size: 32px;
	display: block;
	color: #FFF;
	font-family: 'OpenSans';
	font-weight: bold;
}
#news {
	position: relative;
    top: -110px;
}
#news h2 {
	color:#5E2799;
	font-family: 'OpenSans-Light';
	font-size: 48px;
	text-transform: uppercase;
	text-align: center;
}
#news hr {
	border:#FDE192 solid 8px;
	width: 200px;
	margin: 0 auto;
}
#news .thumbnails {
	margin-top: 20px;
}
#news .thumbnails h3 {
	color: #5E299A;
	font-size: 18px;
	font-family: 'OpenSans';
	font-weight: bold;
	margin-bottom: 0;
}
#news .thumbnails time {
	color:#A7A7A7;
	font-size: 18px;
	font-family: 'OpenSans';
}
#news .thumbnails .item-inner {
	padding: 10px;
}
#news .thumbnails .item-inner img {
	width: 100%;
}
#estatisticas {
	background-color: #5E299A;
	width: 100%;
	height: 200px;
	text-align: center;
}
#estatisticas p {
	color: #FDE092;
	text-transform: uppercase;
	font-family: 'OpenSans-Light';
	font-size: 64px;
	margin-top: 36px;
}
#estatisticas p small {
	color: #fff;
	font-size: 24px;
	display: block;
}
#call-to-action {
	text-align: center;
	margin-top: 105px;
}
#call-to-action h2 {
	color:#5E2799;
	font-family: 'OpenSans-Light';
	font-size: 48px;
	text-align: center;
}
#call-to-action hr {
	border:#FDE192 solid 8px;
	width: 200px;
	margin: 0 auto;
}
#call-to-action p {
	margin-top: 60px;
	margin-bottom: 40px;
	color: #656565;
}
#call-to-action .btn {
	min-width: 164px;
    height: 44px;
    line-height: 34px;
    border-radius: 0;
}
#call-to-action .btn-roxo {
    color: #fff;
    background-color: #5E299A;
    border-color: #5E299A;
}
#call-to-action .btn-amarelo {
    color: #000;
    background-color: #FDE192;
    border-color: #FDE192;
}
#call-to-action .row-max-400 {
	margin: 0 auto;
	max-width: 400px;
}
footer {
	margin-top: 110px;
}
footer .row {
	width: 100%;
	margin-left: 0;
}
footer .row p {
	line-height: 55px;
	margin-bottom: 0;
}
footer .row-cinza-claro {
	height: 240px;
	background-color: #171F26;
}
footer .row-cinza-escuro {
	height: 60px;
	background-color: #11171D;
	border-top: #242D37 1px solid;
}
footer .pull-left {
	font-family: 'OpenSans';
	font-size: 14px;
	color: #666;
}
footer .text-roxo {
	color: #623291;
	font-family: 'OpenSans';
	font-weight: bold;
	font-size: 14px;
}
footer .logotipo {
	margin-top: 28px;
}
footer .col-popular-post,
footer .col-links,
footer .col-get-in-touch {
	margin-top: 40px;
}
footer .row-cols h4 {
	font-family: 'OpenSans';
	font-size: 16px;
	color: #FFF;
	padding-bottom: 17px;
	border-bottom: #242D37 1px solid;
}
footer .row-cols h5 {
	color: #666;
	font-family: Arial;
	font-size: 14px;
	margin-bottom: 0;
}
footer .row-cols time {
	color: #FDE092;
	font-family: Arial;
	font-size: 14px;
}
footer .col-links a {
	color: #FFF;
	font-family: Arial;
	font-size: 14px;
}
footer .col-links .fa {
	margin: 0 6px;
}
footer .col-get-in-touch address {
	color:#666;
	font-family: Arial;
	font-size: 14px;
	margin-bottom: 6px;
}
footer .col-get-in-touch address span {
	display: inline-block;
}
footer .col-get-in-touch address i {
	position: relative;
	top: -14px;
}
footer .col-get-in-touch i {
	color: #9B9B9B;
	font-size: 20px;
	margin: 0 6px;

}
footer .col-get-in-touch a {
	color: #666;
}
footer .col-get-in-touch p {
	line-height: 20px;
}
footer .list-socials {
	margin-top: 4px;
}
footer .list-socials li {
	display: inline-block;
	margin-right: 8px;
}
footer .list-socials a {
	display: block;
	border: #9B9B9B 1px solid;
	width: 28px;
	height: 28px;
	line-height: 28px;
	border-radius: 14px;
	text-align: center;
}
footer .list-socials i {
	font-size: 16px;
	margin: 7px auto;
}
video {
	width: 60%;
}
#btn-bars, #btn-search,
#btn-news-prev, #btn-news-next {
	display: none;
}
.page-up {
	display: none!important;
}
/* Shop */
.text-arial-cinza {
	font-family: arial;
	font-size: 12px;
	color: #666;
}
.text-roxo {
	color: #6E3EA4;
}
#destaque-produtos-container {
	position: relative;
}
#destaque-produtos {
	margin: 30px auto;
}
#destaque-produtos .col-imagem {
	text-align: center;
}
#destaque-produtos .col-imagem img {
	max-width: 100%;
	max-height: 250px;
}
#destaque-produtos .item {
	display: inline-block;
}
#destaque-produtos .col-descricao h2 {
	font-family: arial;
	font-size: 20px;
	color: #666;
	margin-bottom: 10px;
}
#destaque-produtos .col-descricao .box-valor {
	width: 100%;
	position: relative;

}
#destaque-produtos .col-descricao .box-valor .text-reais {
	font-size: 18px;
    font-weight: bold;
    position: absolute;
    top: 13px;
    left: 28px;
}
#destaque-produtos .col-descricao .box-valor .text-valor {
	font-size: 50px;
	position: absolute;
    top: -17px;
    left: 54px;
}
#destaque-produtos .col-descricao .box-valor .text-valor-centavos {
	font-size: 30px;
	position: absolute;
    top: -10px;
    left: 182px;
}
#destaque-produtos .col-descricao .btn-comprar {
	font-size: 26px;
	padding: 10px 0;
}
#destaque-produtos .col-descricao .btn-comprar .fa {
	font-size: 34px;
}
#destaque-produtos .col-descricao .text-parcelas {
	margin-top: 20px;
}
#btn-destaque-prev {
    position: absolute;
    top: 140px;
    left: 0;
    background: none;
    border: none;
    font-size: 64px;
	color:#2A2A2A;
	outline:0;
}
#btn-destaque-next {
    position: absolute;
    top: 140px;
    right: 0;
    background: none;
    border: none;
    font-size: 64px;
	color:#2A2A2A;
	outline:0;
}
#promocoes .box-promocao {
	background-color: #6E3EA4;
	width: 100%;
	height: 150px;
	position: relative;
	color: #fff;
	text-align: center;
}
#promocoes .box-promocao.box-1 {
	font-family: arial;
	font-size: 15px;
    font-weight: bold;
    padding: 7px;
}
#promocoes .box-promocao.box-1 p {
	position: absolute;
	top: 58px;
}
#promocoes .box-promocao .text-ate {
	font-size: 20px;
    font-weight: bold;
    font-family: arial;
    position: absolute;
    left: 15px;
    top: 5px;
}
#promocoes .box-promocao .text-numero {
	font-size: 128px;
	font-family: 'OpenSans-Light';
	position: absolute;
    top: -10px;
    left: 15px;
}
#promocoes .box-promocao .text-porcento {
	font-size: 64px;
    font-family: 'OpenSans';
    position: absolute;
    top: 15px;
    right: 1px;
}
#promocoes .box-promocao .text-off {
	font-size: 42px;
    font-family: 'OpenSans-Light';
    position: absolute;
    top: 78px;
    right: 3px;
}
.box-produto-info a {
	text-decoration: none;
}
.box-produto-info h3 {
	font-size: 12px;
	font-family: arial;
	color: #666;
}
.box-produto-info .produto-img {
	width: 100%;
}
.box-produto-info .text-valor {
	font-size: 26px;
	font-weight: bold;
}
.title-default-roxo h2 {
	color: #5E2799;
    font-family: 'OpenSans-Light';
    font-size: 48px;
    text-transform: uppercase;
    text-align: center;
}
.title-default-roxo hr {
	border: #FDE192 solid 4px;
    width: 200px;
    margin: 0 auto;
}
#cart-products {
	margin-top: 20px;
}
#cart-products td {
	vertical-align: middle;
	color: #666;
}
#cart-products p {
	margin: 0;
	font-size: 12px;
	color: #666;
}
#cart-products .btn {
	border: none;
	background: none;
	outline: 0;
}
#cart-products .btn i {
	font-size: 32px;
}
#cart-products .btn i.fa-close {
	font-size: 14px;
}
#cart-products .form-control {
	text-align: center;
	border: none;
	background: none;
	box-shadow: none;
	outline: 0;
}
#cart-products th {
	font-weight: 100;
}
#cart-products img {
	max-width: 80px;
	max-height: 80px;
}
.box-outline-grey {
	border: #CCC 1px solid;
	height: 160px;
	text-align: center;
}
#calculo-de-frete .btn {
	background-color: #ccc;
	height: 42px;
	border-radius: 0;
}
#calculo-de-frete .form-control {
	height: 42px;
	border-radius: 0;
}
.box-cart-totais {
	background-color: #eee;
	height: 160px;
	padding: 10px;
}
.box-cart-totais .table>tbody>tr>td, 
.box-cart-totais .table>tbody>tr>th, 
.box-cart-totais .table>tfoot>tr>td, 
.box-cart-totais .table>tfoot>tr>th, 
.box-cart-totais .table>thead>tr>td, 
.box-cart-totais .table>thead>tr>th {
	border: none;
	padding: 14px;
}
.text-bold {
	font-weight: bold;
}
.btn-roxo {
	background-color: #5E299A;
	height: 42px;
	width: 164px;
	font-weight: bold;
	color: #fff!important;
	border-radius: 0;
}









/*Tamanho padrão para tablets*/
@media only screen and (max-width: 768px) {
	.header-black ul {
		display: none;
	}
}
/*Tamanho padrão para smartphones*/
@media only screen and (max-width: 480px) {
	.header-black ul, #menu{
		display: none;
	}
	header #logotipo {
		left: 32%;
		z-index: 10;
		transition: 1s;
	}
	header.open-menu #logotipo {
		transform: rotate(360deg);
	}
	#btn-bars, #btn-search {
		color: #fff;
		font-size: 22px;
		position: absolute;
		top: 4px;
		background: none;
		border: none;
		display: block;
	}
	#btn-bars {
		left: 4px;
	}
	#btn-search {
		right: 4px;
	}
	#banner {
		height: 317px;
		background-size: cover;
		background-position: 0;
		text-align: center;
	}
	#banner h1 {
		top: 180px;
		font-size: 48px;
		margin-left: 0;
	}
	#banner h1 small {
		font-size: 22px;
	}
	#news h2 {
		font-size: 32px;
	}
	#news hr {
		border-width: 4px;
	}
	.owl-carousel .owl-wrapper-outer {
		margin-left: 15px;
	}
	.thumbnails {
		text-align: center;
	}
	#news .thumbnails .item-inner img {
		width: 80%;
	}
	#btn-news-prev, #btn-news-next {
		background: none;
		border: none;
		color: #5E2699;
		font-size: 48px;
		display: block;
		position: absolute;
		top:130px;
		z-index: 1;
		outline: 0;
	}
	#btn-news-next {
		right: 15px;
	}
	#estatisticas {
		height: inherit;
	}
	#estatisticas p {
		margin-bottom: 40px;
		margin-top: 40px;
	}
	#call-to-action {
		margin-top: 69px;
	}
	#call-to-action hr {
		border-width: 4px;
	}
	#call-to-action p {
		margin-top: 40px;
		margin-bottom: 40px;
		margin-left: 15px;
		margin-right: 15px;
	}
	#call-to-action h2 {
		font-size: 32px;
		margin-left: 10px;
		margin-right: 10px;
	}
	#call-to-action .btn {
		min-width: 138px;
	}
	#call-to-action .btn-roxo {
		float: left;
	}
	#call-to-action .btn-amarelo {
		float: right;
	}
	#call-to-action .col-xs-6 {
		padding: 0;
	}
	footer {
		margin-top: 60px;
	}
	.copyright-mobile p {
		font-size: 10px;
		line-height: 0;
	}
	.copyright-mobile .pull-left {
		float: inherit!important;
	}
	footer .row p {
		text-align: center;
		line-height: 20px;
	}
	footer .row p:first-child {
		margin-top: 10px;
	}
	footer .text-roxo {
		margin-right: 10px;
	}
	footer .row {
		margin: 0;
	}
	footer .list-socials {
		position: absolute;
		width: 100%;
		left: 0;
		top: 50px;
	}
	footer .col-md-10 {
		padding: 0;
	}
	footer .list-socials a {
		width: 45px;
		height: 45px;
		border-radius: 50%;
	}
	footer .list-socials i {
		font-size: 30px;
	}
	footer .row-cinza-claro {
		height: 157px;
	}
	footer .btn-footer {
		width: 100%;
		background-color: #11171D;
		height: 44px;
		line-height: 35px;
	}
	footer .col-xs-6 {
		padding: 0;
		padding-right: 5px;
	}
	footer .col-xs-6:last-child {
		padding-right: 0;
		padding-left: 5px;
	}
	footer .hidden-sm-up {
		margin-top: -10px;
	}
	header .header-black {
		position: fixed;
		top: 0;
		width: 100%;
		z-index: 9;
	}
	footer .page-up {
		display: inline-block!important;
	}
	header #menu-mobile {
		position: fixed;
		top: 40px;
		background-color: #fff;
		width: 80%;
		height: 100%;
		left:-80%;
		transition: 1s;
		z-index: 5;
	}
	header.open-menu #menu-mobile {
		left: 0;
	}
	header.open-menu #menu-mobile-mask {
		position: fixed;
		width: 100%;
		height: 100%;
		top: 0;
		left: 0;
		background-color: rgba(0,0,0,.5);
		z-index: 4;
	}
	header.open-menu #logotipo {
		position: fixed;
		top: 50px;
		height: 76px;
		left: calc(40% - 33px);
	}
	header.open-menu #menu-mobile ul {
		margin: 20px;
		margin-top: 100px;
	}
	header.open-menu #menu-mobile li {
		text-align: center;
		border-top: #CCC 1px solid;
	}
	header.open-menu #menu-mobile li:last-child {
		border-bottom: #CCC 1px solid;
	}
	header.open-menu #menu-mobile li a {
		color: #633392;
		font-family: 'OpenSans';
		font-weight: bold;
		font-size: 16px;
		padding: 18px;
    	display: block;
	}
	header.open-menu .bar-close {
		position: absolute;
		bottom: 40px;
		background-color: #633492;
		height: 40px;
		width: 100%;
	}
	header.open-menu .bar-close .btn-close {
		background:none;
		border: none;
		color: #fff;
		font-size: 22px;
	}
	header #input-search-mobile {
		transition: 1s;
		top: -40px;
		position: fixed;
		width: 70%;
		left: 15%;
		background-color: #000;
		border: none;
		height: 40px;
		color: #fff;
		outline: 0;
	}
	header.open-search #input-search-mobile {
		top: 0;
	}
	header.open-search #logotipo {
		z-index: 9;
	}
}









<footer>
			
			<div class="row row-cinza-claro">
				
				<div class="container">
					
					<div class="row">
						
						<div class="col-md-2 text-center hidden-xs">
							
							<img class="logotipo" src="img/orlando-logo.png" alt="Logotipo">

						</div>
						<div class="col-md-10">
							
							<div class="row row-cols">
								<div class="col-md-4 col-popular-post hidden-xs">
									
									<h4>POPULAR POSTS</h4>

									<ul class="list-unstyled">
										<li>
											<h5>Neque porro quisquam est, quister.</h5>
											<time>January 01, 2016</time>
										</li>
										<li>
											<h5>Neque porro quisquam est, quister.</h5>
											<time>January 01, 2016</time>
										</li>

									</ul>

								</div>
								<div class="col-md-4 col-links hidden-xs">
									
									<h4>LINKS</h4>

									<ul class="list-unstyled">
										<li><a href="#"><i class="fa fa-angle-right"></i>Tickets</a></li>
										<li><a href="#"><i class="fa fa-angle-right"></i>News</a></li>
										<li><a href="#"><i class="fa fa-angle-right"></i>Schedule</a></li>
									</ul>

								</div>
								<div class="col-md-4 col-get-in-touch">
									
									<h4 class="hidden-xs">GET IN TOUCH</h4>

									<address class="hidden-xs">
										<i class="fa fa-map-marker"></i> <span>618 E. South Street, Suite 510<br/>Orlando, FL 32801</span>
									</address>

									<p class="hidden-xs"><a href="tel:1855ORLCITY"><i class="fa fa-phone"></i>1.855.ORL.CITY</a></p>
									
									<div class="row-fluid visible-xs">
										<div class="col-xs-6">
											<a href="#" class="btn btn-footer "><i class="fa fa-map-marker"></i>Location</a>
										</div>
										<div class="col-xs-6">
											<a href="#" class="btn btn-footer"><i class="fa fa-phone"></i>Call</a>
										</div>
									</div>

									<ul class="list-unstyled list-socials">
										<li>
											<a href="#" target="_blank"><i class="fa fa-facebook"></i></a>
										</li>
										<li>
											<a href="#" target="_blank"><i class="fa fa-twitter"></i></a>
										</li>
										<li>
											<a href="#" target="_blank"><i class="fa fa-instagram"></i></a>
										</li>
										<li>
											<a href="#" target="_blank"><i class="fa fa-pinterest-p"></i></a>
										</li>
										<li class="page-up">
											<a href="#" id="page-up"><i class="fa fa-chevron-up"></i></a>
										</li>
									</ul>

								</div>
							</div>

						</div>

					</div>

				</div>

			</div>

			<div class="row row-cinza-escuro">
				
				<div class="container copyright-mobile">
					
					<p class="pull-left">Copyright © Orlando City Soccer 2016. All rights reserved.</p>
					<p class="pull-right text-roxo">Created by HCODE in Udemy</p>

				</div>

			</div>

		</footer>

		<script src="lib/jquery/jquery.min.js"></script>
		<script src="lib/owl.carousel/owl-carousel/owl.carousel.min.js"></script>
		<script src="lib/bootstrap/js/bootstrap.min.js"></script>
		<script src="lib/raty/lib/jquery.raty.js"></script>
		<script src="js/efeitos.js"></script>

	</body>
</html>









<?php include_once("header.php");?>

<section ng-controller="destaque-controller">
	
	<div class="container" id="destaque-produtos-container">

		<div id="destaque-produtos">
			
			<div class="item" ng-repeat="produto in produtos">
				
				<div class="col-sm-6 col-imagem">
					<a href="produto-{{produto.id_prod}}">
						<img src="img/produtos/{{produto.foto_principal}}" alt="{{produto.nome_prod_longo}}">
					</a>
				</div>
				<div class="col-sm-6 col-descricao">
					<h2>{{produto.nome_prod_longo}}</h2>
					<div class="box-valor">
						<div class="text-noboleto text-arial-cinza">no boleto</div>
						<div class="text-por text-arial-cinza">por</div>
						<div class="text-reais text-roxo">R$</div>
						<div class="text-valor text-roxo">{{produto.preco}}</div>
						<div class="text-valor-centavos text-roxo">,{{produto.centavos}}</div>
						<div class="text-parcelas text-arial-cinza">ou em até {{produto.parcelas}}x de R$ {{produto.parcela}}</div>
						<div class="text-total text-arial-cinza">total a prazo R$ {{produto.total}}</div>	
					</div>
					<a href="carrinhoAdd-{{produto.id_prod}}" class="btn btn-comprar text-roxo"><i class="fa fa-shopping-cart"></i> compre agora</a>
				</div>

			</div>

		</div>

		<button type="button" id="btn-destaque-prev"><i class="fa fa-angle-left"></i></button>
		<button type="button" id="btn-destaque-next"><i class="fa fa-angle-right"></i></button>

	</div>

	<div id="promocoes" class="container">
		
		<div class="row">
			<div class="col-md-2">
				
				<div class="box-promocao box-1">
					<p>escolha por desconto</p>
				</div>

			</div>
			<div class="col-md-10">
				
				<div class="row-fluid">
					<div class="col-md-3">
						<div class="box-promocao">
							<div class="text-ate">até</div>
							<div class="text-numero">40</div>
							<div class="text-porcento">%</div>
							<div class="text-off">off</div>
						</div>
					</div>
					<div class="col-md-3">
						<div class="box-promocao">
							<div class="text-ate">até</div>
							<div class="text-numero">60</div>
							<div class="text-porcento">%</div>
							<div class="text-off">off</div>
						</div>
					</div>
					<div class="col-md-3">
						<div class="box-promocao">
							<div class="text-ate">até</div>
							<div class="text-numero">80</div>
							<div class="text-porcento">%</div>
							<div class="text-off">off</div>
						</div>
					</div>
					<div class="col-md-3">
						<div class="box-promocao">
							<div class="text-ate">até</div>
							<div class="text-numero">85</div>
							<div class="text-porcento">%</div>
							<div class="text-off">off</div>
						</div>
					</div>
				</div>

			</div>
		</div>

	</div>

	<div id="mais-buscados" class="container">
		
		<div class="row text-center title-default-roxo">
			<h2>os mais buscados</h2>
			<hr>	
		</div>

		<div class="row">
			
			<div class="col-md-3" ng-repeat="produto in buscados">
				<div class="box-produto-info">
					<a href="produto-{{produto.id_prod}}">
						<img src="img/produtos/{{produto.foto_principal}}" alt="{{produto.nome_prod_longo}}" class="produto-img">
						<h3>{{produto.nome_prod_longo}}</h3>
						<div class="estrelas" data-score="{{produto.media}}"></div>
						<div class="text-qtd-reviews text-arial-cinza">({{produto.total_reviews}})</div>
						<div class="text-valor text-roxo">R$ {{produto.total}}</div>
						<div class="text-parcelado text-arial-cinza">{{produto.parcelas}}x de R$ {{produto.parcela}} sem juros</div>
					</a>
				</div>

			</div>

		</div>

	</div>

</section>

<?php include_once("footer.php");?>

<script>
angular.module("shop", []).controller("destaque-controller", function($scope, $http){

	$scope.produtos = [];
	$scope.buscados = [];

	var initCarousel = function(){

		$("#destaque-produtos").owlCarousel({
	 
	      autoPlay: 5000,
	      items : 1,
	      singleItem: true
	 
	  	});

	  	var owlDestaque = $("#destaque-produtos").data('owlCarousel');

	  	$('#btn-destaque-prev').on("click", function(){

	  		owlDestaque.prev();

	  	});

	  	$('#btn-destaque-next').on("click", function(){

	  		owlDestaque.next();

	  	});

	};

	$http({
	  method: 'GET',
	  url: 'produtos'
	}).then(function successCallback(response) {

	    $scope.produtos = response.data;

	    setTimeout(initCarousel, 1000);

	  }, function errorCallback(response) {
	    // called asynchronously if an error occurs
	    // or server returns response with an error status.
	  });

	$http({
	  method: 'GET',
	  url: 'produtos-mais-buscados'
	}).then(function successCallback(response) {

	    $scope.buscados = response.data;

	  }, function errorCallback(response) {
	    // called asynchronously if an error occurs
	    // or server returns response with an error status.
	  });

	

});
angular.module("shop", []).controller("destaque-controller", function($scope, $http){

	$scope.produtos = [];
	$scope.buscados = [];

	var initCarousel = function(){

		$("#destaque-produtos").owlCarousel({
	 
	      autoPlay: 5000,
	      items : 1,
	      singleItem: true
	 
	  	});

	  	var owlDestaque = $("#destaque-produtos").data('owlCarousel');

	  	$('#btn-destaque-prev').on("click", function(){

	  		owlDestaque.prev();

	  	});

	  	$('#btn-destaque-next').on("click", function(){

	  		owlDestaque.next();

	  	});

	};

	$http({
	  method: 'GET',
	  url: 'produtos'
	}).then(function successCallback(response) {

	    $scope.produtos = response.data;

	    setTimeout(initCarousel, 1000);

	  }, function errorCallback(response) {
	    // called asynchronously if an error occurs
	    // or server returns response with an error status.
	  });

	var initEstrelas = function(){

		$('.estrelas').each(function(){

	  		$(this).raty({
		  		starHalf    : 'lib/raty/lib/images/star-half.png',                                // The name of the half star image.
				starOff     : 'lib/raty/lib/images/star-off.png',                                 // Name of the star image off.
				starOn      : 'lib/raty/lib/images/star-on.png',
				score		: parseFloat($(this).data("score"))
		  	});

	  	});

	};

	$http({
	  method: 'GET',
	  url: 'produtos-mais-buscados'
	}).then(function successCallback(response) {

	    $scope.buscados = response.data;

	    setTimeout(initEstrelas, 1000);

	  }, function errorCallback(response) {
	    // called asynchronously if an error occurs
	    // or server returns response with an error status.
	  });

	

});
</script>









<?php include_once("header.php");?>

<section>
	
	<div class="container" id="destaque-produtos-container">

		<div id="destaque-produtos">
			
			<div class="col-sm-6 col-imagem">
				<img src="img/produtos/<?=$produto['foto_principal']?>" alt="<?=$produto['nome_prod_longo']?>">
			</div>
			<div class="col-sm-6 col-descricao">
				<h2><?=$produto['nome_prod_longo']?></h2>
				<div class="box-valor">
					<div class="text-noboleto text-arial-cinza">no boleto</div>
					<div class="text-por text-arial-cinza">por</div>
					<div class="text-reais text-roxo">R$</div>
					<div class="text-valor text-roxo"><?=$produto['preco']?></div>
					<div class="text-valor-centavos text-roxo">,<?=$produto['centavos']?></div>
					<div class="text-parcelas text-arial-cinza">ou em até <?=$produto['parcelas']?>x de R$ <?=$produto['parcela']?></div>
					<div class="text-total text-arial-cinza">total a prazo R$ <?=$produto['total']?></div>	
				</div>
				<a href="carrinhoAdd-<?=$produto['id_prod']?>" class="btn btn-comprar text-roxo"><i class="fa fa-shopping-cart"></i> compre agora</a>
			</div>

		</div>

	</div>

</section>

<?php include_once("footer.php");?>








<?php include_once("header.php");?>

<link rel="stylesheet" href="lib/plyr/dist/plyr.css">

<section>
	
	<div id="call-to-action">
		
		<div class="container">

			<div class="row text-center">
				<h2>Videos</h2>
				<hr>	
			</div>

			<div class="row">
				
				<div class="player">
					<video src="mp4/highlights.mp4" controls poster="img/highlights.jpg">
						
						<track kind="subtitles" label="Português (Brasil)" src="vtt/legendas.vtt" srclang="pt-br" default>

					</video>
				</div>
				<input type="range" id="volume" min="0" max="1" step="0.01" value="1">

				<button type="button" id="btn-play-pause" class="btn btn-success">PLAY</button>

				<!-- <audio src="mp3/audio.mp3"></audio> -->

			</div>

		</div>

	</div>

	<div id="news" class="container" style="top:0">
		
		<div class="row text-center">
			<h2>Latest News</h2>
			<hr>	
		</div>				

		<div class="row thumbnails">
			<div class="item" data-video="highlights">
				<div class="item-inner">
					<img src="img/highlights.jpg" alt="Noticia">
					<h3>Highlights</h3>
				</div>
			</div>
			<div class="item" data-video="Orlando_City_Foundation_2015">
				<div class="item-inner">
					<img src="img/Orlando_City_Foundation_2015.jpg" alt="Noticia">
					<h3>Orlando City Foundation 2015</h3>
				</div>
			</div>
			<div class="item" data-video="highlights">
				<div class="item-inner">
					<img src="img/highlights.jpg" alt="Noticia">
					<h3>Highlights</h3>
				</div>
			</div>
			<div class="item" data-video="Orlando_City_Foundation_2015">
				<div class="item-inner">
					<img src="img/Orlando_City_Foundation_2015.jpg" alt="Noticia">
					<h3>Orlando City Foundation 2015</h3>
				</div>
			</div>
			<div class="item" data-video="highlights">
				<div class="item-inner">
					<img src="img/highlights.jpg" alt="Noticia">
					<h3>Highlights</h3>
				</div>
			</div>
			<div class="item" data-video="Orlando_City_Foundation_2015.mp4">
				<div class="item-inner">
					<img src="img/Orlando_City_Foundation_2015.jpg" alt="Noticia">
					<h3>Orlando City Foundation 2015</h3>
				</div>
			</div>
		</div>

	</div>

</section>

<?php include_once("footer.php");?>

<script src="lib/plyr/dist/plyr.js"></script>
<script>
(function(d, p){
    var a = new XMLHttpRequest(),
        b = d.body;
    a.open("GET", p, true);
    a.send();
    a.onload = function(){
        var c = d.createElement("div");
        c.style.display = "none";
        c.innerHTML = a.responseText;
        b.insertBefore(c, b.childNodes[0]);
    }
})(document, "lib/plyr/dist/sprite.svg");
</script>
<script>
$(function(){

	$(".thumbnails .item").on("click", function(){

		$("video").attr({
			"src":"mp4/"+$(this).data('video')+".mp4",
			"poster":"img/"+$(this).data('video')+".jpg"
		});

	});

	$("#volume").on("mousemove", function(){

		$("video")[0].volume = parseFloat($(this).val());

	});

	$("#btn-play-pause").on("click", function(){

		

		var video = $("video")[0];

		if ($(this).hasClass("btn-success")) {
			$(this).text("STOP");
			video.play();
		} else {
			$(this).text("PLAY");
			video.pause();
		}

		$(this).toggleClass("btn-success btn-danger");

	});

	plyr.setup();//Disparando player PLYR

});
</script>










<?php include_once("header.php");?>

<section  ng-controller="cart-controller">
	
	<div class="container">

		<div class="row text-center title-default-roxo" style="margin:40px auto;">
			<h2>carrinho de compras</h2>
			<hr>	
		</div>

		<table id="cart-products" class="table table-bordered">
			<thead>
				<tr>
					<th colspan="2">Produto(s)</th>
					<th class="text-center">Quantidade</th>
					<th class="text-center">Entrega</th>
					<th class="text-center">Valor Unitário</th>
					<th class="text-center">Valor Total</th>
					<th>&nbsp;</th>
				</tr>
			</thead>
			<tbody>
				<tr ng-repeat="produto in produtos">
					<td class="text-center"><img src="img/produtos/{{produto.foto_principal}}"></td>
					<td>{{produto.nome_prod_long}}</td>
					<td class="col-xs-2">
						<div class="input-group">
					      <span class="input-group-btn">
					        <button class="btn text-roxo" ng-click="removeQtd(produto)" type="button"><i class="fa fa-chevron-down"></i></button>
					      </span>
					      <input type="text" class="form-control" ng-model="produto.qtd_car">
					      <span class="input-group-btn">
					        <button class="btn text-roxo" ng-click="addQtd(produto)" type="button"><i class="fa fa-chevron-up"></i></button>
					      </span>
					    </div>
					</td>
					<td class="text-center col-xs-2">
						<p>Entrega para o<br/>CEP: {{carrinho.cep}}</p>
						<strong class="text-roxo">{{carrinho.prazo}}</strong>
					</td>
					<td class="text-center">R$ {{produto.preco}}</td>
					<td class="text-center">R$ {{produto.total}}</td>
					<td class="text-center"><button ng-click="removeAll(produto)" class="btn text-roxo" type="button"><i class="fa fa-close"></i></button></td>
				</tr
			</tbody>
		</table>

		<div id="calculo-de-frete" class="row">
			<div class="col-sm-8">
				<div class="box-outline-grey">
					<p style="margin:28px auto;">Simule o prazo de entrega e o frete para seu CEP abaixo:</p>
					<div class="input-group col-xs-4" style="margin:0 auto;">
				      <input type="text" class="form-control" ng-model="cep">
				      <span class="input-group-btn">
				      	<button class="btn btn-default" ng-click="calcularFrete(cep)" type="button">Calcular Frete</button>
				      </span>
				    </div>
				</div>
			</div>
			<div class="col-sm-4">
				<div class="box-cart-totais">
					<table class="table">
						<tr>
							<td>Subtotal ({{produtos.length}} item):</td>
							<td class="text-right">R$ {{carrinho.subtotal}}</td>
						</tr>
						<tr>
							<td>Frete:</td>
							<td class="text-right">R$ {{carrinho.frete}}</td>
						</tr>
						<tr style="border-top:#999 1px solid;">
							<td class="text-roxo text-bold">Total:</td>
							<td class="text-roxo text-bold text-right">R$ {{carrinho.total}}</td>
						</tr>
					</table>
				</div>
			</div>
		</div>

		<button type="button" class="btn btn-roxo pull-right" style="margin-top:10px">comprar</button>

	</div>

</section>

<?php include_once("footer.php");?>

<script>
angular.module("shop", []).controller("cart-controller", function($scope, $http){

	var carregarCarrinho = function(){

		$http({
			method:'GET',
			url:'carrinho-dados'
		}).then(function(response){

			$scope.carrinho = {
				cep:response.data.cep_car,
				subtotal:response.data.subtotal_car,
				frete:response.data.frete_car,
				total:response.data.total_car,
				prazo:response.data.prazo_car+' dias úteis'
			};

			$scope.produtos = response.data.produtos;

		}, function(response){

			console.error(response);

		});

	};

	$scope.addQtd = function(_produto){

		$http({
			method:'POST',
			url:'carrinho-produto',
			data:JSON.stringify({
				id_prod:_produto.id_prod
			})
		}).then(function(response){

			carregarCarrinho();

		}, function(){



		});

	};

	$scope.removeQtd = function(_produto){

		$http({
			method:'DELETE',
			url:'carrinho-produto',
			data:JSON.stringify({
				id_prod:_produto.id_prod
			})
		}).then(function(response){

			carregarCarrinho();

		}, function(){



		});

	};

	$scope.removeAll = function(_produto){

		$http({
			method:'DELETE',
			url:'carrinhoRemoveAll-'+_produto.id_prod
		}).then(function(response){

			carregarCarrinho();

		}, function(){



		});

	};

	$scope.calcularFrete = function(_cep){

		$http({
			method:'GET',
			url:'calcular-frete-'+_cep
		}).then(function(response){

			carregarCarrinho();

		}, function(){



		});

	};

	carregarCarrinho();

});
</script>









