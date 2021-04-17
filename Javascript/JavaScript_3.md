<h3> Validação </h3>
  <p>Quando vamos validar qualquer campo no mundo da programação, o bom é sempre validar no back tanto no front.</p>
  <p>Nesse arquivo iremos aprender a validar inputs com JS</p>
  <h2>HTML</h2>

<pre>
#<form onSubmit="return validate();">
#<input type="" id="name">
#<button type="submit">Enviar</button>
#</form>
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
