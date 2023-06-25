<h1>Calculadora IMC</h1>
<hr/>
-----HTML-----
<hr/>
<br/>
<p>Comecei o site com uma estrutura básica feita pelas tags: h1, span, button, section,
img, div, input e label.
Primeiro usei uma <section> para colocar a imagem do site, depois adicionei um h1
para colocar um titulo bem bonito pra minha página, coloquei uma <div> com uma
<label> e um <input> dentro, na <label> coloquei uma legenda, no <input> coloquei
o “type” como “number” e fiz isso mais uma vez.
Criei uma <div> para fazer o cálculo, usei um botão, para o Javascript ser acionado
toda vez que clicado, usei um <span> para exibir o resultado.</p>
<hr/>
-----Javascript-----
<hr/>
<br/>
<p>Fiz o link do Javascript no HTML e comecei a fazer o código. No código Javascript,
comecei criando 3 variáveis “const” com um “document.queryselector” em todos.
Criei mais uma “const” para o cálculo que calcula IMC com base nos valores de
altura e peso fornecidos no HTML. A função começa verificando se os campos de
“altura” (altura.value) e “peso” (peso.value) não estão vazios. Se ambos os campos
estiverem preenchidos, o código continuará com o cálculo. O IMC é calculado
dividindo-se o peso pelo quadrado da altura. O resultado é então arredondado para
duas casas decimais usando o “toFixed(2)”. Em seguida há uma série de instruções
condicionais ”if” e “else if” para determinar a classificação do IMC com base nos
valores calculados.
As classificações são as seguintes:
 IMC abaixo de 18.5: "Abaixo do peso"
 IMC entre 18.5 e 24.9: "Peso ideal"
 IMC entre 25 e 29.9: "Acima do peso"
 IMC entre 30 e 34.9: "Obesidade Grau I"
 IMC entre 35 e 39.9: "Obesidade Grau II"
 IMC igual ou acima de 40: "Obesidade Grau III"
Após determinar a classificação, o resultado é exibido em no <span> no HTML.</p>
<hr/>
-----CSS-----
<hr/>
<br/>
<p>No CSS dei a estilização da página HTML, coloquei a fonte principal como a “Arial,
Helvetica, sans-serif”.
Coloquei os itens centralizados e diminui o tamanho da imagem, para que ficasse
bonito e coerente com a página.</p>