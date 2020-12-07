<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Cadastro Escolar</title>
		<article>


			<img src="img/escola.png"alt="some text" width=300 height=200>
		</article>
	

</head>
<body>
	<h1>Cadastro do aluno</h1>
	
	<form action="" method="post" enctype="multipart/form-data">
		<div>
			<label for="">Nome</label>
			<input type="nome" required="required" placeholder="Digite seu nome" type="text">
		</div>

		<div>
			<label for="">E-mail</label>
			<input type="email" required="required" placeholder="Digite seu E-mail" type="text">
		</div>

		<div>
			<label for="">Idade</label>
			<input type="idade" required="required" placeholder="Digite sua Idade" type="text">
		</div>

		<div>
			<label for="">Qual sua Cidade</label>
			<select required="required" name="Cidade">
			<option selected="selected" value="">Cidade</option>
			<option value="1">Cabo</option>
			<option value="2">Recefe</option>
			<option value="3">Olinda</option>
			</select>
		</div>

		<div>
			<p>Escolha seu sexo</p>
			<label for="sexo1"><input name="sexo" id="sexo1" type="radio">Masculino</label>
			<label for="sexo2"><input name="sexo" id="sexo2" type="radio">feminino</label>
			<label for="sexo3"><input name="sexo" id="sexo3" type="radio">Entre outros</label>
		</div>
	</form>

	
