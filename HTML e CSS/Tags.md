# Lista das principais Tags que usamos no dia a dia com o HTML.

## Você poderá copiar toda a estrutura a seguir e colar dentro da Tag Body do HTML para vê-la no seu computador.

### As tags com <!- - [texto] - -> são comentários, utilizamos ela aqui para a explicação do código.

<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
    <!-- Tags são a base do HTML, são elementos que criam
        toda a estrutura da página. Possuem em sua grande maioria
        abertura, caracterizada pela estrutura <[nome da tag]> 
        e de fechamento, caracterizado pela estrutura </[nome da tag]>-->

    <!-- Aqui você verá as principais Tags do HTML usadas no dia a dia -->

    <!-- Tag de Título - Heading -->
    <h1>Seção de Títulos - Título Principal</h1>
    <!-- Só deve ter uma dessa tag por página criada -->

    <!-- Tags de Sub-Títulos - Numeradas por Ordem de Prioridade dos Sub-Títulos -->
    <h2>Sub-Título 1</h2>
    <h3>Sub-Título 2</h3>
    <h4>Sub-Título 3</h4>
    <h5>Sub-Título 4</h5>
    <h6>Sub-Título 5</h6>

    <!-- Tag de Linha Horizontal - Não Necessita de Fechamento -->
    <hr>

    <h2>Seção de Textos</h2>

    <!-- Tag de Parágrafo -->
    <p>Parágrafo</p>

    <!-- Tag de Parágrafo com Tag de Negrito - Texto dentro da tag Strong ficará em negrito -->
    <p><strong>Texto com Negrito</strong></p>

    <!-- Tag de Parágrafo com outro tipo de Tag de Negrito - Texto dentro da tag Bold também ficará em negrito -->
    <p><b>Texto com Negrito 2</b></p>

    <!-- A diferença entre a Tag <B> e a Tag <Strong> é que a Tag Bold não tem semântica de importância,
        o que faz com que o texto em negrito não se destaque em importância do resto do texto, enquanto
        a tag Strong tem semâtica, fazendo com que programas de leitura e o próprio navegador identifiquem
        que essa parte do texto possui uma maior importância que as demais -->

    <!-- Tag de Parágrafo com Tag de Underline - Texto dentro da tag <u> ficará com sublinado -->
    <p><u>Texto com Sublinado</u></p>

    <!-- Tag de Parágrafo com Tag de Itálico - Texto dentro da tag <i> ficará em itálico -->
    <p><i>Texto com itálico</i></p>

    <!-- Tag de Parágrafo com outro tipo de tag de Itálico - Texto dentro da tag <em> ficará em itálico -->
    <p><em>Texto com itálico 2</em></p>

    <!-- A diferença entre a Tag <i> e a Tag <em> é que a Tag <i> não tem semântica de importância,
        o que faz com que o texto em itálico não se destaque em importância do resto do texto, enquanto
        a tag <em> tem semâtica, fazendo com que programas de leitura e o próprio navegador identifiquem
        que essa parte do texto possui uma maior importância que as demais -->

    <!-- Tag de Parágrafo com Tag Small - Diminui o texto, deixando-o pequeno - Útil para descrições de imagens -->
    <p><small>Texto pequeno</small></p>

    <!-- Tag de Parágrafo com Tag de Deletado - Excluí qualquer texto que estiver dentro, deixando ele riscado como
        um item concluído em uma lista -->
    <p><del>Texto Deletado</del></p>

    <!-- Tag de Parágrafo com Tag de Marcação - Destaca o texto que estiver dentro da tag Mark como um marca texto -->
    <p><mark>Texto Destacado</mark></p>

    <!-- Tag de Parágrafo com Tag de Superior - Deixa o texto dentro da tag Sup no superior do texto, como um expoênte,
        sobscrito -->
    <p>1<sup>o</sup> lugar</p>

    <!-- Tag de Parágrafo com Tag de Inferior - Deixa o texto dentro da tag Sub no inferior do texto, subscrito -->
    <p>H<sub>2</sub>O</p>

    <!-- Qualquer uma dessas Tag de manipulação de texto podem ser usadas em qualquer pedaço do texto, necessitando
        apenas que o texto fique dentro dela -->
    <p>Esse texto possui <b>negrito</b>, <i>itálico</i> e <u>sublinado</u></p>

    <!-- Tag Span - Elemento que preenche qualquer espaço em branco de acordo
        com o tamanho do conteúdo dentro dele - Caso sobre espaço em um elemento
        anterior, e o conteúdo dentro do span couber, o conteúdo da tag span se 
        posicionará na mesma linha do elemento anterior -->
    <span>Um parágrafo</span>
    <span>usando 2 tags span</span>

    <!-- Tag de quebra de linha - Faz com que a linha seja quebrada e o próximo elemento seja
        mostrado em uma nova linha -->
    <br>

    <br>

    <span>Parágrafo usando a tag span, porém após quebrar duas linhas</span>
    <!-- Ao usar a quebra de linha, você define que a linha anterior não poderá ser usada,
        fazendo com que até os elementos que pudesem ocupar espaços em branco, como o caso do 
        span, tenham que começar nessa nova linha -->

    <hr>

    <h2>Seção de Links</h2>

    <!-- Tag de link - O endereço ao qual o usuário será enviado ao clicar fica dentro do href="" -->
    <a href="https://www.google.com.br">Ir para o google - tag de link</a>
    
    <br>

    <br>

    <!-- Tag de link com target (alvo) = _blank - Envia para uma nova aba em branco ao clicar,
    extremamente útil no desenvolvimento de sites, pois o usuário não sai do site ao clicar no link -->
    <a href="https://www.google.com.br" target="_blank"> Ir para o google - link com Target para uma nova guia</a>

    <!-- Tag de link encapsulando outro elemento,
        permitindo deixar o elemento clicável como um link - Pode ser usado com 
        imagens, textos, áreas do site -->
    <a href="https://www.google.com" title="Site do google">
        <p>ir para o google - link em uma tag de parágrafo</p>
    </a>
    <!-- O title dentro de uma tag link é usado para definir um texto que irá aparecer
        quando o usuário passar o cursor do mouse por cima do link -->

    <!-- Link de Âncora Interna - Ao clicar no link manda para uma seção da própria página -->
    <a href="#lista">Ir para a seção de listas da página - Link para uma seção da própria página</a>
    <!-- É usado o ID do elemento como link - ID é um identificador/nome que você pode dar para um
        elemento - o ID, após definido, é representado pelo sinal de # -->

    <hr>

    <h2 id="lista">Seção de Listas</h2>
    <!-- Foi definido um ID para esse elemento para que ele pudesse ser acessado por uma tag de âncora -->
    <!-- ID é usado exclusivamente para dar um nome a um elemento,
        não se pode repetir o mesmo nome de ID para múltiplos elementos, pois será identificado apenas
        o primeiro elemento achado com esse nome, sendo ignorado os demais -->

    <h3>Lista Não Ordenada</h3>

    <!-- Tag de Lista Não Ordenada - Sem Numeração -->
    <ul>
        <!-- Tag de itens de uma lista - Que irão compor a lista não ordenada -->
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>

    <h3>Lista Ordenada</h3>

    <!-- Tag de Lista ordenada - Com Numeração -->
    <ol>
        <!-- Tag de itens de uma lista - Igual a Não Ordenada - Irá compor a lista ordenada -->
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ol>

    <hr>

    <h2>Seção de Imagens</h2>

    <p>Imagem 1</p>

    <!-- Tag de Imagem - O caminho da imagem ficará dentro do src="" -->
    <img src="https://www.google.com.br/logos/google.jpg" alt="imagem do google">
    <!-- Alt = Texto Alternativo, um texto que é mostrado quando o site não consegue carregar a imagem,
        também é um texto reproduzido sonoramente por programas usados por deficientes visuais.
        Devemos sempre por um texto nesse campo -->
 
    <br>

    <p>Imagem 2</p>
    <img src="https://www.google.com.br/logos/google.jpg" alt="imagem do google">

    <br>

    <p>Imagem 3</p>
    <img src="https://www.google.com.br/logos/google.jpg" alt="imagem do google">

    <br>

    <p>Imagem 4</p>
    <img src="https://www.google.com.br/logos/google.jpg" alt="imagem do google">

    <br>

    <p>Imagem 5</p>
    <img src="https://www.google.com.br/logos/google.jpg" alt="imagem do google">
</body>
</html>
