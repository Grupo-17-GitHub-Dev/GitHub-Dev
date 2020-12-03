# Acessando parâmetros GET no php!

o vetor `$_GET` contém todas as variáveis passadas ao php via HTTP GET (`127.0.0.1/projeto?nome=gabs`)

o primeiro passo para utilizar parâmetros é verificar se ele foi setado, isso é importante pois a tentativa de uso de uma variável não definida pode quebrar a aplicação.

para isso, basta utilizar a função `isset()`, passando o nome do parâmetro como índice, e validar seu retorno.

    if(isset($_GET['nome'])){
    
    }

para caso o resultado for falso, vamos responder com uma mensagem de erro

    if(isset($_GET['nome'])){
    
    } else {
       echo  'informe seu nome na url para uma surpresa';
    }
agora, iremos guardar o valor do parâmetro em uma variável e criar a frase da resposta baseada nela;

    $nome = $_GET['nome'];
    $frase =  "Olá, seja bem vindo, $nome!";
note que, ao usar aspas duplas, o usuário de variáveis na criação da string.

após isso, vamos imprimir a frase utilizando o comando echo

    echo $frase;

assim, nosso código ficará da seguinte maneira

    <?php
    if(isset($_GET['nome'])){
        $nome = $_GET['nome'];
        $frase = "Olá, seja bem vindo, $nome!";
        echo $frase;
    } else {
        echo 'informe seu nome na url para uma surpresa';
    }
