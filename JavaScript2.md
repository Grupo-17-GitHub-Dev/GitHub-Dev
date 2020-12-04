
<h1>JavaScript 2 </h1>
<p>Em javascript temos vários tipos de loopings, os mais usados geralmente são o <b>WHILE</b> / <b>FOR</b>.</p>

<h2>WHILE:</h2>
<h3>Estrutura:</h3>
<pre>
    while (condição) {
      rotina
    }
</pre>

<h3>Exemplo:</h3>
<p>O seguinte laço while vai adicionando x = x+1 enquanto x é menor que três.</p>
<pre>
    var x = 0;
      while (x <= 3) {
        console.log(x); // <- mostra o resultado do <b>X</b> no console.
        n++; 
      }
</pre>
<h2>FOR:</h2>
<h3>Estrutura:</h3>
 <p>Variável integrada no for</p>
 <pre>
 for (var i = 0; i < 9; i++) { 
   console.log(i);
   
}
</pre>
 <p>Variável criada antes</p>
 <pre>
 var i = 0;
 for (i; i < 9; i++) { 
   console.log(i);
   
}
</pre>
<h3>Exemplo:</h3>
 <p>o seguinte laço for irá realizar o mesmo processo do while exemplicado acima.
 <pre>
 for (var i = 0; i < 9; i++) {
   console.log(i);
   
}
</pre>
