<!DOCTYPE html><!-- Declaração para informar ao navegador qual é a versão do html utilizada no arquivo-->
<html lang="pt-br"> <!--Aqui começa tudo o que irá na pagina e colocamos o lang para definir o idioma da pagina -->
	<head> <!--Cabeçalho da pagina, o conjunto de informações da pagina. Essas informações não são visiveis no site -->
		<meta charset="utf-8"> <!-- Conjunto de caracteres a ser utilizado na exibição do conteúdo do site. Este é o conjunto mais utilizado na web-->
		
		<title>Inicio</title> <!-- Para colocar titulo na aba do navegador -->
		
		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.0/css/all.min.css"> <!--Para pegar a logo lateral -->
		
		<link rel="icon" type="image/x-icon" href="\Users\Beatr\Desktop\FrontEnd3\B.png"> <!-- Para colocar icone na aba do navegador -->
		
		<link rel="stylesheet" href="styleInicio.css"> <!-- Para arquivo abrir o arquivo CSS na pagina html-->
		
	</head>

	<body> <!--Aqui começa o corpo do site, todo conteúdo visível --> 
		
		<div class="background"> <!-- Essa é a parte do fundo da pagina, no css adicionamos uma imagem e tudo que estives dentro, estara em cima da imagem -->
			<header> <!-- Cabeçalho para mudar as paginas  -->
				
				<div class="logo">	<!--- Logo lateral -->
				<i class="fa-solid fa-b"></i> <!-- Pegou o B do site colocado no head -->
				</div>
			
				<div class="cabeçalho-link"> <!--- Uma div para configurar o cabeçalho no css -->
					<li> <!-- Uma lista para alinhar os itens do cabeçalho -->
						<a href="Inicio.html"> Inicio </a> <!-- Aqui ira levar para a pagina Inicio -->
					</li>
					<li>
						<a href="Sobre.html"> Sobre </a> <!-- Aqui ira levar para a pagina Sobre -->
					</li>
					<li>
						<a href="Troia.html"> Troia </a> <!-- Aqui ira levar para a pagina Troia -->
					</li>
					<a href="contato.html"> <button> Entre em Contato </button> </a> <!-- Aqui ira levar para a pagina Entre em contato -->
				</div>
			</header>
				
			<div class="container-text"> <!-- Uma div para configurar tudo no css -->
				<div class="text">
					<h1> Bem-Vindo!</h1>  <!-- Linha principal da pagina -->
					<h2> Meu nome é<span><br>Beatriz</span> </h2> <!---Span é para estilizar apenas o nome --->
					<p>Estou no 1º período de Análise e Desenvolvimento de Sistemas<br> <!---Paragrafo com um breve resumo --->
					Este é meu primeiro portfólio desenvolvido em <span>HTML</span> e <span>CSS</span> </p>
				</div>
			</div> 
				
		</div> 
	</body>
</html>
