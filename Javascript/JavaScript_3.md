<h3> Validação </h3>
  <p>Quando vamos validar qualquer campo no mundo da programação, o bom é sempre validar no back tanto no front.</p>
  <p>Nesse arquivo iremos aprender a validar inputs com JS</p>
  <h2>HTML</h2>

<pre>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form onSubmit="return validate();">
        <input type="" id="name">
        <button type="submit">Enviar</button>
    </form>
    <script src="teste.js"></script>
</body>
</html>
</pre>


<h2>JS</h2>
<p>O retorno após validação é escolha pessoal</p>
<pre>
function validate() 
{
    var validade = document.getElementById("name").value == "" ? console.log('Por favor, insira os dados em todos os campos corretamente') : console.log('Cadastrado com sucesso');
    return false;
}
</pre>
