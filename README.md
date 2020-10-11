<link rel="stylesheet" href="imagens/style.css">
<script type="text/x-mathjax-config">
         MathJax.Hub.Config({
           tex2jax: {
             inlineMath: [ ['$','$'], ["\\(","\\)"] ],
             processEscapes: true
           }
         });
</script>
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

<h2 id="inicio">Construções Geométricas</h2>

<p>Este site contém os procedimentos para construções geométricas usadas na disciplina de Desenho Geométrico</p>
<p>A apostila está disponível no link: <a href="http://www.exatas.ufpr.br/portal/degraf_paulo/wp-content/uploads/sites/4/2014/09/apos_dg.pdf" target="_blank">apostila de Desenho Geométrico</a></p>

<details>
  <summary id="parte1">1.1. Circunferência e Mediatriz</summary>
  <p>Material da página 1 até a página 11.</p>
   <img src="parte1/apos_dg_0001.png"/>
   <p class="topop"><a href="#parte1" class="topo">voltar ao topo</a></p>
   <img src="parte1/apos_dg_0002.png"/>
   <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Construção</summary>
	<p>Utilizaremos o compasso para construir a primeira circunferência. Lembre-se sempre de deixá-lo com o grafite apontado para desenhar com maior precisão.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="001" name="sl" checked>
			   <label for="001"></label>
			   <img src="parte1/02_01_01.png"/>
			   <figcaption>Considerado um ponto <b>O</b> e a medida <b>r</b>, vamos construir a circunferência de centro em <b>O</b> e raio <b>r</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="002" name="sl">
			   <label for="002"></label>
			   <img src="parte1/02_01_02.png"/>
			   <figcaption>Usando o compasso, colocamos a ponta seca em uma extremidade e o grafite na outra extremidade de <b>r</b>. Desta forma, "pegamos" a medida <b>r</b> e...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="003" name="sl">
			   <label for="003"></label>
			   <img src="parte1/02_01_03.png"/>
			   <figcaption>... com a ponta seca em <b>O</b>, construímos a circunferência com raio <b>r</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="004" name="sl">
			   <label for="004"></label>
			   <img src="parte1/02_01_04.png"/>
			   <figcaption>Qualquer ponto <b>P</b> pertencente à <b>Circunf(O,r)</b> tem a distância fixa <b>r</b> até o ponto fixo <b>O</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte1/02_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte1/apos_dg_0002a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos o conceito de lugar geométrico para fazer esta construção. Usaremos o compasso como instrumento auxiliar.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="005" name="sl" checked>
			   <label for="005"></label>
			   <img src="parte1/02_02_01.png"/>
			   <figcaption>Como a distância de <b>P</b> até <b>X</b> é igual a <b>d</b>, vamos construir a circunferência de centro em <b>P</b> e raio <b>d</b>. Logo, podemos usar o compasso com a ponta seca em uma extremidade de <b>d</b> e o grafite na outra extremidade para "pegarmos" a medida <b>d</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="006" name="sl">
			   <label for="006"></label>
			   <img src="parte1/02_02_02.png"/>
			   <figcaption>Com a ponta seca em <b>P</b>, construímos a <b>Circunf(P,d)</b>, que é o lugar geométrico de todos os pontos com distância <b>d</b> até o ponto <b>P</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="007" name="sl">
			   <label for="007"></label>
			   <img src="parte1/02_02_03.png"/>
			   <figcaption>Como o ponto <b>X</b> está na reta <b>t</b>, teremos duas soluções para este problema, encontradas na interseção da <b>Circunf(P,d)</b> com a reta <b>t</b>. Se a <b>Circunf(P,d)</b> não interceptar a reta <b>t</b>, não temos solução. No caso em que a <b>Circunf(P,d)</b> for tangente à reta <b>t</b>, teremos apenas 1 solução.</figcaption>
		   </li>
		</ul>
		<img src="parte1/02_02_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte1" class="topo">voltar ao topo</a></p>
  <img src="parte1/apos_dg_0003.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos o conceito de lugar geométrico para resolver este problema. Usaremos o compasso como instrumento auxiliar.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="008" name="sl" checked>
			   <label for="008"></label>
			   <img src="parte1/03_01_01.png"/>
			   <figcaption>Como a distância de <b>X</b> até <b>A</b> é igual a <b>m</b>, vamos construir a circunferência de centro em <b>A</b> e raio <b>m</b>. Logo, podemos usar o compasso com a ponta seca em uma extremidade de <b>m</b> e o grafite na outra extremidade para "pegarmos" a medida <b>m</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="009" name="sl">
			   <label for="009"></label>
			   <img src="parte1/03_01_02.png"/>
			   <figcaption>Com a ponta seca em <b>A</b>, construímos a <b>Circunf(A,m)</b>, que é o lugar geométrico de todos os pontos com distância <b>m</b> até o ponto <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="010" name="sl">
			   <label for="010"></label>
			   <img src="parte1/03_01_03.png"/>
			   <figcaption>Usando o mesmo raciocínio, "pegamos" a distância <b>n</b> com o compasso...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="011" name="sl">
			   <label for="011"></label>
			   <img src="parte1/03_01_04.png"/>
			   <figcaption>... e construímos a <b>Circunf(B,n)</b>, que é o lugar geométrico dos pontos com distância <b>n</b> até o ponto <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="012" name="sl">
			   <label for="012"></label>
			   <img src="parte1/03_01_05.png"/>
			   <figcaption>Temos duas soluções, encontradas nas interseções das circunferências construídas. Se as circunferências ficarem tangentes, teremos apenas 1 solução. E no caso em que as circunferências não se cortam, não teremos solução neste problema.</figcaption>
		   </li>
		</ul>
		<img src="parte1/03_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte1/apos_dg_0003a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos o conceito de lugar geométrico para fazer a construção deste triângulo. Usaremos a régua e o compasso como instrumentos auxiliares.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="013" name="sl" checked>
			   <label for="013"></label>
			   <img src="parte1/03_02_01.png"/>
			   <figcaption>Vamos imaginar o triângulo <b>ABC</b> construído.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="014" name="sl">
			   <label for="014"></label>
			   <img src="parte1/03_02_02.png"/>
			   <figcaption>Por convenção, vamos nomear os lados opostos aos vértices com as mesmas letras, porém, minúsculas. Por exemplo, o lado <b>BC</b>, oposto ao vértice <b>A</b>, terá o nome <b>a</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="015" name="sl">
			   <label for="015"></label>
			   <img src="parte1/03_02_03.png"/>
			   <figcaption>Vamos começar construindo uma reta qualquer <b>r</b>, e escolhendo um ponto <b>B</b> sobre esta reta.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="016" name="sl">
			   <label for="016"></label>
			   <img src="parte1/03_02_04.png"/>
			   <figcaption>Usando o compasso, vamos "pegar" a medida de um dos lados com extreminade <b>B</b>: neste caso, o lado <b>c</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="017" name="sl">
			   <label for="017"></label>
			   <img src="parte1/03_02_05.png"/>
			   <figcaption>Com centro em <b>B</b>, desenhamos um pequeno arco que serve apenas para transferir a medida <b>c</b> para a reta <b>r</b>. Logo, encontramos o vértice <b>A</b> do triângulo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="018" name="sl">
			   <label for="018"></label>
			   <img src="parte1/03_02_06.png"/>
			   <figcaption>Agora podemos "pegar" as outra medidas dos lados com o compasso. Primeiro, vamos "pegar" o lado <b>a</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="019" name="sl">
			   <label for="019"></label>
			   <img src="parte1/03_02_07.png"/>
			   <figcaption>... e construir a <b>Circunf(B,a)</b>, pois a medida <b>a</b> está no lado oposto do vértice <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="020" name="sl">
			   <label for="020"></label>
			   <img src="parte1/03_02_08.png"/>
			   <figcaption>Por último, "pegamos" com o compasso a medida do lado que falta: <b>b</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="021" name="sl">
			   <label for="021"></label>
			   <img src="parte1/03_02_09.png"/>
			   <figcaption>Assim, podemos construir a <b>Circunf(A,b)</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="022" name="sl">
			   <label for="022"></label>
			   <img src="parte1/03_02_10.png"/>
			   <figcaption>Nas interseções das circunferências construídas, podemos escolher o vértice <b>C</b> e "passar a limpo" o triângulo <b>ABC</b> unindo as extremidades <b>A</b> com <b>C</b> e <b>B</b> com <b>C</b>. O triângulo <b>ABC'</b> pode ser desenhado com linha tracejada.</figcaption>
		   </li>
		</ul>
		<img src="parte1/03_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte1/apos_dg_0003b.png"/>
  <p class="topop"><a href="#parte1" class="topo">voltar ao topo</a></p>
  <img src="parte1/apos_dg_0004.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos o conceito de lugar geométrico para fazer esta construção. O compasso será usado como instrumento auxiliar.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="023" name="sl" checked>
			   <label for="023"></label>
			   <img src="parte1/04_01_01.png"/>
			   <figcaption>Como a circunferência procurada passar pelos pontos <b>A</b> e <b>B</b>, as distâncias entre o centro <b>O</b> e os pontos <b>A</b> e <b>B</b> medem o raio <b>r</b>. Logo, podemos "pegar" a medida <b>r</b> com o compasso...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="024" name="sl">
			   <label for="024"></label>
			   <img src="parte1/04_01_02.png"/>
			   <figcaption>... e construir a <b>Circunf(A,r)</b>, que é o primeiro lugar geométrico do centro <b>O</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="026" name="sl">
			   <label for="026"></label>
			   <img src="parte1/04_01_04.png"/>
			   <figcaption>Com o mesmo raio, construímos a <b>Circunf(B,r)</b>, que é o segundo lugar geométrico de <b>O</b>. Teremos duas soluções: <b>O</b> e <b>O'</b>. Se as circunferências ficarem tangentes, temos apenas 1 solução; e no caso em que as circunferências não se interceptam, não temos solução.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="027" name="sl">
			   <label for="027"></label>
			   <img src="parte1/04_01_05.png"/>
			   <figcaption>Com a ponta seca em <b>O</b>, construímos a <b>Circunf(O,r)</b>, que passa por <b>A</b> e <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="028" name="sl">
			   <label for="028"></label>
			   <img src="parte1/04_01_06.png"/>
			   <figcaption>E com a ponta seca em <b>O'</b>, desenhamos a <b>Circunf(O',r)</b>, que passa por <b>A</b> e <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="029" name="sl">
			   <label for="029"></label>
			   <img src="parte1/04_01_07.png"/>
			   <figcaption>Escolhemos uma solução para ficar com linha contínua e a outra com linha tracejada.</figcaption>
		   </li>
		</ul>
		<img src="parte1/04_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte1/apos_dg_0004a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Usando o conceito do lugar geométrico circunferência, você consegue resolver este exercício proposto.</p>
	<img src="parte1/04_02_00.png"/>
	<figcaption>Encontramos duas soluções na resolução deste problema.</figcaption>
  </details></div>
  <img src="parte1/apos_dg_0004b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Use o conceito do lugar geométrico circunferência para resolver este exercício.</p>
	<img src="parte1/04_03_00.png"/>
	<figcaption>Encontramos duas soluções na resolução deste problema: os triângulos <b>ABC</b> e <b>A'BC</b>.</figcaption>
  </details></div>
  <p class="topop"><a href="#parte1" class="topo">voltar ao topo</a></p>
  <img src="parte1/apos_dg_0005.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Usando o conceito do lugar geométrico circunferência, você consegue resolver este exercício.</p>
	<img src="parte1/05_01_00.png"/>
	<figcaption>Como as laterais do triângulo isósceles medem <b>d</b>, usamos uma circunferência para encontrar os vértices <b>B</b> e <b>C</b>.</figcaption>
  </details></div>
  <img src="parte1/apos_dg_0005a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Use o conceito do lugar geométrico circunferência para resolver este exercício.</p>
	<img src="parte1/05_02_00.png"/>
	<figcaption>Lembrando que o lado <b>b</b> é o lado <b>AC</b> do triângulo, usamos a circunferência com centro em <b>C</b> e raio <b>b</b>.</figcaption>
  </details></div>
  <img src="parte1/apos_dg_0005b.png"/>
  <div class="combo">&#x1f4cf; &#x1f4d0; <span class="atv">Atividade 1</span></div>
  <p class="topop"><a href="#parte1" class="topo">voltar ao topo</a></p>
  <img src="parte1/apos_dg_0006.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos o conceito de lugar geométrico para fazer esta construção. Usaremos a régua e o compasso como instrumentos auxiliares.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="030" name="sl" checked>
			   <label for="030"></label>
			   <img src="parte1/06_01_01.png"/>
			   <figcaption>Lembrando da propriedade: se duas circunferências são tangentes em um ponto <b>T</b>, elas admitem a reta tangente <b>t</b> comum; como a reta tangente forma <b>90&deg;</b> com o raio em <b>T</b>, os raios <b>OT</b> e <b>AT</b> formam <b>180&deg;</b>, ou seja, <b>O</b>, <b>T</b> e <b>A</b> serão colineares.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="031" name="sl">
			   <label for="031"></label>
			   <img src="parte1/06_01_02.png"/>
			   <figcaption>Usando a régua ou um dos esquadros, podemos prolongar o segmento <b>OT</b> e usar o compasso para "pegar" a medida <b>r</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="032" name="sl">
			   <label for="032"></label>
			   <img src="parte1/06_01_03.png"/>
			   <figcaption>Com o centro em <b>T</b>, construímos um arco para marcar o centro <b>A</b> na reta <b>OT</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="033" name="sl">
			   <label for="033"></label>
			   <img src="parte1/06_01_04.png"/>
			   <figcaption>Teremos uma solução interna à circunferência <b>&lambda;</b>; logo, podemos marcar também o ponto <b>A'</b> sobre o raio <b>OT</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="034" name="sl">
			   <label for="034"></label>
			   <img src="parte1/06_01_05.png"/>
			   <figcaption>Com centro em <b>A</b>, construímos a <b>Circunf(A,r)</b>, que é a primeira solução.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="035" name="sl">
			   <label for="035"></label>
			   <img src="parte1/06_01_06.png"/>
			   <figcaption>E com centro em <b>A'</b>, construímos a <b>Circunf(A',r)</b>, que é a segunda solução.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="036" name="sl">
			   <label for="036"></label>
			   <img src="parte1/06_01_07.png"/>
			   <figcaption>Estas são as duas soluções do problema proposto.</figcaption>
		   </li>
		</ul>
		<img src="parte1/06_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte1/apos_dg_0006a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4dd; Propriedades</summary>
	<p>Neste segundo lugar geométrico, usamos a régua e o compasso como instrumentos auxiliares para sua construção.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="037" name="sl" checked>
			   <label for="037"></label>
			   <img src="parte1/06_02_01.png"/>
			   <figcaption>Para encontrar a mediatriz de <b>AB</b>, construímos os arcos de circunferências de centros <b>A</b> e <b>B</b>, com a mesma medida dos raios. Esta medida precisa ser maior do que a metade de <b>AB</b>. As interseções destes arcos definem a reta <b>XX'</b> que é a mediatriz de <b>AB</b>. Usamos a notação <b>med<sub>AB</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="038" name="sl">
			   <label for="038"></label>
			   <img src="parte1/06_02_02.png"/>
			   <figcaption>Como os raios são iguais à uma medida <b>d</b>, temos a formação do <b>&#9651;AXB</b> isósceles de base <b>d</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="039" name="sl">
			   <label for="039"></label>
			   <img src="parte1/06_02_03.png"/>
			   <figcaption>Obtemos assim o ponto médio <b>M</b> de <b>AB</b>, e os <b>&#9651;AMX</b> e <b>&#9651;BMX</b> congruentes.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="040" name="sl">
			   <label for="040"></label>
			   <img src="parte1/06_02_04.png"/>
			   <figcaption>Logo, temos que <b>&angsph;AMX = 90&deg;</b>. Portanto, a mediatriz passa pelo ponto médio e forma <b>90&deg;</b> com este segmento.</figcaption>
		   </li>
		</ul>
		<img src="parte1/06_02_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte1" class="topo">voltar ao topo</a></p>
  <img src="parte1/apos_dg_0007.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos a régua e o compasso como instrumentos auxiliares para sua construção da mediatriz.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="041" name="sl" checked>
			   <label for="041"></label>
			   <img src="parte1/07_01_01.png"/>
			   <figcaption>Vamos construir um arco de circunferência com centro em <b>A</b> e a medida do raio maior do que a metade de <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="042" name="sl">
			   <label for="042"></label>
			   <img src="parte1/07_01_02.png"/>
			   <figcaption>Com a mesma medida do raio do arco anterior, construímos o arco com centro em <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="043" name="sl">
			   <label for="043"></label>
			   <img src="parte1/07_01_03.png"/>
			   <figcaption>Usando a régua ou um dos esquadros, construímos a reta que passa pelos pontos de interseção dos arcos construídos <b>P</b> e <b>P'</b>. Esta é a mediatriz de AB, denotada por <b>med<sub>AB</sub></b></figcaption>
		   </li>
		   <li>
			   <input type="radio" id="044" name="sl">
			   <label for="044"></label>
			   <img src="parte1/07_01_04.png"/>
			   <figcaption>Quando o segmento <b>AB</b> estiver próximo da margem da folha, podemos construir um dos arcos, com centro em <b>A</b> e raio maior do que a metade de <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="045" name="sl">
			   <label for="045"></label>
			   <img src="parte1/07_01_05.png"/>
			   <figcaption>Com a mesma medida do raio usado em <b>A</b>, construímos o arco com centro em <b>B</b>. O ponto de interseção <b>Q</b> pertence à mediatriz procurada. Porém, precisamos de mais um ponto para determinar a mediatriz.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="046" name="sl">
			   <label for="046"></label>
			   <img src="parte1/07_01_06.png"/>
			   <figcaption>Logo, podemos construir dois outros arcos, usando uma outra medida.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="047" name="sl">
			   <label for="047"></label>
			   <img src="parte1/07_01_07.png"/>
			   <figcaption>Usando a mesma medida, construímos o arco com centro em <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="048" name="sl">
			   <label for="048"></label>
			   <img src="parte1/07_01_08.png"/>
			   <figcaption>A mediatriz pode ser construída com a régua ou um esquadro, unindo os pontos de interseção do arcos <b>Q</b> e <b>Q'</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="049" name="sl">
			   <label for="049"></label>
			   <img src="parte1/07_01_09.png"/>
			   <figcaption>A mediatriz de <b>AB</b> está construída com o segmento próximo da margem da folha.</figcaption>
		   </li>
		</ul>
		<img src="parte1/07_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte1/apos_dg_0007a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Constuindo a mediatriz de <b>AB</b>, determinamos o ponto médio deste segmento.</p>
	<img src="parte1/07_02_00.png"/>
	<figcaption>Utilize os mesmos passos usados na construção anterior.</figcaption>
  </details></div>
  <img src="parte1/apos_dg_0007b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Usaremos a régua e o compasso como instrumentos auxiliares nesta construção.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="051" name="sl" checked>
			   <label for="051"></label>
			   <img src="parte1/07_03_01.png"/>
			   <figcaption>Como o triângulo é isósceles de base <b>BC</b>, o vértice <b>A</b> é equidistante dos vértices <b>B</b> e <b>C</b>: logo, <b>A</b> pertence à mediatriz de <b>BC</b>. Com uma medida maior do que a metade de <b>BC</b>, construímos um arco com centro em <b>C</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="052" name="sl">
			   <label for="052"></label>
			   <img src="parte1/07_03_02.png"/>
			   <figcaption>... e outro com mesmo raio e centro em <b>B</b>. As interseções definem os pontos <b>P</b> e <b>P'</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="053" name="sl">
			   <label for="053"></label>
			   <img src="parte1/07_03_03.png"/>
			   <figcaption>Usando a régua ou um dos esquadros, construa a mediatriz de <b>BC</b> unindo os pontos <b>P</b> e <b>P'</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="054" name="sl">
			   <label for="054"></label>
			   <img src="parte1/07_03_04.png"/>
			   <figcaption>Como o vértice <b>A</b> pertence à circunferência <b>&lambda;</b>, as interseções de <b>&lambda;</b> com a <b>med<sub>BC</sub></b> definem os vértices do triângulo isósceles. Teremos 2 soluções para este problema, pois a mediatriz intercepta a circunferência em 2 pontos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="055" name="sl">
			   <label for="055"></label>
			   <img src="parte1/07_03_05.png"/>
			   <figcaption>Escolha uma solução para construir o triângulo com linha contínua e o outro com linha tracejada.</figcaption>
		   </li>
		</ul>
		<img src="parte1/07_03_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte1" class="topo">voltar ao topo</a></p>
  <img src="parte1/apos_dg_0008.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos usar a régua e o compasso como instrumentos auxiliares para resolver este problema.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="056" name="sl" checked>
			   <label for="056"></label>
			   <img src="parte1/08_01_01.png"/>
			   <figcaption>Temos os três pontos pertencentes à circunferência de centro <b>O</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="057" name="sl">
			   <label for="057"></label>
			   <img src="parte1/08_01_02.png"/>
			   <figcaption>As distâncias entre os pontos dados e o centro é a mesma: o raio <b>r</b> da circunferência. Logo, podemos construir duas mediatrizes para encontrar o centro.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="058" name="sl">
			   <label for="058"></label>
			   <img src="parte1/08_01_03.png"/>
			   <figcaption>Com o centro em <b>A</b>, construiremos um arco com medida maior do que <b>AC</b> para encontrar a <b>med<sub>AC</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="059" name="sl">
			   <label for="059"></label>
			   <img src="parte1/08_01_04.png"/>
			   <figcaption>Com o centro em <b>C</b>, construimos um arco com mesmo raio do primeiro, encontrando as interseções <b>P</b> e <b>P'</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="060" name="sl">
			   <label for="060"></label>
			   <img src="parte1/08_01_05.png"/>
			   <figcaption>Usando a régua ou um dos esquadros, construímos a mediatriz de <b>AC</b>, que é o primeiro lugar geométrico do centro <b>O</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="061" name="sl">
			   <label for="061"></label>
			   <img src="parte1/08_01_06.png"/>
			   <figcaption>Usando a construção similar, construímos a <b>med<sub>AB</sub></b>, que é o segundo lugar geométrico de <b>O</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="062" name="sl">
			   <label for="062"></label>
			   <img src="parte1/08_01_07.png"/>
			   <figcaption>Na interseção das duas mediatrizes, temos o centro da circunferência que passa pelos 3 pontos. Não precisamos construir a mediatriz do terceiro segmento, <b>BC</b>, pois basta a interseção de duas retas para determinar o ponto <b>O</b>. Com centro em <b>O</b>, podemos abrir o compasso até qualquer um dos três pontos...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="063" name="sl">
			   <label for="063"></label>
			   <img src="parte1/08_01_08.png"/>
			   <figcaption>... e construir a circunferência que passa pelos 3 pontos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="064" name="sl">
			   <label for="064"></label>
			   <img src="parte1/08_01_09.png"/>
			   <figcaption>Esta é a única solução deste problema.</figcaption>
		   </li>
		</ul>
		<img src="parte1/08_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte1/apos_dg_0008a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos usar a régua, o compasso e os esquadros como instrumentos auxiliares para resolver este problema. Vamos começar usando a régua e o compasso.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="065" name="sl" checked>
			   <label for="065"></label>
			   <img src="parte1/08_02_01.png"/>
			   <figcaption>Vamos usar o fato do que a mediatriz de um segmento é perpendicular ao segmento. Construa então um arco de circunferência de centro <b>P</b> e raio de medida qualquer, determinando o ponto <b>A</b> sobre a reta <b>r</b>, no lado direito.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="066" name="sl">
			   <label for="066"></label>
			   <img src="parte1/08_02_02.png"/>
			   <figcaption>Com a mesma medida do raio do arco usado para encontrar <b>A</b>, encontre do lado esquerdo do ponto <b>P</b> o ponto <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="067" name="sl">
			   <label for="067"></label>
			   <img src="parte1/08_02_03.png"/>
			   <figcaption>É como se <b>P</b> fosse o ponto médio de <b>AB</b>. Então vamos encontrar a <b>med<sub>AB</sub></b>: com centro em <b>A</b>, construa um arco com raio de medida maior do que <b>AP</b> e...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="068" name="sl">
			   <label for="068"></label>
			   <img src="parte1/08_02_04.png"/>
			   <figcaption>... com centro em <b>B</b>, construa um arco com mesmo raio. A interseção destes arcos é o ponto <b>C</b>, que pertence à <b>med<sub>AB</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="069" name="sl">
			   <label for="069"></label>
			   <img src="parte1/08_02_05.png"/>
			   <figcaption>Logo, podemos construir com a régua ou um dos esquadros a reta <b>PC</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="070" name="sl">
			   <label for="070"></label>
			   <img src="parte1/08_02_06.png"/>
			   <figcaption>Esta reta é perpendicular à reta <b>r</b>, pois é a <b>med<sub>AB</sub></b>. Agora determine um ponto <b>P'</b> sobre a reta <b>r</b> para construirmos a perpendicular a esta reta que passa por <b>P'</b> com os esquadros.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="071" name="sl">
			   <label for="071"></label>
			   <img src="parte1/08_02_07.png"/>
			   <figcaption>Neste exemplo, vamos usar o esquadro de 45 alinhando um cateto com a reta. Coloque na hipotenusa deste esquadro o outro esquadro ou a régua como apoio.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="072" name="sl">
			   <label for="072"></label>
			   <img src="parte1/08_02_08.png"/>
			   <figcaption>Deixando fixo o esquadro de 60, deslize o esquadro de 45 até chegar em <b>P'</b>. Use o outro cateto do esquadro de 45 para construir a reta perpendicular.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="073" name="sl">
			   <label for="073"></label>
			   <img src="parte1/08_02_09.png"/>
			   <figcaption>Esta é a solução do problema com o uso de esquadros. Você pode usar o esquadro de 60 alinhado e o outro fixo. O importante é lembrar de apoiar sempre a hipotenusa deste esquadro que irá deslizar com o outro esquadro.</figcaption>
		   </li>
		</ul>
		<img src="parte1/08_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte1/apos_dg_0008b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos usar a régua, o compasso e os esquadros como instrumentos auxiliares para resolver este problema. Vamos começar usando a régua e o compasso.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="074" name="sl" checked>
			   <label for="074"></label>
			   <img src="parte1/08_03_01.png"/>
			   <figcaption>Neste item, vamos novamente usar o fato do que a mediatriz de um segmento é perpendicular ao segmento. Construa então um arco de circunferência com raio de medida qualquer, que intercepte a reta <b>r</b> nos pontos <b>A</b> e <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="075" name="sl">
			   <label for="075"></label>
			   <img src="parte1/08_03_02.png"/>
			   <figcaption>É como se <b>P</b> fosse um ponto qualquer da <b>med<sub>AB</sub></b>. Então vamos encontrar a <b>med<sub>AB</sub></b>: com centro em <b>B</b>, construa um arco com raio de medida maior do que a metade de <b>AB</b> e...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="076" name="sl">
			   <label for="076"></label>
			   <img src="parte1/08_03_03.png"/>
			   <figcaption>... com centro em <b>A</b>, construa um arco com mesmo raio. A interseção destes arcos é o ponto <b>C</b>, que pertence à <b>med<sub>AB</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="077" name="sl">
			   <label for="077"></label>
			   <img src="parte1/08_03_04.png"/>
			   <figcaption>Logo, podemos construir com a régua ou um dos esquadros a reta <b>PC</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="078" name="sl">
			   <label for="078"></label>
			   <img src="parte1/08_03_05.png"/>
			   <figcaption>Esta reta é perpendicular à reta <b>r</b>, pois é a <b>med<sub>AB</sub></b>. Agora determine um ponto <b>P'</b> não pertencente à reta <b>r</b> para construirmos a perpendicular a esta reta que passa por <b>P'</b> com os esquadros.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="079" name="sl">
			   <label for="079"></label>
			   <img src="parte1/08_03_06.png"/>
			   <figcaption>Neste exemplo, vamos usar o esquadro de 60 alinhando o cateto maior com a reta. Coloque na hipotenusa deste esquadro o outro esquadro ou a régua como apoio.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="080" name="sl">
			   <label for="080"></label>
			   <img src="parte1/08_03_07.png"/>
			   <figcaption>Deixando fixo o esquadro de 45, deslize o esquadro de 60 até chegar em <b>P'</b>. Use o outro cateto do esquadro de 60 para construir a reta perpendicular.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="081" name="sl">
			   <label for="081"></label>
			   <img src="parte1/08_03_08.png"/>
			   <figcaption>Esta é a solução do problema com o uso de esquadros. Você pode usar o esquadro de 45 alinhado e o outro fixo. O importante é lembrar de apoiar sempre a hipotenusa deste esquadro que irá deslizar com o outro esquadro.</figcaption>
		   </li>
		</ul>
		<img src="parte1/08_03_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte1" class="topo">voltar ao topo</a></p>
  <img src="parte1/apos_dg_0009.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Constuindo a mediatriz de <b>AB</b>, determinamos o ponto médio <b>M</b>deste segmento.</p>
	<img src="parte1/09_01_00.png"/>
	<figcaption>Usando as mediatrizes das metades do segmento <b>AB</b>, dividimos este segmento em 4 partes iguais.</figcaption>
  </details></div>
  <img src="parte1/apos_dg_0009a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Como <b>P</b> é esquidistante de <b>B</b> e de <b>C</b>, pertence à <b>med<sub>BC</sub></b>.</p>
	<img src="parte1/09_02_00.png"/>
	<figcaption></figcaption>
  </details></div>
  <img src="parte1/apos_dg_0009b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Como <b>X</b> é esquidistante de <b>A</b> e de <b>C</b>, pertence à <b>med<sub>AC</sub></b>.</p>
	<img src="parte1/09_03_00.png"/>
	<figcaption>Como a distância de <b>X</b> até <b>B</b> é igual a <b>r</b>, pertence à <b>Circunf(B,r)</b>.</figcaption>
  </details></div>
  <p class="topop"><a href="#parte1" class="topo">voltar ao topo</a></p>
  <img src="parte1/apos_dg_0010.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Como <b>X</b> é esquidistante de <b>A</b> e de <b>B</b>, pertence à <b>med<sub>AB</sub></b>.</p>
	<img src="parte1/10_01_00.png"/>
	<figcaption>Como <b>X</b> é esquidistante de <b>C</b> e de <b>D</b>, pertence à <b>med<sub>CD</sub></b>.</figcaption>
  </details></div>
  <img src="parte1/apos_dg_0010a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Neste caso, o centro será o ponto médio do diâmetro <b>AB</b>.</p>
	<img src="parte1/10_02_00.png"/>
	<figcaption></figcaption>
  </details></div>
  <img src="parte1/apos_dg_0010b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Como a circunferência procurada passa por <b>P</b> e <b>Q</b>, seu centro pertence à <b>med<sub>PQ</sub></b>.</p>
	<img src="parte1/10_03_00.png"/>
	<figcaption>Depois de achar o centro <b>O</b>, o raio será <b>OP = OQ</b>.</figcaption>
  </details></div>
  <p class="topop"><a href="#parte1" class="topo">voltar ao topo</a></p>
  <img src="parte1/apos_dg_0011.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos usar a régua e o compasso como instrumentos auxiliares para resolver este problema.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="082" name="sl" checked>
			   <label for="082"></label>
			   <img src="parte1/11_01_01.png"/>
			   <figcaption>Podemos definir dois pontos sobre a circunferência. Se construirmos a mediatriz deste segmento, o centro estará contido nesta reta. Logo, defina o arco com centro em <b>A</b> e um raio com medida maior do que a metade de <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="083" name="sl">
			   <label for="083"></label>
			   <img src="parte1/11_01_02.png"/>
			   <figcaption>Com centro em <b>B</b>, construa o arco com mesma medida do raio usado em <b>A</b>. As interseções definem a  <b>med<sub>AB</sub></b>, que contém o centro da circunferência.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="084" name="sl">
			   <label for="084"></label>
			   <img src="parte1/11_01_03.png"/>
			   <figcaption>Podemos escolher outro ponto da circunferência: <b>C</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="085" name="sl">
			   <label for="085"></label>
			   <img src="parte1/11_01_04.png"/>
			   <figcaption>Construindo a mediatriz de <b>med<sub>BC</sub></b>, temos que a interseção da <b>med<sub>AB</sub></b> com a <b>med<sub>BC</sub></b> será o ponto equidistante de <b>A</b>, <b>B</b> e <b>C</b>. Logo, este ponto é o centro da circunferência.</figcaption>
		   </li>
		</ul>
		<img src="parte1/11_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte1/apos_dg_0011a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos usar os esquadros e o compasso como instrumentos auxiliares para resolver este problema. Como a reta <b>t</b> é tangente à circunferência de centro <b>O</b>, o raio <b>OT</b> será perpendicular a <b>t</b>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="086" name="sl" checked>
			   <label for="086"></label>
			   <img src="parte1/11_02_01.png"/>
			   <figcaption>Podemos construir a reta perpendicular a <b>t</b> que passa por <b>O</b> com régua e compasso ou com os esquadros. Neste exemplo, vamos usar os esquadros: alinhe um cateto do esquadro de 45 com a reta <b>t</b>, e a hipotenusa deste esquadro fica apoiada com a régua ou com outro esquadro.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="087" name="sl">
			   <label for="087"></label>
			   <img src="parte1/11_02_02.png"/>
			   <figcaption>Deixando fixo o esquadro de 60, deslize o esquadro de 45 até chegar em <b>O</b>. Construa a reta perpendicular usando o cateto do esquadro de 45.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="088" name="sl">
			   <label for="088"></label>
			   <img src="parte1/11_02_03.png"/>
			   <figcaption>O raio da circunferência procurada será <b>OT</b>. Com centro em <b>O</b> e raio <b>OT</b>, construímos a solução deste problema.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="089" name="sl">
			   <label for="089"></label>
			   <img src="parte1/11_02_04.png"/>
			   <figcaption>Se você preferir, pode fazer a construção da reta perpendicular a <b>t</b> que passa por <b>O</b> usando régua e compasso.</figcaption>
		   </li>
		</ul>
		<img src="parte1/11_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte1/apos_dg_0011b.png"/>
  <div class="combo">&#x1f4cf; &#x1f4d0; <span class="atv">Atividade 2</span></div>
  <p class="topop"><a href="#parte1" class="topo">voltar ao topo</a></p>
</details>

<details>
  <summary id="parte2">1.2. Retas paralelas e bissetriz</summary>
  <p>Material da página 12 até a página 20.</p>
  <img src="parte2/apos_dg_0012.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Construção</summary>
	<p>Agora vamos estudar o terceiro lugar geométrico: retas paralelas. Vamos ver algumas propriedades.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="090" name="sl" checked>
			   <label for="090"></label>
			   <img src="parte2/12_01_01.png"/>
			   <figcaption>Fixando a reta <b>r</b>, as retas paralelas <b>s<sub>1</sub></b> e <b>s<sub>2</sub></b> formam o conjunto de pontos com distância <b>d</b> até a reta <b>r</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="091" name="sl">
			   <label for="091"></label>
			   <img src="parte2/12_01_02.png"/>
			   <figcaption>Para medir a distância de um ponto <b>P</b> qualquer, pertencente a <b>s<sub>1</sub></b>, até a reta <b>r</b> basta construir a reta perpendicular a <b>r</b> que passa por <b>P</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte2/12_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte2/apos_dg_0012a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos a régua e o compasso para resolver os dois primeiros casos nesta construção.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="092" name="sl" checked>
			   <label for="092"></label>
			   <img src="parte2/12_02_01.png"/>
			   <figcaption>Vamos usar a ideia de mediatriz para a primeira construção. Primeiro, vamos construir a reta perpendicular a <b>t</b> que passa por <b>P</b>. Com centro em <b>P</b>, construa o arco que intercepta <b>t</b> nos pontos <b>A</b> e <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="093" name="sl">
			   <label for="093"></label>
			   <img src="parte2/12_02_02.png"/>
			   <figcaption>Com centro em <b>B</b>, construa um arco com medida do raio maior do que a metade de <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="094" name="sl">
			   <label for="094"></label>
			   <img src="parte2/12_02_03.png"/>
			   <figcaption>Com centro em <b>A</b>, construa o arco com mesmo raio usado em <b>B</b>. A interseção é o ponto <b>C</b> que define a reta <b>PC &perp; r</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="095" name="sl">
			   <label for="095"></label>
			   <img src="parte2/12_02_04.png"/>
			   <figcaption>Agora vamos construir a reta perpendicular à reta <b>PC</b> que passa por <b>P</b>. Com centro em <b>P</b>, defina um arco qualquer que intercepte <b>PC</b> em <b>D</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="096" name="sl">
			   <label for="096"></label>
			   <img src="parte2/12_02_05.png"/>
			   <figcaption>Encontre o ponto <b>E</b>, tal que <b>PE = PD</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="097" name="sl">
			   <label for="097"></label>
			   <img src="parte2/12_02_06.png"/>
			   <figcaption>Agora vamos construir a mediatriz de <b>ED</b>. Com centro em <b>D</b>, construa um arco com raio maior do que <b>PD</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="098" name="sl">
			   <label for="098"></label>
			   <img src="parte2/12_02_07.png"/>
			   <figcaption>... e use o mesmo raio para construir o arco com centro em <b>E</b>. Desta forma, encontramos o ponto <b>F</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="099" name="sl">
			   <label for="099"></label>
			   <img src="parte2/12_02_08.png"/>
			   <figcaption>A reta <b>PF &perp; PD</b> é paralela à reta <b>t</b>, pois os ângulos alternos internos são iguais a <b>90&deg;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="100" name="sl">
			   <label for="100"></label>
			   <img src="parte2/12_02_09.png"/>
			   <figcaption>Agora vamos construi a reta paralela a <b>t</b> que passa por <b>P</b> usando outro raciocínio. Construa um arco de circunferência de raio qualquer <b>PQ</b>, onde <b>Q &isin; t</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="101" name="sl">
			   <label for="101"></label>
			   <img src="parte2/12_02_10.png"/>
			   <figcaption>Com a mesma medida do raio, encontre o ponto <b>R &isin; t</b>, ou seja, <b>QR = PQ</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="102" name="sl">
			   <label for="102"></label>
			   <img src="parte2/12_02_11.png"/>
			   <figcaption>Com centro em <b>R</b>, determine o arco com mesmo raio que usamos para achar <b>Q</b> e <b>R</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="103" name="sl">
			   <label for="103"></label>
			   <img src="parte2/12_02_12.png"/>
			   <figcaption>Na interseção do terceiro arco que construímos com o arco de centro <b>P</b>, encontramos o ponto <b>S</b>, tal que <b>PS // t</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="104" name="sl">
			   <label for="104"></label>
			   <img src="parte2/12_02_13.png"/>
			   <figcaption>De fato, <b>PS // t</b> pois construímos um losango <b>PQRS</b>, e os lados opostos de um losango são paralelos.</figcaption>
		   </li>
		</ul>
		<img src="parte2/12_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte2/apos_dg_0012b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos a régua e o compasso para resolver o terceiro caso desta construção, e o par de esquadros no quarto caso.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="105" name="sl" checked>
			   <label for="105"></label>
			   <img src="parte2/12_03_01.png"/>
			   <figcaption>Vamos usar outro raciocínio para construir a reta paralela a <b>t</b> que passa por <b>P</b>. Determine um ponto <b>A</b> sobre a reta, de tal forma que <b>A</b> não esteja na direção da reta perpendicular a <b>t</b> que passa por <b>P</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="106" name="sl">
			   <label for="106"></label>
			   <img src="parte2/12_03_02.png"/>
			   <figcaption>Com centro em <b>A</b>, construa um arco com medida do raio igual a <b>AP</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="107" name="sl">
			   <label for="107"></label>
			   <img src="parte2/12_03_03.png"/>
			   <figcaption>Este arco deve formar uma semi-circunferência, interceptando <b>t</b> em <b>B</b> e <b>C</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="108" name="sl">
			   <label for="108"></label>
			   <img src="parte2/12_03_04.png"/>
			   <figcaption>Com o compasso, "pegue" a medida <b>BP</b> e...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="109" name="sl">
			   <label for="109"></label>
			   <img src="parte2/12_03_05.png"/>
			   <figcaption>... construa o arco com raio <b>BP</b> e centro em <b>C</b>, determinando <b>D</b> na semi-circunferência.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="110" name="sl">
			   <label for="110"></label>
			   <img src="parte2/12_03_06.png"/>
			   <figcaption>A reta <b>PD</b> será paralela a <b>t</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="111" name="sl">
			   <label for="111"></label>
			   <img src="parte2/12_03_07.png"/>
			   <figcaption>De fato, esta construção dá certo pois construímos um trapézio iscósceles; as retas <b>PD</b> e <b>t</b> formam as bases do trapézio, que são paralelas.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="112" name="sl">
			   <label for="112"></label>
			   <img src="parte2/12_03_08.png"/>
			   <figcaption>Agora, com o uso dos esquadros, podemos alinhar com a reta <b>t</b> a hipotenusa de um dos esquadros: neste exemplo, alinhamos a hipotenusa do esquadro de 45. Coloque o outro esquadro ou a régua como apoio em um dos catetos do esquadro de 45.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="113" name="sl">
			   <label for="113"></label>
			   <img src="parte2/12_03_09.png"/>
			   <figcaption>Deixando fixo o esquadro de 60, deslize o esquadro de 45 até chegar no ponto <b>P</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="114" name="sl">
			   <label for="114"></label>
			   <img src="parte2/12_03_10.png"/>
			   <figcaption>Desta forma temos a reta <b>p // t</b> construída com esquadros.</figcaption>
		   </li>
		</ul>
		<img src="parte2/12_03_00.png" class="fundo"/>
  </details></div>
  <img src="parte2/apos_dg_0012c.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Podemos utilizar a régua e o compasso ou o par de esquadros para resolver este exercício. Vamos usar os esquadros para construção e a régua para marcamos a medida de 2cm.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="115" name="sl" checked>
			   <label for="115"></label>
			   <img src="parte2/12_04_01.png"/>
			   <figcaption>Defina um ponto <b>A &isin; t</b>. Para definir o LG de todos os pontos com distância 2cm até a reta <b>t</b>, vamos construir uma reta perpendicular a <b>t</b> passando por <b>A</b>. Alinhando um cateto do esquadro de 45 e apoiando a hipotenusa com o outro esquadro...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="116" name="sl">
			   <label for="116"></label>
			   <img src="parte2/12_04_02.png"/>
			   <figcaption>... deixamos fixo o esquadro de 60 e deslizamos o esquadro de 45 até chegar em <b>A</b>. Desta forma, temos a reta <b>a &perp; t</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="117" name="sl">
			   <label for="117"></label>
			   <img src="parte2/12_04_03.png"/>
			   <figcaption>Podemos usar a régua para medir a distância de 2cm nos dois semi-planos definidos pela reta <b>t</b>, definindo os pontos <b>B</b> e <b>C</b> pertencentes à reta <b>a</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="118" name="sl">
			   <label for="118"></label>
			   <img src="parte2/12_04_04.png"/>
			   <figcaption>Agora podemos construir as retas paralelas à reta <b>t</b> que passam por <b>B</b> e <b>C</b>. Alinhando a hipotenusa de um dos esquadros com a reta <b>t</b>, e deixando o outro esquadro como apoio... </figcaption>
		   </li>
		   <li>
			   <input type="radio" id="119" name="sl">
			   <label for="119"></label>
			   <img src="parte2/12_04_05.png"/>
			   <figcaption>... deslizamos o esquadro de 60 até chegam em <b>C</b>, deixando fixo o esquadro de 45.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="120" name="sl">
			   <label for="120"></label>
			   <img src="parte2/12_04_06.png"/>
			   <figcaption>Aproveitando o alinhamento, podemos deslizar o esquadro de 60 até chegar em <b>B</b>. Logo, construímos as retas <b>p<sub>1</sub></b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="121" name="sl">
			   <label for="121"></label>
			   <img src="parte2/12_04_07.png"/>
			   <figcaption>... e <b>p<sub>2</sub></b>, que definem o lugar geométrico dos pontos com distância 2cm à reta <b>t</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte2/12_04_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte2" class="topo">voltar ao topo</a></p>
  <img src="parte2/apos_dg_0013.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos os esquadros e o compasso para resolver este exercício. Lembrando que para construir uma circunferência tangente a uma reta, o raio deve ser perpendicular à reta no ponto de tangência.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="122" name="sl" checked>
			   <label for="122"></label>
			   <img src="parte2/13_01_01.png"/>
			   <figcaption>Primeiro vamos construir a reta paralela ao segmento <b>AB</b>, com distância <b>r</b>. Podemos construir a reta perpendicular a <b>AB</b> que passa pelo ponto <b>A</b> com os esquadros. Alinhando um cateto do esquadro de 45, e apoiando a hipotenusa no outro esquadro...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="123" name="sl">
			   <label for="123"></label>
			   <img src="parte2/13_01_02.png"/>
			   <figcaption>... deslizamos o esquadro de 45 até chegar no ponto <b>A</b>, deixando fixo o outro esquadro.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="124" name="sl">
			   <label for="124"></label>
			   <img src="parte2/13_01_03.png"/>
			   <figcaption>Usando o compasso, "pegamos" a medida do raio <b>r</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="125" name="sl">
			   <label for="125"></label>
			   <img src="parte2/13_01_04.png"/>
			   <figcaption>... e marcamos a partir do ponto <b>A</b> na reta perpendicular que construímos: logo, temos que <b>AD &perp; AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="126" name="sl">
			   <label for="126"></label>
			   <img src="parte2/13_01_05.png"/>
			   <figcaption>Podemos alinhar a hipotenusa do esquadro de 45 com <b>AB</b>, deixando o outro esquadro apoiado em um cateto do esquadro de 45.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="127" name="sl">
			   <label for="127"></label>
			   <img src="parte2/13_01_06.png"/>
			   <figcaption>Deslizando o esquadro de 45 até chegar em <b>D</b>, deixando fixo o outro esquadro, construímos a reta <b>s // AB</b> com distância <b>r</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="128" name="sl">
			   <label for="128"></label>
			   <img src="parte2/13_01_07.png"/>
			   <figcaption>Agora podemos construir a reta perpendicular ao segmento <b>BC</b> que passa pelo ponto <b>C</b>. Podemos alinhar um cateto do esquadro de 60 com <b>BC</b>, deixando o outro esquadro apoiado na hipotenusa do esquadro de 60.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="129" name="sl">
			   <label for="129"></label>
			   <img src="parte2/13_01_08.png"/>
			   <figcaption>Deixando fixo o esquadro de 45, deslizamos o esquadro de 60 até chegar em <b>C</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="130" name="sl">
			   <label for="130"></label>
			   <img src="parte2/13_01_09.png"/>
			   <figcaption>Com o compasso, "pegamos" a distância <b>r</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="131" name="sl">
			   <label for="131"></label>
			   <img src="parte2/13_01_10.png"/>
			   <figcaption>... e marcamos esta distância a partir de <b>C</b>, encontrando <b>CE &perp; BC</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="132" name="sl">
			   <label for="132"></label>
			   <img src="parte2/13_01_11.png"/>
			   <figcaption>Agora podemos alinhar a hipotenusa do esquadro de 45 com <b>BC</b>, deixando um cateto apoiado com o outro esquadro...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="133" name="sl">
			   <label for="133"></label>
			   <img src="parte2/13_01_12.png"/>
			   <figcaption>... e deixamos fixo o esquadro de 60 para deslizar o esquadro de 45 até chegar em <b>E</b>. Logo, temos a reta <b>t // BC</b> com distância <b>r</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="134" name="sl">
			   <label for="134"></label>
			   <img src="parte2/13_01_13.png"/>
			   <figcaption>A interseção entre <b>s</b> e <b>t</b> é o centro da circunferência tangente aos segmentos <b>AB</b> e <b>BC</b> com raio <b>r</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte2/13_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte2/apos_dg_0013a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>No exercício anterior, construímos as retas perpendiculares e paralelas com os esquadros. Neste exercício, vamos utilizar a régua e o compasso.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="135" name="sl" checked>
			   <label for="135"></label>
			   <img src="parte2/13_02_01.png"/>
			   <figcaption>Como vamos construir uma circunferência tangente à reta <b>t</b>, dado o raio <b>r</b>, construiremos a reta perpendicular a <b>t</b> por um ponto qualquer <b>B &isin; t</b>. Com centro em <b>B</b>, defina um raio qualquer para marcar o ponto <b>C &isin; t</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="136" name="sl">
			   <label for="136"></label>
			   <img src="parte2/13_02_02.png"/>
			   <figcaption>Usando o mesmo raio <b>BC</b>, encontre o ponto <b>D &isin; t</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="137" name="sl">
			   <label for="137"></label>
			   <img src="parte2/13_02_03.png"/>
			   <figcaption>Construindo a mediatriz de <b>CD</b>, teremos a reta perpendicular a <b>t</b> que passa por <b>B</b>. Com centro em <b>D</b>, defina um arco com raio maior do que <b>BC</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="138" name="sl">
			   <label for="138"></label>
			   <img src="parte2/13_02_04.png"/>
			   <figcaption>... e com centro em <b>C</b> e mesmo raio, encontramos o ponto <b>E</b> tal que <b>s &equiv; BE &perp; t &equiv; BC</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="139" name="sl">
			   <label for="139"></label>
			   <img src="parte2/13_02_05.png"/>
			   <figcaption>Com o compasso, "pegue" a medida <b>r</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="140" name="sl">
			   <label for="140"></label>
			   <img src="parte2/13_02_06.png"/>
			   <figcaption>... e marque esta distância <b>r</b> a partir de <b>B</b> na reta <b>s</b>. Assim, encontramos o ponto <b>F</b>. Neste ponto, podemos construir a reta paralela a <b>t</b> com distância <b>r</b>. Já vimos 3 construções diferentes para usar de retas paralelas. Neste exemplo, vamos fazer esta reta paralela usando a construção do losango.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="141" name="sl">
			   <label for="141"></label>
			   <img src="parte2/13_02_07.png"/>
			   <figcaption>Com centro em <b>F</b>, construímos um arco de medida qualquer que intercepte <b>t</b> em <b>G</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="142" name="sl">
			   <label for="142"></label>
			   <img src="parte2/13_02_08.png"/>
			   <figcaption>Com a mesma medida <b>FG</b>, encontramos <b>H &isin; t</b> e <b>GH = FG</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="143" name="sl">
			   <label for="143"></label>
			   <img src="parte2/13_02_09.png"/>
			   <figcaption>Com a mesma medida, construimos o arco com centro em <b>H</b>, interceptando o primeiro arco que construimos com centro em <b>F</b> no ponto <b>I</b>. A reta <b>FI</b> é paralela à reta <b>t</b></figcaption>
		   </li>
		   <li>
			   <input type="radio" id="144" name="sl">
			   <label for="144"></label>
			   <img src="parte2/13_02_10.png"/>
			   <figcaption>Agora podemos "pegar" a medida do raio <b>r</b> para definir a distância do centro da circunferência procurada com o ponto <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="145" name="sl">
			   <label for="145"></label>
			   <img src="parte2/13_02_11.png"/>
			   <figcaption>Este é o segundo lugar geométrico do centro da circunferência tangente: uma circunferência com centro em A e raio <b>r</b>. Esta circunferência intercepta a reta <b>u // t</b> nos pontos <b>O</b> e <b>O'</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="146" name="sl">
			   <label for="146"></label>
			   <img src="parte2/13_02_12.png"/>
			   <figcaption>Construimos uma solução com linha contínua e outra com linha tracejada.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="147" name="sl">
			   <label for="147"></label>
			   <img src="parte2/13_02_13.png"/>
			   <figcaption>Neste exemplo, temos 2 soluções. Caso a <b>Circunf(A,r)</b> não intercepte a reta <b>u // t</b>, não temos solução. E caso a <b>Circunf(A,r) </b> seja tangente à reta <b>u // t</b>, temos apenas 1 solução.</figcaption>
		   </li>
		</ul>
		<img src="parte2/13_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte2/apos_dg_0013b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Neste exercício, vamos utilizar o par de esquadros e o compasso.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="148" name="sl" checked>
			   <label for="148"></label>
			   <img src="parte2/13_03_01.png"/>
			   <figcaption>Vamos construir uma reta perpendicular a um dos segmentos, escolhendo um ponto <b>A</b> pertencente ao primeiro segmento. Com um cateto alinhado com o segmento e o esquadro de 60 apoiado na hipotenusa...<b>t</b></figcaption>
		   </li>
		   <li>
			   <input type="radio" id="149" name="sl">
			   <label for="149"></label>
			   <img src="parte2/13_03_02.png"/>
			   <figcaption>... deslizamos o esquadro de 45 até chegar em <b>A</b>, deixando o esquadro de 60 fixo. Logo, temos a perpendicular ao segmento que passa por <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="150" name="sl">
			   <label for="150"></label>
			   <img src="parte2/13_03_03.png"/>
			   <figcaption>Agora "pegamos" a medida do raio <b>d</b> com o compasso...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="151" name="sl">
			   <label for="151"></label>
			   <img src="parte2/13_03_04.png"/>
			   <figcaption>... e com centro em <b>A</b>, construímos o arco com raio <b>d</b>, definindo o segmento <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="152" name="sl">
			   <label for="152"></label>
			   <img src="parte2/13_03_05.png"/>
			   <figcaption>Agora podemos construir a reta paralela ao segmento que passa por <b>B</b>. Alinhando a hipotenusa do esquadro de 60 no segmento, e deixando um cateto apoiado com o outro esquadro...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="153" name="sl">
			   <label for="153"></label>
			   <img src="parte2/13_03_06.png"/>
			   <figcaption>... deslizamos o esquadro de 60 até chegar em <b>B</b> com o esquadro de 45 fixo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="154" name="sl">
			   <label for="154"></label>
			   <img src="parte2/13_03_07.png"/>
			   <figcaption>Podemos fazer a mesma construção no outro segmento, com um ponto <b>C</b> em qualquer posição deste segundo segmento.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="155" name="sl">
			   <label for="155"></label>
			   <img src="parte2/13_03_08.png"/>
			   <figcaption>Alinhando um cateto do esquadro de 45 e deslizando até chegar em <b>C</b>, temos a reta perpendicular construída.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="156" name="sl">
			   <label for="156"></label>
			   <img src="parte2/13_03_09.png"/>
			   <figcaption>Podemos "pegar" a medida do raio <b>d</b> com o compasso...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="157" name="sl">
			   <label for="157"></label>
			   <img src="parte2/13_03_10.png"/>
			   <figcaption>... e marcá-la na perpendicular a partir do ponto <b>C</b>, encontrando o ponto <b>D</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="158" name="sl">
			   <label for="158"></label>
			   <img src="parte2/13_03_11.png"/>
			   <figcaption>Alinhamos a hipotenusa do esquadro de 60 com o segmento...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="159" name="sl">
			   <label for="159"></label>
			   <img src="parte2/13_03_12.png"/>
			   <figcaption>... e deslizamos este esquadro até chegar em <b>D</b>, deixando o outro esquadro fixo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="160" name="sl">
			   <label for="160"></label>
			   <img src="parte2/13_03_13.png"/>
			   <figcaption>A interseção das retas paralelas aos segmentos é o centro <b>O</b> da circunferência de raio <b>r</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte2/13_03_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte2" class="topo">voltar ao topo</a></p>
  <img src="parte2/apos_dg_0014.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Você pode fazer a construção da reta paralela com régua e compasso ou com esquadros.</p>
	<img src="parte2/14_01_00.png"/>
	<figcaption>Como a circunferência deve passar por <b>A</b> e <b>B</b>, o centro estará na mediatriz de <b>AB</b>.</figcaption>
  </details></div>
  <img src="parte2/apos_dg_0014a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Você pode fazer a construção da reta paralela com régua e compasso ou com esquadros.</p>
	<img src="parte2/14_02_00.png"/>
	<figcaption>Antes de construir a circunferência, lembre-se de determinar o raio <b>OT</b> por meio de uma perpendicular à reta <b>t</b>.</figcaption>
  </details></div>
  <img src="parte2/apos_dg_0014b.png"/>
  <div class="combo">&#x1f4cf; &#x1f4d0; <span class="atv">Atividade 3</span></div>
  <p class="topop"><a href="#parte2" class="topo">voltar ao topo</a></p>
  <img src="parte2/apos_dg_0015.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Você pode fazer as construções com régua e compasso ou com esquadros e o compasso.</p>
	<img src="parte2/15_01_00.png"/>
	<figcaption>Para construir a reta paralela <b>s</b>, lembre-se de construir o segmento <b>CD &perp; r</b> para marcar o segmento <b>d</b>.</figcaption>
  </details></div>
  <img src="parte2/apos_dg_0015a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Neste exercício, você pode usar a régua e o compasso para construir as retas perpendiculares e paralelas ou o par de esquadros com o compasso. Vamos ver como fica a construção com os esquadros e o compasso.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="161" name="sl" checked>
			   <label for="161"></label>
			   <img src="parte2/15_02_01.png"/>
			   <figcaption>Podemos escolher um ponto qualquer <b>A &isin; b</b> para construir a reta perpendicular à reta <b>b</b>. Alinhando um cateto do esquadro de 45 com a reta <b>b</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="162" name="sl">
			   <label for="162"></label>
			   <img src="parte2/15_02_02.png"/>
			   <figcaption>... deixando o outro esquadro fixo, deslizamos o esquadro de 45 até chegar em <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="163" name="sl">
			   <label for="163"></label>
			   <img src="parte2/15_02_03.png"/>
			   <figcaption>Podemos usar o compasso para "pegar" a media <b>r</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="164" name="sl">
			   <label for="164"></label>
			   <img src="parte2/15_02_04.png"/>
			   <figcaption>... e marcá-la na reta perpendicular à reta <b>b</b> a partir do ponto <b>A</b>, definindo o segmento <b>AB &perp; b</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="165" name="sl">
			   <label for="165"></label>
			   <img src="parte2/15_02_05.png"/>
			   <figcaption>No prolongamento de <b>AB</b>, marcamos o raio <b>r</b> para encontrar a outra reta paralela à reta <b>b</b>, definindo <b>BC &perp; b</b></figcaption>
		   </li>
		   <li>
			   <input type="radio" id="166" name="sl">
			   <label for="166"></label>
			   <img src="parte2/15_02_06.png"/>
			   <figcaption>Alinhando a hipotenusa do esquadro de 45 com a reta <b>b</b>, deixando o esquadro de 60 como apoio fixo...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="167" name="sl">
			   <label for="167"></label>
			   <img src="parte2/15_02_07.png"/>
			   <figcaption>... deslizamos o esquadro de 45 até chegar em <b>B</b>, definindo a primeira paralela, e...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="168" name="sl">
			   <label for="168"></label>
			   <img src="parte2/15_02_08.png"/>
			   <figcaption>... deslizamos este esquadro até chegar em <b>C</b>, definindo a segunda paralela à reta <b>b</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="169" name="sl">
			   <label for="169"></label>
			   <img src="parte2/15_02_09.png"/>
			   <figcaption>Como o centro da solução pertence à reta <b>a</b>, teremos 2 soluções: <b>O &equiv; s &cap; a</b> e <b>O' &equiv; t &cap; a</b>.Construímos estas circunferências com raios de medida <b>r</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte2/15_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte2/apos_dg_0015b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4dd; Propriedades</summary>
	<p>Vamos ver algumas propriedades deste lugar geométrico.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="171" name="sl" checked>
			   <label for="171"></label>
			   <img src="parte2/15_03_01.png"/>
			   <figcaption>Considere as bissetrizes <b>b<sub>1</sub></b> e <b>b<sub>2</sub></b> dos ângulos formados entre as retas <b>r</b> e <b>s</b>, com vértice <b>O</b>. Escolha um ponto <b>Q &isin; b<sub>2</sub></b>. O ponto <b>P &isin; b<sub>1</sub></b> é equidistante das retas <b>r</b> e <b>s</b>, ou seja, <b>PP' = PP''</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="172" name="sl">
			   <label for="172"></label>
			   <img src="parte2/15_03_02.png"/>
			   <figcaption>Se construirmos o segmento <b>QQ'' &perp; s</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="173" name="sl">
			   <label for="173"></label>
			   <img src="parte2/15_03_03.png"/>
			   <figcaption>... e <b>QQ' &perp; r</b>, teremos a mesma medida <b>QQ' = QQ''</b>. Esta é uma das propriedades da bissetriz: lugar geométrico dos pontos equidistantes de duas retas. </figcaption>
		   </li>
		   <li>
			   <input type="radio" id="174" name="sl">
			   <label for="174"></label>
			   <img src="parte2/15_03_04.png"/>
			   <figcaption>Temos o caso de congruência LLAr (lado, lado, ângulo reto): <b>&#9651;OPP' = &#9651;OPP''</b>, pois <b>OP</b> é lado comum, <b>PP' = PP''</b> e <b>&angsph;P' = &angsph;P'' = 90&deg;</b>. Logo, os ângulos <b>&angsph;POP'</b> e <b>&angsph;POP''</b> são iguais. O mesmo vale para a congruência de <b>&#9651;OQQ' = &#9651;OQQ''</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="175" name="sl">
			   <label for="175"></label>
			   <img src="parte2/15_03_05.png"/>
			   <figcaption>Portanto, temos os ângulos <b>&alpha;</b> e <b>&beta;</b> que definem outra propriedade da bissetriz: ela divide os ângulos formados entre<b>r</b> e <b>s</b> ao meio.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="170" name="sl">
			   <label for="170"></label>
			   <img src="parte2/15_03_05.png"/>
			   <figcaption>O ângulo formado entre as bissetrizes <b>b<sub>1</sub></b> e <b>b<sub>2</sub></b> mede <b>&alpha; + &beta;</b>. Como <b>&alpha; + &alpha; + &beta; + &beta; = 180&deg;</b>, temos que <b>&alpha; + &beta; = 90&deg;</b>, ou seja, as bissetrizes dos ângulos suplementares são perpendiculares.</figcaption>
		   </li>
		</ul>
		<img src="parte2/15_03_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte2" class="topo">voltar ao topo</a></p>
  <img src="parte2/apos_dg_0016.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos a régua e o compasso para construir a bissetriz.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="176" name="sl" checked>
			   <label for="176"></label>
			   <img src="parte2/16_01_01.png"/>
			   <figcaption>Com centro no vértice <b>A</b>, construímos um arco de circunferência de raio qualquer que intercepte os lados do ângulo nos pontos <b>D</b> e <b>E</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="177" name="sl">
			   <label for="177"></label>
			   <img src="parte2/16_01_02.png"/>
			   <figcaption>Com centro em <b>D</b>, construímos um arco com raio de medida qualquer que seja maior do que a metade de <b>DE</b> (é a construção de um ponto da mediatriz de <b>DE</b>).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="178" name="sl">
			   <label for="178"></label>
			   <img src="parte2/16_01_03.png"/>
			   <figcaption>Com centro em <b>E</b>, construímos um arco com raio igual ao que fizemos no ponto <b>D</b>, encontrando o ponto <b>F</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="179" name="sl">
			   <label for="179"></label>
			   <img src="parte2/16_01_04.png"/>
			   <figcaption>Usando a régua ou um dos esquadros, construímos a semi-reta <b>OF</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="180" name="sl">
			   <label for="180"></label>
			   <img src="parte2/16_01_05.png"/>
			   <figcaption>Esta semi-reta é a bissetriz do ângulo <b>&angsph;A</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte2/16_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte2/apos_dg_0016a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos utilizar a régua, os esquadros e o compasso neste exercício. A ideia é não usar a interseção das retas para construir a bissetriz.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="181" name="sl" checked>
			   <label for="181"></label>
			   <img src="parte2/16_02_01.png"/>
			   <figcaption>Vamos nomear as retas <b>r</b> e <b>s</b>. Neste primeiro exemplo, vamos usar a ideia de definir uma terceira reta <b>t</b>, concorrente com <b>r</b> e <b>s</b> nos pontos <b>A</b> e <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="182" name="sl">
			   <label for="182"></label>
			   <img src="parte2/16_02_02.png"/>
			   <figcaption>No vértice <b>A</b>, podemos construir a bissetriz do <b>&angsph;DAE</b>: com centro em <b>A</b> e um arco com raio qualquer, encontre os pontos <b>D</b> e <b>E</b> sobre <b>t</b> e <b>r</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="183" name="sl">
			   <label for="183"></label>
			   <img src="parte2/16_02_03.png"/>
			   <figcaption>Com centro em <b>D</b>, construa um arco com raio maior do que a metade de <b>DE</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="184" name="sl">
			   <label for="184"></label>
			   <img src="parte2/16_02_04.png"/>
			   <figcaption>... e construa um arco de mesmo raio com centro em <b>E</b>, encontrando o ponto <b>F</b>. A semi-reta <b>OF</b> é a bissetriz do <b>&angsph;DAE</b>. Podemos construir a bissetriz do suplementar deste ângulo, ou podemos usar a propriedade de que as bissetrizes de ângulos suplementares são perpendiculares.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="185" name="sl">
			   <label for="185"></label>
			   <img src="parte2/16_02_05.png"/>
			   <figcaption>Usando a propriedade, podemos alinhar um cateto do esquadro de 45 com a bissetriz, deixando o outro esquadro como apoio fixo...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="186" name="sl">
			   <label for="186"></label>
			   <img src="parte2/16_02_06.png"/>
			   <figcaption>... e deslizamos o esquadro de 45 até chegar em <b>A</b>. Logo, temos a bissetriz do ângulo suplementar do <b>&angsph;DAE</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="187" name="sl">
			   <label for="187"></label>
			   <img src="parte2/16_02_07.png"/>
			   <figcaption>No vértice <b>B</b>, podemos fazer a mesma construção: bissetriz do <b>&angsph;GBH</b> e a perpendicular à bissetriz. Todos os pontos das bissetrizes <b>biss(A)</b> são esquidistantes de <b>r</b> e <b>t</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="188" name="sl">
			   <label for="188"></label>
			   <img src="parte2/16_02_08.png"/>
			   <figcaption>Todos os pontos das bissetrizes <b>biss(B)</b> são esquidistantes de <b>s</b> e <b>t</b>. Logo, nas interseções de <b>biss(A)</b> e <b>biss(B)</b>, temos os pontos equidistantes de <b>r</b> e <b>s</b>, ou seja, <b>J</b> e <b>K</b> definem a <b>biss(r,s)</b>. Agora vamos usar outro raciocínio: escolha um ponto <b>A &isin; r</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="189" name="sl">
			   <label for="189"></label>
			   <img src="parte2/16_02_09.png"/>
			   <figcaption>Neste ponto <b>A</b>, construa a reta <b>t // s</b>. Use os esquadros ou a régua e compasso para fazer esta construção.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="190" name="sl">
			   <label for="190"></label>
			   <img src="parte2/16_02_10.png"/>
			   <figcaption>Agora vamos construir o triângulo isósceles de base <b>BC</b> e vértice <b>A</b>: com centro em <b>A</b>, construa um arco com raio qualquer que intercepte as retas <b>r</b> e <b>t</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="191" name="sl">
			   <label for="191"></label>
			   <img src="parte2/16_02_11.png"/>
			   <figcaption>Prolongando-se o segmento <b>BC</b>, encontramos o ponto <b>D</b>. Se imaginarmos que o vértice do encontro de <b>r</b> e <b>s</b> é um ponto <b>V</b>, temos que os triângulos <b>&#9651;ABC</b> e <b>&#9651;VDB</b> serão semelhantes, pois a reta <b>r</b> é comum e as retas <b>t</b> e <b>s</b> são paralelas.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="192" name="sl">
			   <label for="192"></label>
			   <img src="parte2/16_02_12.png"/>
			   <figcaption>Logo, a mediatriz da base <b>BD</b> do <b>&#9651;VDB</b> será a bissetriz do ângulo formado entre <b>r</b> e <b>s</b>. Esta mediatriz será paralela à bissetriz do <b>&angsph;BAC</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte2/16_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte2/apos_dg_0016b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos usar a régua e o compasso neste exercício.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="193" name="sl" checked>
			   <label for="193"></label>
			   <img src="parte2/16_03_01.png"/>
			   <figcaption>Considere uma reta <b>r</b> e um ponto qualquer <b>A &isin; r</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="194" name="sl">
			   <label for="194"></label>
			   <img src="parte2/16_03_02.png"/>
			   <figcaption>Se construirmos o arco com centro em <b>A</b> e um raio qualquer, que intercepte <b>r</b> nos pontos <b>B</b> e <b>C</b>, estamos considerando o <b>&angsph;BAC = 180&deg;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="195" name="sl">
			   <label for="195"></label>
			   <img src="parte2/16_03_03.png"/>
			   <figcaption>Logo, podemos construir sua bissetriz (do mesmo jeito que fizemos com mediatriz): com centro em <b>B</b> e raio com medida maior do que <b>AB</b>, construimos um arco... </figcaption>
		   </li>
		   <li>
			   <input type="radio" id="196" name="sl">
			   <label for="196"></label>
			   <img src="parte2/16_03_04.png"/>
			   <figcaption>... e com centro em <b>C</b>, construimos um arco com raio de mesma medida, determinando o ponto <b>D</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="197" name="sl">
			   <label for="197"></label>
			   <img src="parte2/16_03_05.png"/>
			   <figcaption>A semi-reta <b>AD</b> será a bissetriz de <b>180&deg;</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte2/16_03_00.png" class="fundo"/>
  </details></div>
  <img src="parte2/apos_dg_0016c.png"/>
  <p class="topop"><a href="#parte2" class="topo">voltar ao topo</a></p>
  <img src="parte2/apos_dg_0017.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Neste exercício, vamos utilizar a régua e o compasso. Vamos determinar o centro da circunferência inscrita, que fica tangente aos 3 lados do triângulo.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="198" name="sl" checked>
			   <label for="198"></label>
			   <img src="parte2/17_01_01.png"/>
			   <figcaption>O incentro do triângulo está no encontro das 3 bissetrizes dos ângulos internos do triângulo. Como precisamos da interseção de 2 retas para determinar o ponto, vamos construir apenas 2 bissetrizes. Com centro em <b>A</b>, determine um arco com raio qualquer que intercepte os lados <b>AC</b> e <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="199" name="sl">
			   <label for="199"></label>
			   <img src="parte2/17_01_02.png"/>
			   <figcaption>Com centro em <b>D</b> e em <b>E</b>, construímos os arcos com mesma medida de raio, que seja maior do que a metade de <b>DE</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="200" name="sl">
			   <label for="200"></label>
			   <img src="parte2/17_01_03.png"/>
			   <figcaption>A semi-reta <b>AF</b> é a bissetriz do <b>&angsph;A</b>, relativa ao lado <b>a</b>, que podemos nomear como <b>b<sub>a</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="201" name="sl">
			   <label for="201"></label>
			   <img src="parte2/17_01_04.png"/>
			   <figcaption>Com centro em <b>B</b>, definimos um arco com raio de medida qualquer que intercepte os lados <b>AB</b> e <b>BC</b> do triângulo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="202" name="sl">
			   <label for="202"></label>
			   <img src="parte2/17_01_05.png"/>
			   <figcaption>Com centros em <b>G</b> e em <b>H</b> e raios iguais a uma medida maior do que a metade de <b>GH</b>, definimos os arcos que se cortam em <b>J</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="203" name="sl">
			   <label for="203"></label>
			   <img src="parte2/17_01_06.png"/>
			   <figcaption>A semi-reta <b>AJ</b> é a bissetriz do <b>&angsph;B</b>, relativa ao lado <b>b</b>, que podemos nomear como <b>b<sub>b</sub></b>. A interseção das bissetrizes construídas é o incentro <b>I</b> do triângulo. Não é necessária a construção da bissetriz do <b>&angsph;C</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="204" name="sl">
			   <label for="204"></label>
			   <img src="parte2/17_01_07.png"/>
			   <figcaption>Para determinarmos o raio da circunferência inscrita, podemos usar os esquadros, ou o compasso. Se construirmos um arco com centro em <b>I</b>, que intercepte um dos lados do triângulo nos pontos <b>K</b> e <b>L</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="205" name="sl">
			   <label for="205"></label>
			   <img src="parte2/17_01_08.png"/>
			   <figcaption>... construímos a mediatriz de <b>KL</b> com arcos centrados em <b>K</b> e <b>L</b>, com mesmo raio, de medida maior do que a metade de <b>KL</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="206" name="sl">
			   <label for="206"></label>
			   <img src="parte2/17_01_09.png"/>
			   <figcaption>Definimos então o segmento <b>IM &perp; BC</b>. A distância <b>IT<sub>a</sub></b> é o raio da circunferência inscrita.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="207" name="sl">
			   <label for="207"></label>
			   <img src="parte2/17_01_10.png"/>
			   <figcaption>Esta é a solução do problema. Se você quiser, pode construir a reta perpendicular <b>IM</b> com os esquadros. Note que fizemos esta perpendicular ao lado <b>BC</b>, mas ela pode ser feita em qualquer um dos lados do triângulo.</figcaption>
		   </li>
		</ul>
		<img src="parte2/17_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte2/apos_dg_0017a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos utilizar a régua, os esquadros e o compasso neste exercício. As retas perpendiculares podem ser construídas com os esquadros ou com a régua e o compasso.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="208" name="sl" checked>
			   <label for="208"></label>
			   <img src="parte2/17_02_01.png"/>
			   <figcaption>O centro de uma circunferência ex-inscrita é determinado pelo encontro de duas bissetrizes dos ângulos externos do triângulo com a bissetriz de um ângulo interno. Vamos começar definindo as bissetrizes dos ângulos externos relativos aos lados <b>AB</b> e <b>BC</b>. Prolongue estes lados.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="209" name="sl">
			   <label for="209"></label>
			   <img src="parte2/17_02_02.png"/>
			   <figcaption>Construa a bissetriz do <b>&angsph;DAE</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="210" name="sl">
			   <label for="210"></label>
			   <img src="parte2/17_02_03.png"/>
			   <figcaption>Vamos chamar esta bissetriz de <b>biss<sub>1</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="211" name="sl">
			   <label for="211"></label>
			   <img src="parte2/17_02_04.png"/>
			   <figcaption>Agora vamos construir a bissetriz do <b>&angsph;GCH</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="212" name="sl">
			   <label for="212"></label>
			   <img src="parte2/17_02_05.png"/>
			   <figcaption>A semi-reta <b>CJ</b> define esta bissetriz.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="213" name="sl">
			   <label for="213"></label>
			   <img src="parte2/17_02_06.png"/>
			   <figcaption>Vamos nomear esta semi-reta de <b>biss<sub>2</sub></b>. O encontro destas bissetrizes é o primeiro ex-incentro, relativo ao lado <b>AC = b</b>, que nomeamos como <b>I<sub>b</sub></b>. Se construirmos a bissetriz do <b>&angsph;B</b>, ela passa pelo ex-incentro <b>I<sub>b</sub></b></figcaption>
		   </li>
		   <li>
			   <input type="radio" id="214" name="sl">
			   <label for="214"></label>
			   <img src="parte2/17_02_07.png"/>
			   <figcaption>Agora vamos encontrar o raio desta circunferência. No exercício anterior, vimos como encontrar o raio da circunferência inscrita com o compasso. Com os esquadros, temos que alinhar o cateto de um esquadro com um lado (por exemplo, <b>AB</b>), deixando o outro apoiado na hipotenusa e fixo...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="215" name="sl">
			   <label for="215"></label>
			   <img src="parte2/17_02_08.png"/>
			   <figcaption>E deslizamos o esquadro alinhado até chegar em <b>I<sub>b</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="216" name="sl">
			   <label for="216"></label>
			   <img src="parte2/17_02_09.png"/>
			   <figcaption>O raio da circunferência ex-inscrita mede <b>I<sub>b</sub>T<sub>1</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="217" name="sl">
			   <label for="217"></label>
			   <img src="parte2/17_02_10.png"/>
			   <figcaption>Agora vamos prolongar os lados <b>AC</b> e <b>BC</b> para encontrar a outra circunferência ex-inscrita. Uma das bissetrizes não precisa ser construída (<b>biss<sub>3</sub></b>), pois os ângulos com vértice em <b>A</b> têm mesma medida: são opostos pelo vértice. Logo, podemos apenas prolongar a <b>biss<sub>1</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="218" name="sl">
			   <label for="218"></label>
			   <img src="parte2/17_02_11.png"/>
			   <figcaption>Construa a bissetriz do <b>&angsph;KBL</b>, que define a <b>biss<sub>4</sub></b>. Logo, temos que <b>I<sub>c</sub> &equiv; biss<sub>3</sub> &cap; biss<sub>4</sub></b>. Defina o raio <b>I<sub>c</sub>T<sub>2</sub> &perp; AC</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="219" name="sl">
			   <label for="219"></label>
			   <img src="parte2/17_02_12.png"/>
			   <figcaption>A última circunferência ex-inscrita é a mais fácil de fazer, pois as bissetrizes <b>biss<sub>5</sub></b> e <b>biss<sub>6</sub></b> são os prolongamentos de <b>biss<sub>4</sub></b> e de <b>biss<sub>2</sub></b>. Logo, temos o ex-incentro <b>I<sub>a</sub></b> e podemos construir a terceira circunferência ex-inscrita.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="220" name="sl">
			   <label for="220"></label>
			   <img src="parte2/17_02_13.png"/>
			   <figcaption>Construa <b>I<sub>a</sub>T<sub>3</sub> &perp; AB</b> e construa a circunferência ex-inscrita relativa ao lado <b>a</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte2/17_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte2/apos_dg_0017b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Você pode fazer as construções com régua e compasso ou com esquadros e o compasso.</p>
	<img src="parte2/17_03_00.png"/>
	<figcaption>Lembre-se de construir o segmento <b>r</b> perpendicular a um dos lados do triângulo.</figcaption>
  </details></div>
  <img src="parte2/apos_dg_0017c.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Você pode fazer as construções com régua e compasso ou com esquadros e o compasso.</p>
	<img src="parte2/17_04_00.png"/>
	<figcaption>Lembre-se de construir o segmento <b>r</b> perpendicular a um dos lados do triângulo. Este segmento tem medida aproximada de 1,4cm.</figcaption>
  </details></div>
  <p class="topop"><a href="#parte2" class="topo">voltar ao topo</a></p>
  <img src="parte2/apos_dg_0018.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Neste exercício, você pode usar a régua e o compasso como instrumentos auxiliares.</p>
	<img src="parte2/18_01_00.png"/>
	<figcaption>Este exercício admite 4 soluções.</figcaption>
  </details></div>
  <img src="parte2/apos_dg_0018a.png"/>
  <div class="combo">&#x1f4cf; &#x1f4d0; <span class="atv">Atividade 4</span></div>
  <img src="parte2/apos_dg_0018b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Você pode usar a régua e o compasso ou os esquadros e o compasso para resolver este exercício.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="221" name="sl" checked>
			   <label for="221"></label>
			   <img src="parte2/18_03_01.png"/>
			   <figcaption>Considere os segmentos <b>s</b> e <b>t</b>. Vamos encontrar a bissetriz do ângulo formado entre <b>s</b> e <b>t</b> sem usar o vértice.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="222" name="sl">
			   <label for="222"></label>
			   <img src="parte2/18_03_02.png"/>
			   <figcaption>Construa a reta <b>u // s</b> que passa por <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="223" name="sl">
			   <label for="223"></label>
			   <img src="parte2/18_03_03.png"/>
			   <figcaption>Defina o arco com centro em <b>A</b>, que intercepta <b>u</b> e <b>t</b> em <b>C</b> e <b>D</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="224" name="sl">
			   <label for="224"></label>
			   <img src="parte2/18_03_04.png"/>
			   <figcaption>Prolongando o segmento <b>CD</b>, encontramos <b>E &isin; s</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="225" name="sl">
			   <label for="225"></label>
			   <img src="parte2/18_03_05.png"/>
			   <figcaption>A bissetriz do ângulo formado entre <b>s</b> e <b>t</b> é a mediatriz de <b>DE</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="226" name="sl">
			   <label for="226"></label>
			   <img src="parte2/18_03_06.png"/>
			   <figcaption>Com a circunferência de centro em <b>A</b> e raio <b>d</b>, encontramos o ponto <b>B &isin; biss(s,t)</b>. Note que usamos apenas uma das interseções: a que está proxima da reta <b>u</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="227" name="sl">
			   <label for="227"></label>
			   <img src="parte2/18_03_07.png"/>
			   <figcaption>Agora você pode construir a circunferência com centro em <b>B</b> e raio <b>r</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte2/18_03_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte2" class="topo">voltar ao topo</a></p>
  <img src="parte2/apos_dg_0019.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Neste exercício, vamos utilizar a régua e o compasso.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="228" name="sl" checked>
			   <label for="228"></label>
			   <img src="parte2/19_01_01.png"/>
			   <figcaption>Para transportar o ângulo <b>&alpha;</b>, podemos construir um arco com centro no vértice do ângulo, com raio qualquer e que intercepte os lados nos pontos <b>B</b> e <b>C</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="229" name="sl">
			   <label for="229"></label>
			   <img src="parte2/19_01_02.png"/>
			   <figcaption>Com a mesma medida, definimos o arco com centro no vértice onde queremos transportar o ângulo: <b>O</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="230" name="sl">
			   <label for="230"></label>
			   <img src="parte2/19_01_03.png"/>
			   <figcaption>Com o compasso, "pegamos" a medida da abertura do ângulo <b>BC</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="231" name="sl">
			   <label for="231"></label>
			   <img src="parte2/19_01_04.png"/>
			   <figcaption>... e construímos o arco com centro em <b>D</b> e raio <b>BC</b>. A semi-reta <b>OE</b> forma ângulo <b>&alpha;</b> com <b>OA</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="232" name="sl">
			   <label for="232"></label>
			   <img src="parte2/19_01_05.png"/>
			   <figcaption>Note que esta construção funciona, pois construímos os triângulos congruentes.</figcaption>
		   </li>
		</ul>
		<img src="parte2/19_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte2/apos_dg_0019a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos utilizar a régua, os esquadros e o compasso neste exercício. Vamos começar com a régua e o compasso.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="233" name="sl" checked>
			   <label for="233"></label>
			   <img src="parte2/19_02_01.png"/>
			   <figcaption>Construa uma reta qualquer e defina um ponto <b>A</b> nesta reta. Relembrando a construção de perpendicular, construimos um arco com centro <b>A</b> e raio <b>AB</b> qualquer...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="234" name="sl">
			   <label for="234"></label>
			   <img src="parte2/19_02_02.png"/>
			   <figcaption>... definindo o ponto <b>C</b> sobre a reta, com mesmo raio.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="235" name="sl">
			   <label for="235"></label>
			   <img src="parte2/19_02_03.png"/>
			   <figcaption>Agora é só construir a mediatriz de <b>BC</b>, com centro em <b>C</b> e um raio maior do que <b>AB</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="236" name="sl">
			   <label for="236"></label>
			   <img src="parte2/19_02_04.png"/>
			   <figcaption>... e centro em <b>B</b> com mesmo raio.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="237" name="sl">
			   <label for="237"></label>
			   <img src="parte2/19_02_05.png"/>
			   <figcaption>A semi-reta <b>AD</b> forma <b>90&deg;</b> com a reta. A construção com os esquadros já foi feita anteriormente, e você pode fazê-la como exercício. Agora vamos escolher um ponto <b>E</b> sobre a reta.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="238" name="sl">
			   <label for="238"></label>
			   <img src="parte2/19_02_06.png"/>
			   <figcaption>Com centro em <b>E</b>, defina um arco de circunferência com raio <b>EF</b> qualquer...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="239" name="sl">
			   <label for="239"></label>
			   <img src="parte2/19_02_07.png"/>
			   <figcaption>... e com centro em <b>F</b>, construa o arco com mesmo raio <b>EF</b>, encontrando a interseção <b>G</b>. Unindo <b>E</b> com <b>G</b>, temos a semi-reta que forma <b>60&deg;</b> com a reta.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="240" name="sl">
			   <label for="240"></label>
			   <img src="parte2/19_02_08.png"/>
			   <figcaption>Esta construção funciona, pois construímos um triângulo equilátero de lado <b>EF</b>. Agora vamos ver como construir o ângulo de <b>60&deg;</b> com os esquadros.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="241" name="sl">
			   <label for="241"></label>
			   <img src="parte2/19_02_09.png"/>
			   <figcaption>Escolha um ponto <b>H</b> sobre a reta, e alinhe a hipotenusa do esquadro de 60 com a reta, apoiando o cateto do ângulo de <b>30&deg;</b> com o outro esquadro fixo, ou seja, deixaremos livre o lado do esquadro de <b>60&deg;</b> para transferí-lo na reta.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="242" name="sl">
			   <label for="242"></label>
			   <img src="parte2/19_02_10.png"/>
			   <figcaption>Deslizando o esquadro de 60 até chegar em <b>H</b>, você consegue construir o ângulo de <b>60&deg;</b> com vértice <b>H</b>. Este ângulo ficou virado para a direita da folha.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="243" name="sl">
			   <label for="243"></label>
			   <img src="parte2/19_02_11.png"/>
			   <figcaption>Se você quiser o ângulo de <b>60&deg;</b> virado para a esquerda, basta mudar o lado de alinhamento do esquadro de 60. O importante é lembrar sempre de deisar o ângulo de <b>60&deg;</b> livre, sem apoio.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="244" name="sl">
			   <label for="244"></label>
			   <img src="parte2/19_02_12.png"/>
			   <figcaption>Deslizando o esquadro do outro lado, você consegue construir o ângulo de <b>60&deg;</b> do outro lado.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="245" name="sl">
			   <label for="245"></label>
			   <img src="parte2/19_02_13.png"/>
			   <figcaption>Assim ficam definidas as duas opções de construção de <b>60&deg;</b>: com o compasso e com os esquadros.</figcaption>
		   </li>
		</ul>
		<img src="parte2/19_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte2/apos_dg_0019b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução: 1&ordf; parte</summary>
	<p>Vamos utilizar a régua, os esquadros e o compasso neste exercício. Vamos começar com a régua e o compasso.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="246" name="sl" checked>
			   <label for="246"></label>
			   <img src="parte2/19_03_01.png"/>
			   <figcaption>Começamos construindo o ângulo de <b>90&deg;</b>, como fizemos no exercício anterior. Podemos prolongar o arco com centro em <b>C</b> para fazer a bissetriz de <b>90&deg;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="247" name="sl">
			   <label for="247"></label>
			   <img src="parte2/19_03_02.png"/>
			   <figcaption>Com centro em <b>C</b>, construa o arco com raio maior do que a metade de <b>EC</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="248" name="sl">
			   <label for="248"></label>
			   <img src="parte2/19_03_03.png"/>
			   <figcaption>... e use este mesmo raio para construir o arco com centro em <b>E</b>, encontrando o ponto <b>F</b> na interseção dos arcos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="249" name="sl">
			   <label for="249"></label>
			   <img src="parte2/19_03_04.png"/>
			   <figcaption>A semi-reta <b>AF</b> forma <b>45&deg;</b> com a reta.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="250" name="sl">
			   <label for="250"></label>
			   <img src="parte2/19_03_05.png"/>
			   <figcaption>Ao construir a bissetriz dos <b>45&deg;</b>, temos o ângulo de <b>22,5&deg; = 22&deg;30'</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="251" name="sl">
			   <label for="251"></label>
			   <img src="parte2/19_03_06.png"/>
			   <figcaption>E a bissetriz de <b>22,5&deg;</b> fornece o ângulo de <b>11,15&deg;</b>. Para construir o ângulo de <b>45&deg;</b> com os esquadros, alinhamos a hipotenusa do esquadro de 45 com a reta, e apoiamos um cateto com o outro esquadro que ficará fixo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="252" name="sl">
			   <label for="252"></label>
			   <img src="parte2/19_03_07.png"/>
			   <figcaption>Ao deslizar o esquadro de 45 até chegar no ponto <b>K</b> pertencente à reta, construimos o ângulo de 45 virado à direita da folha.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="253" name="sl">
			   <label for="253"></label>
			   <img src="parte2/19_03_08.png"/>
			   <figcaption>Note que encontramos o ângulo de <b>135&deg;</b>, que é o suplementar de <b>45&deg;</b>. Se você quiser o ângulo de <b>45&deg;</b> virado à esquerda, basta mudar o lado do apoio do esquadro de 60...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="254" name="sl">
			   <label for="254"></label>
			   <img src="parte2/19_03_09.png"/>
			   <figcaption>... e deslizar o esquadro até chegar no ponto <b>K</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="255" name="sl">
			   <label for="255"></label>
			   <img src="parte2/19_03_10.png"/>
			   <figcaption>Vamos desenhar outra reta no espaço abaixo para construir os outros ângulos.</figcaption>
		   </li>
		</ul>
		<img src="parte2/19_03_00.png" class="fundo"/>
  </details>
  <details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução: 2&ordf; parte</summary>
	<p>Vamos utilizar a régua, os esquadros e o compasso neste exercício. Vamos começar com a régua e o compasso.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="256" name="sl" checked>
			   <label for="256"></label>
			   <img src="parte2/19_03_11.png"/>
			   <figcaption>Escolha um ponto <b>L</b> da reta, e construa um arco com raio qualquer, interceptando a reta em <b>M</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="257" name="sl">
			   <label for="257"></label>
			   <img src="parte2/19_03_12.png"/>
			   <figcaption>Com mesmo raio, construa o arco com centro em <b>M</b>, definindo a semi-reta <b>LN</b> que forma <b>60&deg;</b> com a reta.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="258" name="sl">
			   <label for="258"></label>
			   <img src="parte2/19_03_13.png"/>
			   <figcaption>Construindo a bissetriz dos <b>60&deg;</b>, temos o ângulo de <b>30&deg;</b> construído com régua e compasso.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="259" name="sl">
			   <label for="259"></label>
			   <img src="parte2/19_03_14.png"/>
			   <figcaption>Com a bissetriz de <b>30&deg;</b>, temos o ângulo de <b>15&deg;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="260" name="sl">
			   <label for="260"></label>
			   <img src="parte2/19_03_15.png"/>
			   <figcaption>Quando construímos o ângulo de <b>60&deg;</b>, definimos o suplementar de <b>120&deg;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="261" name="sl">
			   <label for="261"></label>
			   <img src="parte2/19_03_16.png"/>
			   <figcaption>Também temos o ângulo de <b>150&deg;</b>, que é o suplementar de <b>30&deg;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="262" name="sl">
			   <label for="262"></label>
			   <img src="parte2/19_03_17.png"/>
			   <figcaption>Se construirmos a bissetriz do ângulo de <b>150&deg;</b>, temos o ângulo de <b>75&deg;</b> com régua e compasso.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="263" name="sl">
			   <label for="263"></label>
			   <img src="parte2/19_03_18.png"/>
			   <figcaption>Agora vamos construir alguns ângulos com os esquadros. Escolha um ponto <b>R</b> sobre a reta e alinhe o cateto de <b>30&deg;</b> com a reta. Coloque o cateto de <b>60&deg;</b> com o apoio fixo do esquadro de 45...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="264" name="sl">
			   <label for="264"></label>
			   <img src="parte2/19_03_19.png"/>
			   <figcaption>... e deslize o esquadro de 60 até chegar no ponto <b>R</b>. Assim, temos os ângulos de <b>30&deg;</b> e <b>150&deg;</b> construídos com os esquadros. Se você quiser o ângulo de <b>30&deg;</b> virado para o outro lado, basta inverter as posições dos esquadros, como fizemos anteriormente com os ângulos de <b>45&deg;</b> e <b>60&deg;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="265" name="sl">
			   <label for="265"></label>
			   <img src="parte2/19_03_20.png"/>
			   <figcaption>Escolha um ponto <b>S</b> sobre a reta, e apoie os esquadros assim: o de 45 com o cateto alinhado na reta, e o de 60 com o vértice de <b>30&deg;</b> junto com o vértice de <b>45&deg;</b>. Somando os ângulos, temos <b>75&deg;</b>, então deixaremos fixo o esquadro de <b>45&deg;</b>, deslizando o esquadro de 60...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="266" name="sl">
			   <label for="266"></label>
			   <img src="parte2/19_03_21.png"/>
			   <figcaption>... até chegar em <b>S</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="267" name="sl">
			   <label for="267"></label>
			   <img src="parte2/19_03_22.png"/>
			   <figcaption>Desta maneira, temos a construção do ângulo de <b>75&deg;</b> com os esquadros. Conseguimos também o suplementar de <b>105&deg;</b> com esta construção. Então, ficam as opções para você construir nos próximos exercícios: com os esquadros ou com régua e compasso.</figcaption>
		   </li>
		</ul>
		<img src="parte2/19_03_10.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte2" class="topo">voltar ao topo</a></p>
  <img src="parte2/apos_dg_0020.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Neste exercício, vamos utilizar a régua e o compasso.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="268" name="sl" checked>
			   <label for="268"></label>
			   <img src="parte2/20_01_01.png"/>
			   <figcaption>Como a semi-reta <b>OC</b> é bissetriz do <b>&angsph;AOB</b>, vamos transportar a medida do <b>&angsph;AOC</b> para o outro semi-plano definido por <b>OC</b>: construa um arco com raio qualquer, centrado em <b>O</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="269" name="sl">
			   <label for="269"></label>
			   <img src="parte2/20_01_02.png"/>
			   <figcaption>Com o compasso, "pegue" a medida da abertura do ângulo <b>DE</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="270" name="sl">
			   <label for="270"></label>
			   <img src="parte2/20_01_03.png"/>
			   <figcaption>... e construa o arco com centro em <b>E</b> e raio <b>DE</b>. Assim, encontramos o ponto <b>B</b> que define o ângulo procurado.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="271" name="sl">
			   <label for="271"></label>
			   <img src="parte2/20_01_04.png"/>
			   <figcaption>A semi-reta <b>OB</b> define o <b>&angsph;AOB</b>, com bissetriz <b>OC</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte2/20_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte2/apos_dg_0020a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Neste exercício, você pode usar a régua e o compasso como instrumentos auxiliares.</p>
	<img src="parte2/20_02_00.png"/>
	<figcaption>Basta lembrar da construção que fizemos para transportar ângulos. Lembre-se que os arcos com centros nos vértices devem ter mesma medida de raio.</figcaption>
  </details></div>
  <img src="parte2/apos_dg_0020b.png"/>
  <div class="combo">&#x1f4cf; &#x1f4d0; <span class="atv">Atividade 5</span></div>
  <img src="parte2/apos_dg_0020c.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Neste exercício, você pode usar a régua e o compasso como instrumentos auxiliares.</p>
	<img src="parte2/20_04_00.png"/>
	<figcaption>Lembre-se da construção que fizemos para transportar ângulos.</figcaption>
  </details></div>
  <p class="topop"><a href="#parte2" class="topo">voltar ao topo</a></p>
</details>

<details>
  <summary id="parte3">2.1. Arco capaz</summary>
  <p>Material da página 21 até a página 29.</p>
  <img src="parte3/apos_dg_0021.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4dd; Propriedades</summary>
	<p>Vamos ver alguns elementos para o próximo Lugar geométrico.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="272" name="sl" checked>
			   <label for="272"></label>
			   <img src="parte3/21_01_01.png"/>
			   <figcaption>Unindo dois pontos quaisquer <b>A</b> e <b>B</b> de uma circunferência, definimos uma <b>corda</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="273" name="sl">
			   <label for="273"></label>
			   <img src="parte3/21_01_02.png"/>
			   <figcaption>Quando a corda contém o centro da circunferência, temos um <b>diâmetro</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte3/21_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte3/apos_dg_0021a.png"/>
  <p class="topop"><a href="#parte3" class="topo">voltar ao topo</a></p>
  <img src="parte3/apos_dg_0022.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4dd; Demonstração</summary>
	<p>Vamos demonstrar a Propriedade 1. Vamos considerar os 3 casos possíveis: quando um lado do ângulo inscrito define um diâmetro; quando o centro está no interior do ângulo inscrito; e quando o centro está na região externa definida pelo ângulo inscrito.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="274" name="sl" checked>
			   <label for="274"></label>
			   <img src="parte3/22_01_01.png"/>
			   <figcaption>Vamos considerar o vértice <b>P</b> e os lados <b>PA</b> e <b>PB</b>. No primeiro caso, o lado <b>PB</b> define um diâmetro da circunferência.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="275" name="sl">
			   <label for="275"></label>
			   <img src="parte3/22_01_02.png"/>
			   <figcaption>Temos que <b>OP = OA = r</b>, onde <b>r</b> é o raio da circunferência. Logo, o <b>&angsph;OAP = &alpha;</b>, pois o <b>&#9651;AOP</b> é isósceles de base <b>AP</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="276" name="sl" checked>
			   <label for="276"></label>
			   <img src="parte3/22_01_03.png"/>
			   <figcaption>O <b>&angsph;AOB = &beta;</b> é o ângulo central correspondente de <b>&alpha;</b>. Temos que <b>&beta;</b> e <b>&delta;</b> são suplementares, ou seja, <b>&beta; + &delta; = 180&deg;</b>. Temos também que <b>2&alpha; + &delta; = 180&deg;</b>, pois são ângulos internos do <b>&#9651;AOP</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="276a" name="sl" checked>
			   <label for="276a"></label>
			   <img src="parte3/22_01_03.png"/>
			   <figcaption>Logo, temos que <b>2&alpha; + &delta; = &beta; + &delta;</b>, ou seja, <b>2&alpha; = &beta;</b>. Portanto, <b>$\alpha = {\beta \over 2}$</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="277" name="sl">
			   <label for="277"></label>
			   <img src="parte3/22_01_04.png"/>
			   <figcaption>No segundo caso, considere o diâmetro <b>PC</b>, que divide o ângulo <b>&alpha;</b> em <b>&alpha;<sub>1</sub></b> e <b>&alpha;<sub>2</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="278" name="sl" checked>
			   <label for="278"></label>
			   <img src="parte3/22_01_05.png"/>
			   <figcaption>Unindo os pontos <b>A</b> e <b>B</b> com o centro da circunferência, determinamos o ângulo central <b>&beta; = &angsph; AOB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="279" name="sl">
			   <label for="279"></label>
			   <img src="parte3/22_01_06.png"/>
			   <figcaption>O ângulo central está dividido nos ângulos centrais correspondentes de <b>&alpha;<sub>1</sub></b> e <b>&alpha;<sub>2</sub></b>, que são <b>&beta;<sub>1</sub></b> e <b>&beta;<sub>2</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="279a" name="sl">
			   <label for="279a"></label>
			   <img src="parte3/22_01_06.png"/>
			   <figcaption>De acordo com o caso anterior, temos que $\mathsf{\alpha_1 = {\beta_1 \over 2}}$ e $\mathsf{\alpha_2 = {\beta_2 \over 2}}$. Logo, $\mathsf{\alpha = \alpha_1 + \alpha_2 = {\beta_1 \over 2} + {\beta_2 \over 2} = { {\beta_1 + \beta_2} \over 2} = {\beta \over 2}}$.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="280" name="sl" checked>
			   <label for="280"></label>
			   <img src="parte3/22_01_07.png"/>
			   <figcaption>No terceiro caso, considere o diâmetro <b>PC</b>, que define o ângulo <b>&alpha;</b> como <b>&alpha;<sub>1</sub> &minus; &alpha;<sub>2</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="281" name="sl" checked>
			   <label for="281"></label>
			   <img src="parte3/22_01_08.png"/>
			   <figcaption>Unindo os pontos <b>A</b> e <b>B</b> com o centro da circunferência, determinamos o ângulo central <b>&beta; = &angsph; AOB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="282" name="sl">
			   <label for="282"></label>
			   <img src="parte3/22_01_09.png"/>
			   <figcaption>O ângulo central tem a seguinte relação com os ângulos centrais correspondentes de <b>&alpha;<sub>1</sub></b> e <b>&alpha;<sub>2</sub></b>: <b>&beta; = &beta;<sub>1</sub> &minus; &beta;<sub>2</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="282a" name="sl">
			   <label for="282a"></label>
			   <img src="parte3/22_01_09.png"/>
			   <figcaption>De acordo com o primeiro caso provado, temos que $\mathsf{\alpha_1 = {\beta_1 \over 2}}$ e $\mathsf{\alpha_2 = {\beta_2 \over 2}}$. Logo, $\mathsf{\alpha = \alpha_1 - \alpha_2 = {\beta_1 \over 2} - {\beta_2 \over 2} = { {\beta_1 - \beta_2} \over 2} = {\beta \over 2}}$. Portanto, a propriedade vale em todos os casos, ou seja, o ângulo inscrito sempre vale a metade da medida do ângulo central correspondente.</figcaption>
		   </li>
		</ul>
		<img src="parte3/22_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte3/apos_dg_0022a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4dd; Propriedades</summary>
	<p>Vamos ver alguns do ângulo de segmento.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="283" name="sl" checked>
			   <label for="283"></label>
			   <img src="parte3/22_02_01.png"/>
			   <figcaption>Vamos definir as extremidades <b>A</b> e <b>B</b> da corda e a reta tangente <b>t</b> que passa por <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="284" name="sl">
			   <label for="284"></label>
			   <img src="parte3/22_02_02.png"/>
			   <figcaption>Quando unimos <b>A</b> e <b>B</b> com o centro da circunferência, temos o ângulo central correspondente <b>&beta;</b> do ângulo de segmento.</figcaption>
		   </li>
		</ul>
		<img src="parte3/22_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte3/apos_dg_0022b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4dd; Demonstração</summary>
	<p>Vamos demonstrar a Propriedade 2, que relaciona o ângulo de segmento com o ângulo central correspondente.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="285" name="sl" checked>
			   <label for="285"></label>
			   <img src="parte3/22_03_01.png"/>
			   <figcaption>Vamos considerar a reta tangente à circunferência <b>t</b> no ponto <b>A</b> e o raio com medida <b>r</b>. Logo, temos o <b>&#9651;AOB</b> isósceles de base <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="286" name="sl">
			   <label for="286"></label>
			   <img src="parte3/22_03_02.png"/>
			   <figcaption>Logo, temos os ângulos da base iguais a <b>&delta;</b>. Temos também que <b>&theta; + &delta; = 90&deg;</b>, pois a reta <b>t</b> é tangente e <b>2&delta; + &beta; = 180&deg;</b> pois são ângulos internos do <b>&#9651;AOB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="287" name="sl">
			   <label for="287"></label>
			   <img src="parte3/22_03_02.png"/>
			   <figcaption>Da relação de <b>&delta;</b> e <b>&theta;</b>, podemos concluir que <b>2&delta; + 2&theta; = 180&deg;</b>. Temos que <b>2&delta; + 2&theta; = 2&delta; + &beta;</b>, ou seja <b>2&theta; = &beta;</b>. Portanto, $\mathsf{\theta = {\beta \over 2} }$, que é a mesma relação que provamos entre o ângulo inscrito e o central correspondente. </figcaption>
		   </li>
		</ul>
		<img src="parte3/22_03_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte3" class="topo">voltar ao topo</a></p>
  <img src="parte3/apos_dg_0023.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos usar os conceitos dos ângulos de segmento e inscrito para encontrar o centro da circunferência. Utilizaremos os esquadros e o compasso neste exercício.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="288" name="sl" checked>
			   <label for="288"></label>
			   <img src="parte3/23_01_01.png"/>
			   <figcaption>Determine os vértices de um <b>&#9651;PAB</b> inscrito na circunferência.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="289" name="sl">
			   <label for="289"></label>
			   <img src="parte3/23_01_02.png"/>
			   <figcaption>Neste caso, <b>AB</b> será a corda do ângulo inscrito <b>&angsph;APB</b>. Vamos transportá-lo na extermidade <b>A</b> da corda. Com centro em <b>P</b> e um raio <b>PC</b> qualquer, determine o arco que intercepta <b>PB</b> em <b>D</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="290" name="sl" checked>
			   <label for="290"></label>
			   <img src="parte3/23_01_03.png"/>
			   <figcaption>Com centro em <b>A</b>, determine o arco com mesmo raio <b>PC</b>, encontrando <b>E &isin; AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="291" name="sl" checked>
			   <label for="291"></label>
			   <img src="parte3/23_01_04.png"/>
			   <figcaption>Com o compasso, "pegue" a medida <b>CD</b> e...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="292" name="sl">
			   <label for="292"></label>
			   <img src="parte3/23_01_05.png"/>
			   <figcaption>... com centro em <b>E</b>, determine o arco com raio <b>CD</b> para encontrar <b>F</b> na interseção com o outro arco que construímos centrado em <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="293" name="sl" checked>
			   <label for="293"></label>
			   <img src="parte3/23_01_06.png"/>
			   <figcaption>Desta forma, conseguimos construir o ângulo de segmento com mesma medida do ângulo inscrito correspondente <b>&alpha;</b>. Portanto, a reta <b>t &equiv; AF</b> é tangente à circunferência no ponto <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="294" name="sl">
			   <label for="294"></label>
			   <img src="parte3/23_01_07.png"/>
			   <figcaption>Vamos construir uma reta perpendicular a <b>t</b> passando por <b>A</b>, pois a reta tangente é perpendicular ao raio da circunferência em <b>A</b>. Alinhando um cateto do esquadro de 45 com <b>t</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="295" name="sl">
			   <label for="295"></label>
			   <img src="parte3/23_01_08.png"/>
			   <figcaption>... deixamos fixo o esquadro de 60 e deslizamos o esquadro de 45 até chegar em <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="296" name="sl" checked>
			   <label for="296"></label>
			   <img src="parte3/23_01_09.png"/>
			   <figcaption>Desta forma, temos definido o diâmetro <b>AG</b> da circunferência.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="297" name="sl" checked>
			   <label for="297"></label>
			   <img src="parte3/23_01_10.png"/>
			   <figcaption>Construindo a mediatriz de <b>AG</b>, temos o centro da circunferência <b>O</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte3/23_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte3/apos_dg_0023a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Utilizando as definições dos ângulos inscrito, central e de segmento, conseguimos deduzir os valores do ângulo <b>x</b> indicados.</p>
	<img src="parte3/23_02_00.png"/>
	<figcaption>No item <b>a</b>, o ângulo <b>x</b> é inscrito. Logo, <b>x</b> mede a metade do central correspondente, indicado por <b>90&deg;</b>. Determine as justificativas das medidas dos outros itens.</figcaption>
  </details></div>
  <img src="parte3/apos_dg_0023b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Utilizando as definições dos ângulos inscrito, central e de segmento, conseguimos deduzir os valores do ângulo <b>x</b> indicados.</p>
	<img src="parte3/23_03_00.png"/>
	<figcaption>No item <b>d</b>, o ângulo <b>x</b> é inscrito, e "enxerga" a mesma corda que o ângulo de <b>45&deg;</b> indicado. Logo, <b>x = 45&deg;</b>. Determine as justificativas das medidas dos outros itens.</figcaption>
  </details></div>
  <img src="parte3/apos_dg_0023c.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Utilizando as definições dos ângulos inscrito, central e de segmento, conseguimos deduzir os valores do ângulo <b>x</b> indicados.</p>
	<img src="parte3/23_04_00.png"/>
	<figcaption>No item <b>g</b>, o ângulo <b>x</b> é de segmento, correspondente ao ângulo central indicado de <b>120&deg;</b>. Logo, <b>x = 60&deg;</b>, metade da medida do ângulo central correspondente. Determine as justificativas das medidas dos outros itens.</figcaption>
  </details></div>
  <p class="topop"><a href="#parte3" class="topo">voltar ao topo</a></p>
  <img src="parte3/apos_dg_0024.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4dd; Propriedades</summary>
	<p>Vamos ver algumas propriedades deste lugar geométrico.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="298" name="sl" checked>
			   <label for="298"></label>
			   <img src="parte3/24_01_01.png"/>
			   <figcaption>Ao determinar um ponto <b>P</b> no arco capaz, unindo este ponto à extremidades da corda <b>AB</b>, temos sempre a mesma medida <b>&alpha;</b> do ângulo inscrito (que mede a metade da medida do ângulo central correspondente).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="299" name="sl">
			   <label for="299"></label>
			   <img src="parte3/24_01_02.png"/>
			   <figcaption>A mesma propriedade vale se escolhermos um ponto <b>Q</b> do arco simétrico em relação à corda <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="300" name="sl">
			   <label for="300"></label>
			   <img src="parte3/24_01_03.png"/>
			   <figcaption>Considere o ponto <b>Q'</b> no prolongamento de <b>BQ</b>, fora do arco capaz, que forma <b>&angsph; AQ'B = &alpha;'</b>. De acordo com o Teorema do Ângulo Externo, temos que <b>&alpha; > &alpha;'</b>, ou seja, <b>Q'</b> não possui a propriedade de "enxergar" o segmento <b>AB</b> segundo ângulo <b>&alpha;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="301" name="sl">
			   <label for="301"></label>
			   <img src="parte3/24_01_04.png"/>
			   <figcaption>Agora considere o ponto <b>Q'' &isin; BQ</b>, dentro da região formada pelo arco capaz, formando <b>&angsph; AQ''B = &alpha;''</b>. De acordo com o Teorema do Ângulo Externo, temos que <b>&alpha;'' > &alpha;</b>, ou seja, <b>Q''</b> não possui a propriedade de "enxergar" o segmento <b>AB</b> segundo ângulo <b>&alpha;</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte3/24_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte3/apos_dg_0024a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos as propriedades dos ângulos inscrito, central e de segmento para construir o arco capaz.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="302" name="sl" checked>
			   <label for="302"></label>
			   <img src="parte3/24_02_01.png"/>
			   <figcaption>Vamos transportar o ângulo <b>&alpha;</b> no segmento <b>AB</b>, com vértice <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="303" name="sl">
			   <label for="303"></label>
			   <img src="parte3/24_02_02.png"/>
			   <figcaption>Desta forma, temos o ângulo de segmento <b>&alpha;</b>, que determina a reta tangente <b>t</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="304" name="sl">
			   <label for="304"></label>
			   <img src="parte3/24_02_03.png"/>
			   <figcaption>Construa com régua e compasso ou com os esquadros a reta perpendicular a <b>t</b> que passa por <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="305" name="sl">
			   <label for="305"></label>
			   <img src="parte3/24_02_04.png"/>
			   <figcaption>Construa a mediatriz de <b>AB</b>. A interseção da <b>med<sub>AB</sub></b> com a reta perpendicular é o centro <b>O</b> de um dos arcos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="306" name="sl" checked>
			   <label for="306"></label>
			   <img src="parte3/24_02_05.png"/>
			   <figcaption>Com o centro em <b>O</b> e raio <b>OA = OB</b>, construa o arco capaz de <b>&alpha;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="307" name="sl">
			   <label for="307"></label>
			   <img src="parte3/24_02_06.png"/>
			   <figcaption>O arco simétrico pode ser construído com centro em <b>A</b> ou <b>B</b>, e raio <b>OA</b>. Temos que <b>O' &isin; med<sub>AB</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="308" name="sl">
			   <label for="308"></label>
			   <img src="parte3/24_02_07.png"/>
			   <figcaption>Com centro em <b>O'</b> e raio <b>O'A = O'B</b>, construa o arco simétrico.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="309" name="sl">
			   <label for="309"></label>
			   <img src="parte3/24_02_08.png"/>
			   <figcaption>Esta é a construção do arco capaz de um ângulo <b>&alpha;</b> segundo segmento <b>AB</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte3/24_02_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte3" class="topo">voltar ao topo</a></p>
  <img src="parte3/apos_dg_0025.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Neste exercício, vamos construir os arcos capazes dos ângulos conhecendo os valores de suas medidas.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="310" name="sl" checked>
			   <label for="310"></label>
			   <img src="parte3/25_01_01.png"/>
			   <figcaption>Vamos começar construindo o ângulo de segmento de <b>60&deg;</b> com vértice em <b>A</b>. Com centro em <b>A</b>, construa um arco que intercepte <b>AB</b> em <b>C</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="311" name="sl">
			   <label for="311"></label>
			   <img src="parte3/25_01_02.png"/>
			   <figcaption>Com a mesma medida de raio, construa o arco com centro em <b>C</b>, encontrando o ponto <b>D</b> no arco que construimos no passo anterior. Assim, temos a reta tangente ao arco: <b>t</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="312" name="sl">
			   <label for="312"></label>
			   <img src="parte3/25_01_03.png"/>
			   <figcaption>Com os esquadros ou a régua e o compasso, construa a reta perpendicular a <b>t</b> que passa por <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="313" name="sl">
			   <label for="313"></label>
			   <img src="parte3/25_01_04.png"/>
			   <figcaption>O centro do arco capaz de <b>60&deg;</b> está na interseção da reta peropendicular a <b>t</b> com a mediatriz de <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="314" name="sl" checked>
			   <label for="314"></label>
			   <img src="parte3/25_01_05.png"/>
			   <figcaption>Com centro em <b>O</b> e raio <b>OA = OB</b>, construa o arco capaz de <b>60&deg;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="315" name="sl">
			   <label for="315"></label>
			   <img src="parte3/25_01_06.png"/>
			   <figcaption>Com centro em <b>A</b> ou <b>B</b>, construa o arco com raio <b>OA</b>. A interseção deste arco com a <b>med<sub>AB</sub></b> é o centro do arco simétrico.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="316" name="sl">
			   <label for="316"></label>
			   <img src="parte3/25_01_07.png"/>
			   <figcaption>Pronto! Temos os 2 arcos que definem o arco capaz de <b>60&deg;</b> segundo o segmento <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="317" name="sl">
			   <label for="317"></label>
			   <img src="parte3/25_01_08.png"/>
			   <figcaption>Para construir o arco capaz de <b>120&deg;</b>, podemos construir o suplementar de <b>60&deg;</b> no prolongamento de <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="318" name="sl" checked>
			   <label for="318"></label>
			   <img src="parte3/25_01_09.png"/>
			   <figcaption>Logo, temos que o <b>&angsph;FAB = 120&deg;</b>. Podemos construir a reta perpendicular a <b>t</b> que passa por <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="319" name="sl">
			   <label for="319"></label>
			   <img src="parte3/25_01_10.png"/>
			   <figcaption>O encontro da mediatriz de <b>AB</b> com a reta perpendicular que construímos é o centro do arco capaz.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="320" name="sl">
			   <label for="320"></label>
			   <img src="parte3/25_01_11.png"/>
			   <figcaption>Com o centro em <b>O</b> e raio <b>OA = OB</b>, construa o primeiro arco.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="321" name="sl">
			   <label for="321"></label>
			   <img src="parte3/25_01_12.png"/>
			   <figcaption>Construindo o arco com centro em <b>A</b> e raio <b>OA = OB</b>, econtramos o centro <b>O'</b> do segundo arco. Note que <b>O'</b> pertence ao arco capaz que acabamos de construir.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="322" name="sl">
			   <label for="322"></label>
			   <img src="parte3/25_01_13.png"/>
			   <figcaption>Com centro em <b>O'</b>, construimos o arco simétrico do primeiro. Os centros pertencem aos arcos simétricos, pois <b>&angsph;AOB =  &angsph;AO'B = 120&deg;</b>, que é a medida do ângulo inscrito que define este arco capaz.</figcaption>
		   </li>
		</ul>
		<img src="parte3/25_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte3/apos_dg_0025a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>De forma genérica, vamos encontrar a relação existente entre os ângulos opostos <b>&alpha;</b> e <b>&beta;</b> que formam um quadrilátro inscrito em uma circunferência.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="323" name="sl" checked>
			   <label for="323"></label>
			   <img src="parte3/25_02_01.png"/>
			   <figcaption>Considerando o ângulo inscrito <b>&alpha;</b>, o central correspondente será o ângulo <b>&delta;</b>. Sabemos que $\mathsf{\alpha = {\delta \over 2} }$.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="324" name="sl">
			   <label for="324"></label>
			   <img src="parte3/25_02_02.png"/>
			   <figcaption>O ângulo central correspondente de <b>&beta;</b> é o ângulo <b>&theta;</b>. Temos a relação $\mathsf{\beta = {\theta \over 2} }$. Como <b>&delta; + &theta; = 360&deg;</b>, temos que $\mathsf{\alpha + \beta = {\delta \over 2} + {\theta \over 2} = { {\delta + \theta} \over 2} = 180^o }$. Logo, <b>&alpha;</b> e <b>&beta;</b> são suplementares.</figcaption>
		   </li>
		</ul>
		<img src="parte3/25_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte3/apos_dg_0025b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos encontrar a medida de um ângulo insrito em uma semi-circunferência. Note que o ângulo central correspondente vale 180&deg;</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="325" name="sl" checked>
			   <label for="325"></label>
			   <img src="parte3/25_03_01.png"/>
			   <figcaption>Como o ângulo central <b>&theta;</b> mede <b>180&deg;</b>, o ângulo inscrito correspondente vale a metade, ou seja, <b>&gamma; = 90&deg;</b>. Logo, a construção de um arco capaz de <b>90&deg;</b> é mais simples: o centro será o ponto médio do segmento.</figcaption>
		   </li>
		</ul>
		<img src="parte3/25_03_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte3" class="topo">voltar ao topo</a></p>
  <img src="parte3/apos_dg_0026.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos o conceito da construção de um arco capaz de <b>90&deg;</b> para resolver este exercício.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="326" name="sl" checked>
			   <label for="326"></label>
			   <img src="parte3/26_01_01.png"/>
			   <figcaption>Escolha um ponto <b>O &notin; r</b>, que não esteja próximo da região onde construiremos a reta perpendicular à reta <b>r</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="327" name="sl">
			   <label for="327"></label>
			   <img src="parte3/26_01_02.png"/>
			   <figcaption>Com centro em <b>O</b>, construa a circunferência com raio <b>OP</b>, encontrando o ponto <b>Q &equiv; r &cap; Circunf(O,OP)</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="328" name="sl">
			   <label for="328"></label>
			   <img src="parte3/26_01_03.png"/>
			   <figcaption>Construa o diâmetro <b>QR</b>. Como uma semi-circunferência é o arco capaz de <b>90&deg;</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="329" name="sl">
			   <label for="329"></label>
			   <img src="parte3/26_01_04.png"/>
			   <figcaption>... então a reta <b>PR</b> formará <b>90&deg;</b> com a reta <b>r</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte3/26_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte3/apos_dg_0026a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos o conceito da construção de um arco capaz de <b>90&deg;</b> para resolver este exercício. O ponto de tangência "enxerga" o segmento <b>OP</b> segundo <b>90&deg;</b>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="330" name="sl" checked>
			   <label for="330"></label>
			   <img src="parte3/26_02_01.png"/>
			   <figcaption>Vamos construir o arco capaz de <b>90&deg;</b> segundo segmento <b>OP</b>. Construa a mediatriz de <b>PO</b>, encontrando o ponto <b>M</b> médio deste segmento.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="331" name="sl">
			   <label for="331"></label>
			   <img src="parte3/26_02_02.png"/>
			   <figcaption>Com centro em <b>M</b>, construa o par de arcos capazes de <b>90&deg;</b> com raio <b>MP = MO</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="332" name="sl">
			   <label for="332"></label>
			   <img src="parte3/26_02_03.png"/>
			   <figcaption>As interseções destes arcos capazes com a circunferência <b>&lambda;</b> definem os pontos de tangência <b>T</b> e <b>T'</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="333" name="sl">
			   <label for="333"></label>
			   <img src="parte3/26_02_04.png"/>
			   <figcaption>As retas <b>t &equiv; PT</b> e <b>t' &equiv; PT'</b> são as retas tangentes à circunferência <b>&lambda;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="334" name="sl">
			   <label for="334"></label>
			   <img src="parte3/26_02_05.png"/>
			   <figcaption>Se unirmos os pontos de tangência com o centro <b>O</b>, podemos verificar que <b>&angsph;PTO = &angsph;PT'O = 90&deg;</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte3/26_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte3/apos_dg_0026b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos o conceito entre o ângulo central de <b>90&deg;</b>, e o inscrito correspondente que mede <b>45&deg;</b>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="335" name="sl" checked>
			   <label for="335"></label>
			   <img src="parte3/26_03_01.png"/>
			   <figcaption>Como o ponto <b>B</b> "enxerga" o segmento <b>AC</b> segundo <b>45&deg;</b>, vamos usar o arco capaz para resolver este exercício. Podemos construir o arco capaz de <b>45&deg;</b> de uma forma mais simples: primeiro construimos o arco capaz de <b>90&deg;</b>, cujo centro é o ponto médio de <b>AC</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="336" name="sl">
			   <label for="336"></label>
			   <img src="parte3/26_03_02.png"/>
			   <figcaption>Com centro em <b>M</b>, construa o arco capaz de <b>90&deg;</b> com raio <b>MA = MC</b>. Não precisamos construir o arco da esquerda, pois não será usado no desenho da peça.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="337" name="sl">
			   <label for="337"></label>
			   <img src="parte3/26_03_03.png"/>
			   <figcaption>A interseção da mediatriz de <b>AC</b> com o arco capaz de <b>90&deg;</b> é o centro do arco capaz de <b>45&deg;</b>, pois o ângulo inscrito mede a metade do central correspondente.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="338" name="sl">
			   <label for="338"></label>
			   <img src="parte3/26_03_04.png"/>
			   <figcaption>O ponto <b>B</b> pode ser encontrado na interseção da <b>Circunf(A,AB)</b> com o arco capaz de <b>45&deg;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="339" name="sl">
			   <label for="339"></label>
			   <img src="parte3/26_03_05.png"/>
			   <figcaption>Para finalizar, construímos as retas perpendiculares a <b>AB</b> que passam por <b>A</b> e <b>B</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte3/26_03_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte3" class="topo">voltar ao topo</a></p>
  <img src="parte3/apos_dg_0027.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Exercício simples, de aplicação dos conceitos que envolvem arco capaz.</p>
	<img src="parte3/27_01_00.png"/>
	<figcaption></figcaption>
  </details></div>
  <img src="parte3/apos_dg_0027a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Construindo os arcos capazes de <b>30&deg;</b> e de <b>45&deg;</b>, encontramos os arcos capazes dos ângulos suplementares.</p>
	<img src="parte3/27_02_00.png"/>
	<figcaption>O mesmo vale se você construir os arcos capazes de <b>150&deg;</b> e de <b>135&deg;</b>.</figcaption>
  </details></div>
  <p class="topop"><a href="#parte3" class="topo">voltar ao topo</a></p>
  <img src="parte3/apos_dg_0028.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>O vértice <b>C</b>, oposto de <b>AB</b>, enxerga o segmento segundo ângulo de <b>60&deg;</b>.</p>
	<img src="parte3/28_01_00.png"/>
	<figcaption>A construção envolve o arco capaz de <b>60&deg;</b>.</figcaption>
  </details></div>
  <img src="parte3/apos_dg_0028a.png"/>
  <div class="combo">&#x1f4cf; &#x1f4d0; <span class="atv">Atividade 1</span></div>
  <img src="parte3/apos_dg_0028b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>O vértice <b>C</b>, oposto de <b>AB</b>, enxerga o segmento segundo ângulo de <b>60&deg;</b>.</p>
	<img src="parte3/28_03_00.png"/>
	<figcaption>A construção envolve o arco capaz de <b>60&deg;</b>.</figcaption>
  </details></div>
  <p class="topop"><a href="#parte3" class="topo">voltar ao topo</a></p>
  <img src="parte3/apos_dg_0029.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Como o ponto <b>X</b> é equidistante de <b>P</b> e <b>Q</b>, pertence à <b>med<sub>PQ</sub></b>.</p>
	<img src="parte3/29_01_00.png"/>
	<figcaption>A construção envolve o arco capaz de <b>30&deg;</b>.</figcaption>
  </details></div>
  <img src="parte3/apos_dg_0029a.png"/>
  <div class="combo">&#x1f4cf; &#x1f4d0; <span class="atv">Atividade 2</span></div>
  <p class="topop"><a href="#parte3" class="topo">voltar ao topo</a></p>
</details>

<details>
  <summary id="parte4">2.2. Operações com segmentos</summary>
  <p>Material da página 30 até a página 48.</p>
  <img src="parte4/apos_dg_0030.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4dd; Propriedades</summary>
	<p>Vamos verificar as propriedades do Teorema de Tales.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="340" name="sl" checked>
			   <label for="340"></label>
			   <img src="parte4/30_01_01.png"/>
			   <figcaption>Considere as retas paralelas <b>a</b>, <b>b</b> e <b>c</b> que interceptam a reta <b>r</b> nos pontos <b>A</b>, <b>B</b> e <b>C</b>, respectivamente. </figcaption>
		   </li>
		   <li>
			   <input type="radio" id="341" name="sl">
			   <label for="341"></label>
			   <img src="parte4/30_01_02.png"/>
			   <figcaption>Considere a reta <b>s</b>, que intercepta o feixe de paralelas <b>a</b>, <b>b</b> e <b>c</b> nos pontos <b>A'</b>, <b>B'</b> e <b>C'</b>, respectivamente.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="342" name="sl">
			   <label for="342"></label>
			   <img src="parte4/30_01_03.png"/>
			   <figcaption>A razão entre os segmentos <b>AB</b> e <b>BC</b> da reta <b>r</b> e a razão entre os segmentos correspondentes <b>A'B'</b> e <b>B'C'</b> da reta <b>s</b> têm mesmo valor: $\mathsf{ {AB \over BC} = {A'B' \over B'C'} }$.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="343" name="sl">
			   <label for="343"></label>
			   <img src="parte4/30_01_04.png"/>
			   <figcaption>Utilizando a correspondência de outra maneira, temos a relação entre as razões entre os segmentos <b>AB</b> e <b>AC</b> e seus correspondentes: $\mathsf{ {AB \over AC} = {A'B' \over A'C'} }$.</figcaption>
		   </li>
		</ul>
		<img src="parte4/30_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0030a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos a régua, o compasso e os esquadros para resolver este exercício.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="344" name="sl" checked>
			   <label for="344"></label>
			   <img src="parte4/30_02_01.png"/>
			   <figcaption>Podemos construir o segmento <b>AB</b> com a medida de 11cm diretamente com a régua. Na extremidade <b>A</b>, podemos construir uma reta com inclinação qualquer. A reta suporte de <b>AB</b> e a reta qualquer formam o feixe de retas concorrentes.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="345" name="sl">
			   <label for="345"></label>
			   <img src="parte4/30_02_02.png"/>
			   <figcaption>Podemos construir um segmento com medida qualquer <b>A1</b> com o compasso, e repetí-la consecutivamente...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="346" name="sl">
			   <label for="346"></label>
			   <img src="parte4/30_02_03.png"/>
			   <figcaption>... encontrando os segmentos com mesma medida: <b>12 = 23 = ... = 67 = A1</b>. Outra maneira de encontrar estes pontos é marcando diretamente com a régua uma medida qualquer (por exemplo, 1cm) e repetindo-a até chegar na 7&ordf; unidade.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="347" name="sl">
			   <label for="347"></label>
			   <img src="parte4/30_02_04.png"/>
			   <figcaption>Unindo as extremidades <b>B</b> e <b>7</b>, podemos alinhar um dos esquadros para definir o feixe das 6 retas que dividem <b>AB</b> em 7 partes iguais.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="348" name="sl" checked>
			   <label for="348"></label>
			   <img src="parte4/30_02_05.png"/>
			   <figcaption>Deslizamos o esquadro no ponto <b>6</b> paralelamente ao segmento <b>B7</b>, depois no ponto <b>5</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="349" name="sl">
			   <label for="349"></label>
			   <img src="parte4/30_02_06.png"/>
			   <figcaption>... até chegarmos no ponto <b>1</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="350" name="sl">
			   <label for="350"></label>
			   <img src="parte4/30_02_07.png"/>
			   <figcaption>Logo, temos os segmentos <b>AA<sub>1</sub> = A<sub>1</sub>A<sub>2</sub> = ... = A<sub>6</sub>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="351" name="sl">
			   <label for="351"></label>
			   <img src="parte4/30_02_08.png"/>
			   <figcaption>De acordo com o Teorema de Tales, temos que $\mathsf{ {AA_1 \over A1} = {AB \over A7} }$.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="352" name="sl">
			   <label for="352"></label>
			   <img src="parte4/30_02_09.png"/>
			   <figcaption>Ou seja, temos que $\mathsf{ {A1 \over A7} = {1 \over 7} = {AA_1 \over AB}}$.</figcaption>
		   </li>
		</ul>
		<img src="parte4/30_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0030b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos a régua, o compasso e os esquadros para resolver este exercício.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="353" name="sl" checked>
			   <label for="353"></label>
			   <img src="parte4/30_03_01.png"/>
			   <figcaption>Podemos construir o segmento <b>AB</b> com a medida de 12cm diretamente com a régua. Na extremidade <b>A</b>, podemos construir uma reta com inclinação qualquer. A reta suporte de <b>AB</b> e a reta qualquer formam o feixe de retas concorrentes. </figcaption>
		   </li>
		   <li>
			   <input type="radio" id="354" name="sl">
			   <label for="354"></label>
			   <img src="parte4/30_03_02.png"/>
			   <figcaption>Com o compasso, "pegue" a medida do segmento <b>m</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="355" name="sl">
			   <label for="355"></label>
			   <img src="parte4/30_03_03.png"/>
			   <figcaption>... e marque esta medida a partir do ponto <b>A</b> na reta qualquer, encontrando o ponto <b>M</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="356" name="sl">
			   <label for="356"></label>
			   <img src="parte4/30_03_04.png"/>
			   <figcaption>Faça o mesmo com o segmento <b>n</b>, marcando esta medida a partir da extremidade de <b>m</b>, ou seja, <b>MN = n</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="357" name="sl" checked>
			   <label for="357"></label>
			   <img src="parte4/30_03_05.png"/>
			   <figcaption>Na sequência, marque a medida do último segmento, <b>p</b>, obtendo-se <b>NP = p</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="358" name="sl">
			   <label for="358"></label>
			   <img src="parte4/30_03_06.png"/>
			   <figcaption>Agora podemos unir a extremidade <b>P</b> com <b>B</b> e construir as paralelas a <b>BP</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="359" name="sl">
			   <label for="359"></label>
			   <img src="parte4/30_03_07.png"/>
			   <figcaption>... deslizando um esquadro até o ponto <b>N</b>, obtendo-se <b>N' &isin; AB</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="360" name="sl">
			   <label for="360"></label>
			   <img src="parte4/30_03_08.png"/>
			   <figcaption>... e até o ponto <b>M</b>, definindo <b>M' &isin; AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="361" name="sl">
			   <label for="361"></label>
			   <img src="parte4/30_03_09.png"/>
			   <figcaption>De acordo com o Teorema de Tales, os segmentos <b>m'</b>, <b>n'</b> e <b>p'</b> são proporcionais aos segmentos <b>m</b>, <b>n</b> e <b>p</b>, respectivamente.</figcaption>
		   </li>
		</ul>
		<img src="parte4/30_03_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0031.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos a régua e os esquadros para resolver este exercício.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="362" name="sl" checked>
			   <label for="362"></label>
			   <img src="parte4/31_01_01.png"/>
			   <figcaption>Podemos construir o segmento <b>AB</b> com a medida de 13cm diretamente com a régua. Na extremidade <b>A</b>, podemos construir uma reta com inclinação qualquer. A reta suporte de <b>AB</b> e a reta qualquer formam o feixe de retas concorrentes.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="363" name="sl">
			   <label for="363"></label>
			   <img src="parte4/31_01_02.png"/>
			   <figcaption>Podemos construir o segmento <b>m</b> com o compasso, ou diretamente com a régua, marcando <b>m = 2cm</b> a partir de <b>A</b> na reta qualquer.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="364" name="sl">
			   <label for="364"></label>
			   <img src="parte4/31_01_03.png"/>
			   <figcaption>Na sequência, a partir de <b>C</b> marcamos <b>n = 4,2cm</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="365" name="sl">
			   <label for="365"></label>
			   <img src="parte4/31_01_04.png"/>
			   <figcaption>E a partir de <b>D</b>, marcamos <b>p = 5,3cm</b>. Conseguimos marcar com a régua, pois sabemos as medidas. No exercício anterior, só tínhamos os segmentos. Se medíssemos estes segmentos com a régua, poderíamos cometer erros de arredondamento.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="366" name="sl" checked>
			   <label for="366"></label>
			   <img src="parte4/31_01_05.png"/>
			   <figcaption>Agora basta construir as retas paralelas a <b>EB</b> com os esquadros...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="367" name="sl">
			   <label for="367"></label>
			   <img src="parte4/31_01_06.png"/>
			   <figcaption>... obtendo-se os pontos <b>D' &isin; AB</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="368" name="sl">
			   <label for="368"></label>
			   <img src="parte4/31_01_07.png"/>
			   <figcaption>... e <b>C' &isin; AB</b>. De acordo com o Teorema de Tales, o segmento <b>AB</b> está dividido em partes proporcionais aos números <b>m</b>, <b>n</b> e <b>p</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte4/31_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0031a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos a régua, o compasso e os esquadros para resolver este exercício.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="369" name="sl" checked>
			   <label for="369"></label>
			   <img src="parte4/31_02_01.png"/>
			   <figcaption>Podemos construir o segmento <b>AB</b> com a medida de 15cm diretamente com a régua. Na extremidade <b>A</b>, podemos construir uma reta com inclinação qualquer. Vamos dividir o perímetro em partes proporcionais aos segmentos <b>q</b>, <b>r</b> e <b>s</b>, encontrando os lados <b>a</b>, <b>b</b> e <b>c</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="370" name="sl">
			   <label for="370"></label>
			   <img src="parte4/31_02_02.png"/>
			   <figcaption>Podemos marcar com a régua, na reta qualquer e partir de <b>A</b> o segmento <b>q = 5cm</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="371" name="sl">
			   <label for="371"></label>
			   <img src="parte4/31_02_03.png"/>
			   <figcaption>Na sequência, marcamos <b>r = 3,5cm</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="372" name="sl">
			   <label for="372"></label>
			   <img src="parte4/31_02_04.png"/>
			   <figcaption>... e <b>s = 4cm</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="373" name="sl" checked>
			   <label for="373"></label>
			   <img src="parte4/31_02_05.png"/>
			   <figcaption>Agora podemos construir as retas paralelas ao segmento que une a extremidade de <b>s</b> com <b>Q</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="374" name="sl">
			   <label for="374"></label>
			   <img src="parte4/31_02_06.png"/>
			   <figcaption>Deslizamos um dos esquadros até chegar na extremidade de <b>r</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="375" name="sl">
			   <label for="375"></label>
			   <img src="parte4/31_02_07.png"/>
			   <figcaption>... e depois na extremidade de <b>q</b>. Desta forma, temos os lados <b>a</b>, <b>b</b> e <b>c</b> sobre o perímetro que marcamos <b>PQ = 15cm</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="376" name="sl">
			   <label for="376"></label>
			   <img src="parte4/31_02_08.png"/>
			   <figcaption>Podemos manter um dos lados e usar circunferências para encontrar o terceiro vértice do triângulo. Se mantivermos o lado <b>b = AC</b>, temos as relações dos segmentos: <b>AQ = c = AB</b> e <b>PC = a = BC</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="377" name="sl">
			   <label for="377"></label>
			   <img src="parte4/31_02_09.png"/>
			   <figcaption>Construindo a Circunf(C,a), temos o primeiro lugar geométrico do ponto <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="378" name="sl">
			   <label for="378"></label>
			   <img src="parte4/31_02_10.png"/>
			   <figcaption>O segundo lugar geométrico de <b>B</b> é a Circunf(A,c).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="379" name="sl">
			   <label for="379"></label>
			   <img src="parte4/31_02_11.png"/>
			   <figcaption>Logo, temos as duas soluções deste exercício: <b>&#9651;ABC</b> e <b>&#9651;AB'C</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte4/31_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0031b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Utilizaremos a régua, o compasso e os esquadros para resolver este exercício.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="380" name="sl" checked>
			   <label for="380"></label>
			   <img src="parte4/31_03_01.png"/>
			   <figcaption>Vamos construir a divisão dos segmentos de uma só vez. Para funcionar esta "tática", construa uma reta qualquer, e determine um ponto  <b>A</b> que tenha a distância até a reta um pouco menor do que o menor dos segmentos que queremos dividir: ou seja, a distância de <b>A</b> até a reta será um pouco menor do que 3cm.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="381" name="sl">
			   <label for="381"></label>
			   <img src="parte4/31_03_02.png"/>
			   <figcaption>Agora construa a reta paralela à reta qualquer que construímos que passa por <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="382" name="sl">
			   <label for="382"></label>
			   <img src="parte4/31_03_03.png"/>
			   <figcaption>Logo, temos 2 retas paralelas com distância menor do que 3cm.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="383" name="sl">
			   <label for="383"></label>
			   <img src="parte4/31_03_04.png"/>
			   <figcaption>Agora "pegue" a medida 3cm na régua, usando o compasso...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="384" name="sl" checked>
			   <label for="384"></label>
			   <img src="parte4/31_03_05.png"/>
			   <figcaption>... e construa a Circunf(A,a), encontrando o ponto <b>B</b> na primeira reta construída.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="385" name="sl">
			   <label for="385"></label>
			   <img src="parte4/31_03_06.png"/>
			   <figcaption>Podemos dividir este segmento <b>AB = a</b> usando como reta suporte uma das retas paralelas. Marque 5 unidades a partir de <b>A</b> ou de <b>B</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="386" name="sl">
			   <label for="386"></label>
			   <img src="parte4/31_03_07.png"/>
			   <figcaption>... e construa as retas paralelas a <b>A5</b> ou <b>B5</b>, dividindo <b>AB</b> em 5 partes iguais.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="387" name="sl">
			   <label for="387"></label>
			   <img src="parte4/31_03_08.png"/>
			   <figcaption>Em cada ponto da divisão de <b>AB</b>, construa as retas paralelas às retas iniciais que construímos. Elas funcionam como um feixe para dividirmos os outros segmentos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="388" name="sl">
			   <label for="388"></label>
			   <img src="parte4/31_03_09.png"/>
			   <figcaption>Agora basta escolher um ponto <b>C</b> em uma das retas paralelas iniciais que construímos, e construir a Circunf(C,b). Na outra paralela, temos o ponto <b>D</b> e o segmento já aparece dividido em 5 partes iguais.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="389" name="sl">
			   <label for="389"></label>
			   <img src="parte4/31_03_10.png"/>
			   <figcaption>Fazemos o mesmo com o ponto <b>E</b>, construindo a Circunf(E,c).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="390" name="sl">
			   <label for="390"></label>
			   <img src="parte4/31_03_11.png"/>
			   <figcaption>Fazemos o mesmo para dividir o segmento <b>d</b>, construindo a Circunf(G,d).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="391" name="sl">
			   <label for="391"></label>
			   <img src="parte4/31_03_12.png"/>
			   <figcaption>Fazemos o mesmo com o ponto <b>I</b>, construindo a Circunf(I,e).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="392" name="sl">
			   <label for="392"></label>
			   <img src="parte4/31_03_13.png"/>
			   <figcaption>E finalmente temos a Circunf(K,f), que divide o segmento <b>f</b>em 5 partes iguais. Esta construção é bem menos trabalhosa do que fazer a divisão separada de cada segmento em 5 partes iguais.</figcaption>
		   </li>
		</ul>
		<img src="parte4/31_03_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0031c.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Neste exercício proposto, temos a aplicação do Teorema de Tales para encontrar os lados do triângulo.</p>
	<img src="parte4/31_04_00.png"/>
	<figcaption>Temos 2 soluções possíveis.</figcaption>
  </details></div>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0032.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Neste exercício proposto, podemos aplicar do Teorema de Tales para encontrar o segmento <b>x</b>.</p>
	<img src="parte4/32_01_00.png"/>
	<figcaption></figcaption>
  </details></div>
  <img src="parte4/apos_dg_0032a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4dd; Propriedade</summary>
	<p>Vamos ver o conceito e as propriedades da Divisão Harmônica.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="393" name="sl" checked>
			   <label for="393"></label>
			   <img src="parte4/32_02_01.png"/>
			   <figcaption>Considere o segmento <b>AB</b>. Vamos encontrar o 3&ordm; e o 4&ordm; harmônicos, ou simplesmente os conjugados harmônicos de <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="394" name="sl">
			   <label for="394"></label>
			   <img src="parte4/32_02_02.png"/>
			   <figcaption>O ponto interno <b>M</b>, tal que $\mathsf{ {AM \over BM} = -{p \over q} }$ é chamado de 3&ordm; conjugado harmônico. O sinal negativo apenas indica a direção oposta, considerando que os segmentos começam pelas extremidades de <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="395" name="sl">
			   <label for="395"></label>
			   <img src="parte4/32_02_03.png"/>
			   <figcaption>O ponto externo <b>N</b>, tal que $\mathsf{ {AN \over BN} = +{p \over q} }$ é chamado de 4&ordm; conjugado harmônico. O sinal positivo apenas indica a mesma direção, considerando que os segmentos começam pelas extremidades de <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="396" name="sl">
			   <label for="396"></label>
			   <img src="parte4/32_02_04.png"/>
			   <figcaption>Desta forma, temos os pontos <b>M</b> e <b>N</b> dividem harmonicamente o segmento <b>AB</b>. Vamos ver a seguir como é a construção da Divisão Harmônica de um segmento.</figcaption>
		   </li>
		</ul>
		<img src="parte4/32_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0032b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos utilizar a régua e os esquadros para fazer esta construção.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="397" name="sl" checked>
			   <label for="397"></label>
			   <img src="parte4/32_03_01.png"/>
			   <figcaption>Construa o segmento <b>AB</b> = 7cm.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="398" name="sl">
			   <label for="398"></label>
			   <img src="parte4/32_03_02.png"/>
			   <figcaption>Com a extremidade em <b>A</b>, construa uma reta com inclinação qualquer e marque com a régua <b>A7</b> = 7cm, correspondente ao numerador da razão <b>k</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="399" name="sl">
			   <label for="399"></label>
			   <img src="parte4/32_03_03.png"/>
			   <figcaption>Usando os esquadros, construa a reta paralela a <b>A7</b> que passa por <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="400" name="sl">
			   <label for="400"></label>
			   <img src="parte4/32_03_04.png"/>
			   <figcaption>Construa os segmentos <b>B2</b> e <b>B2'</b> com medidas iguais a 2cm, correspondente ao denominador da razão <b>k</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="401" name="sl">
			   <label for="401"></label>
			   <img src="parte4/32_03_05.png"/>
			   <figcaption>Unindo os pontos <b>2</b> e <b>7</b>, encontramos o 3&ordm; conjugado harmônico de <b>AB</b> na razão <b>k</b>. Temos que $\mathsf{ {AM \over BM} = -{7 \over 2} }$ por causa da semelhança dos triângulos <b>&#9651;AM7</b> e <b>&#9651;BM2</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="402" name="sl">
			   <label for="402"></label>
			   <img src="parte4/32_03_06.png"/>
			   <figcaption>Unindo os pontos <b>2'</b> e <b>7</b>, encontramos o 4&ordm; conjugado harmônico de <b>AB</b> na razão <b>k</b>. Temos que $\mathsf{ {AN \over BN} = +{7 \over 2} }$ por causa da semelhança dos triângulos <b>&#9651;AN7</b> e <b>&#9651;BN2'</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte4/32_03_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0032c.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos utilizar a régua e os esquadros para fazer esta construção.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="403" name="sl" checked>
			   <label for="403"></label>
			   <img src="parte4/32_04_01.png"/>
			   <figcaption>Construa o segmento <b>AB</b> = 7cm.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="404" name="sl">
			   <label for="404"></label>
			   <img src="parte4/32_04_02.png"/>
			   <figcaption>Com a extremidade em <b>A</b>, construa uma reta com inclinação qualquer e marque com a régua <b>A2</b> = 2cm, correspondente ao numerador da razão <b>k</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="405" name="sl">
			   <label for="405"></label>
			   <img src="parte4/32_04_03.png"/>
			   <figcaption>Usando os esquadros, construa a reta paralela a <b>A2</b> que passa por <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="406" name="sl">
			   <label for="406"></label>
			   <img src="parte4/32_04_04.png"/>
			   <figcaption>Construa os segmentos <b>B5</b> e <b>B5'</b> com medidas iguais a 5cm, correspondente ao denominador da razão <b>k</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="407" name="sl">
			   <label for="407"></label>
			   <img src="parte4/32_04_05.png"/>
			   <figcaption>Unindo os pontos <b>2</b> e <b>5</b>, encontramos o 3&ordm; conjugado harmônico de <b>AB</b> na razão <b>k</b>. Temos que $\mathsf{ {AM \over BM} = -{2 \over 5} }$ por causa da semelhança dos triângulos <b>&#9651;AM2</b> e <b>&#9651;BM5</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="408" name="sl">
			   <label for="408"></label>
			   <img src="parte4/32_04_06.png"/>
			   <figcaption>Unindo os pontos <b>2</b> e <b>5'</b>, encontramos o 4&ordm; conjugado harmônico de <b>AB</b> na razão <b>k</b>. Temos que $\mathsf{ {AN \over BN} = +{2 \over 5} }$ por causa da semelhança dos triângulos <b>&#9651;AN2</b> e <b>&#9651;BN5'</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte4/32_04_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0033.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos utilizar a régua e os esquadros para fazer esta construção. </p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="409" name="sl" checked>
			   <label for="409"></label>
			   <img src="parte4/33_01_01.png"/>
			   <figcaption>Construa o segmento <b>AB</b> = 7cm. Como os números 3 e 5 são "próximos", o ponto externo da razão harmônica ficará mais distante de <b>AB</b>. Por isso, construa o segmento <b>AB</b> próximo da margem esquerda ou direita da folha.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="410" name="sl">
			   <label for="410"></label>
			   <img src="parte4/33_01_02.png"/>
			   <figcaption>Com a extremidade em <b>A</b>, construa uma reta com inclinação qualquer e marque com a régua <b>A3</b> = <b>A3'</b> = 3cm, correspondentes ao numerador da razão <b>k</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="411" name="sl">
			   <label for="411"></label>
			   <img src="parte4/33_01_03.png"/>
			   <figcaption>Usando os esquadros, construa a reta paralela a <b>A3</b> que passa por <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="412" name="sl">
			   <label for="412"></label>
			   <img src="parte4/33_01_04.png"/>
			   <figcaption>Construa o segmento <b>B5</b> com medida igual a 5cm, correspondente ao denominador da razão <b>k</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="413" name="sl">
			   <label for="413"></label>
			   <img src="parte4/33_01_05.png"/>
			   <figcaption>Unindo os pontos <b>3</b> e <b>5</b>, encontramos o 3&ordm; conjugado harmônico de <b>AB</b> na razão <b>k</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="414" name="sl">
			   <label for="414"></label>
			   <img src="parte4/33_01_06.png"/>
			   <figcaption>Unindo os pontos <b>3'</b> e <b>5</b>, encontramos o 4&ordm; conjugado harmônico de <b>AB</b> na razão <b>k</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte4/33_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0033a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos utilizar o compasso e os esquadros para fazer esta construção. </p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="415" name="sl" checked>
			   <label for="415"></label>
			   <img src="parte4/33_02_01.png"/>
			   <figcaption>Construa o segmento <b>AP</b> com medida <b>p</b> qualquer, com inclinação também qualquer. Vamos encontrar o segmento correspondente <b>q</b> que "gerou" o 3&ordm; harmônico <b>M</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="416" name="sl">
			   <label for="416"></label>
			   <img src="parte4/33_02_02.png"/>
			   <figcaption>Construa com os esquadros a reta paralela a <b>AP</b> que passa por <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="417" name="sl">
			   <label for="417"></label>
			   <img src="parte4/33_02_03.png"/>
			   <figcaption>Se unirmos <b>P</b> e <b>M</b>, encontramos o ponto <b>Q</b> na reta paralela que construímos. Este é o segmento correspondente <b>q</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="418" name="sl">
			   <label for="418"></label>
			   <img src="parte4/33_02_04.png"/>
			   <figcaption>Usando o compasso, "pegue" a medida <b>BQ</b>...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="419" name="sl">
			   <label for="419"></label>
			   <img src="parte4/33_02_05.png"/>
			   <figcaption>E construa o segmento <b>BR = BQ</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="420" name="sl">
			   <label for="420"></label>
			   <img src="parte4/33_02_06.png"/>
			   <figcaption>Unindo os pontos <b>P</b> e <b>R</b>, encontramos o 4&ordm; conjugado harmônico de <b>AB</b> na razão $\mathsf{ k = +{AP \over BQ} }$.</figcaption>
		   </li>
		</ul>
		<img src="parte4/33_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0033b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4dd; Propriedade</summary>
	<p>Vamos ver qual é a propriedade deste lugar geométrico. Neste exemplo, a razão considerada é  $\mathsf{ k = {5 \over 3} }$</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="421" name="sl" checked>
			   <label for="421"></label>
			   <img src="parte4/33_03_01.png"/>
			   <figcaption>Se considerarmos o ponto <b>P</b> pertencente à Circunferência de Apolônio construída, a razão entre as medidas dos segmentos <b>AP</b> e <b>BP</b> será igual à razão da Divisão Harmônica $\mathsf{ k = {5 \over 3} }$.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="422" name="sl">
			   <label for="422"></label>
			   <img src="parte4/33_03_01.png"/>
			   <figcaption>O centro desta circunferência é encontrado com a mediatriz de <b>MN</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte4/33_03_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0034.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos utilizar a régua, o compasso e os esquadros para fazer esta construção. </p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="423" name="sl" checked>
			   <label for="423"></label>
			   <img src="parte4/34_01_01.png"/>
			   <figcaption>Vamos encontrar os conjugados harmônicos de <b>AB</b> na razão $\mathsf{ 5 \over 2 }$. Na extremidade <b>A</b>, construa o segmento <b>A5</b> = 5cm com inclinação qualquer.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="424" name="sl">
			   <label for="424"></label>
			   <img src="parte4/34_01_02.png"/>
			   <figcaption>Usando os esquadros, construa a reta paralela a <b>A5</b> que passa por <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="425" name="sl">
			   <label for="425"></label>
			   <img src="parte4/34_01_03.png"/>
			   <figcaption>Construa os segmentos <b>B2</b> e <b>B2'</b> com medidas iguais a 2cm, correspondente ao denominador da razão.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="426" name="sl">
			   <label for="426"></label>
			   <img src="parte4/34_01_04.png"/>
			   <figcaption>Unindo os pontos <b>2</b> e <b>5</b>, encontramos o 3&ordm; conjugado harmônico de <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="427" name="sl">
			   <label for="427"></label>
			   <img src="parte4/34_01_05.png"/>
			   <figcaption>>Unindo os pontos <b>2'</b> e <b>5</b>, encontramos o 4&ordm; conjugado harmônico de <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="428" name="sl">
			   <label for="428"></label>
			   <img src="parte4/34_01_06.png"/>
			   <figcaption>Agora podemos construir a mediatriz de <b>MN</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="429" name="sl">
			   <label for="429"></label>
			   <img src="parte4/34_01_07.png"/>
			   <figcaption>Com centro no ponto médio de <b>MN</b>, construa a circunferência de raio <b>OM = ON</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="430" name="sl">
			   <label for="430"></label>
			   <img src="parte4/34_01_08.png"/>
			   <figcaption>A construção é similar para a razão $\mathsf{ 1 \over 4 }$.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="431" name="sl">
			   <label for="431"></label>
			   <img src="parte4/34_01_09.png"/>
			   <figcaption>Com centro no ponto médio de <b>MN</b>, construa a circunferência de raio <b>OM = ON</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte4/34_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0034a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos utilizar a régua, o compasso e os esquadros para fazer esta construção. Como temos a medida do lado <b>a</b> e a razão dos outros lados, precisamos utilizar a Circunferência de Apolônio de <b>a</b> com a razão $\mathsf{ b \over c }$</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="432" name="sl" checked>
			   <label for="432"></label>
			   <img src="parte4/34_02_01.png"/>
			   <figcaption>Na extremidade <b>B</b>, construa o segmento <b>B5</b> = 5cm com inclinação qualquer, correspondente ao lado <b>c</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="433" name="sl">
			   <label for="433"></label>
			   <img src="parte4/34_02_02.png"/>
			   <figcaption>Usando os esquadros, construa a reta paralela a <b>B5</b> que passa por <b>C</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="434" name="sl">
			   <label for="434"></label>
			   <img src="parte4/34_02_03.png"/>
			   <figcaption>Construa os segmentos <b>C3</b> e <b>C3'</b> com medidas iguais a 3cm, correspondente ao lado <b>b</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="435" name="sl">
			   <label for="435"></label>
			   <img src="parte4/34_02_04.png"/>
			   <figcaption>Unindo os pontos <b>3</b> e <b>5</b>, encontramos o 3&ordm; conjugado harmônico de <b>BC</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="436" name="sl">
			   <label for="436"></label>
			   <img src="parte4/34_02_05.png"/>
			   <figcaption>>Unindo os pontos <b>3'</b> e <b>5</b>, encontramos o 4&ordm; conjugado harmônico de <b>BC</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="437" name="sl">
			   <label for="437"></label>
			   <img src="parte4/34_02_06.png"/>
			   <figcaption>Agora podemos construir a mediatriz de <b>MN</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="438" name="sl">
			   <label for="438"></label>
			   <img src="parte4/34_02_07.png"/>
			   <figcaption>Com centro no ponto médio de <b>MN</b>, construa a circunferência de raio <b>OM = ON</b>. A Circunferência de Apolônio é o primeiro lugar geométrico do vértice <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="439" name="sl">
			   <label for="439"></label>
			   <img src="parte4/34_02_08.png"/>
			   <figcaption>Como temos a medida da altura <b>h<sub>a</sub></b>, devemos construir a reta paralela a <b>BC</b> com distância <b>h<sub>a</sub></b> = 4cm. Podemos usar a mediatriz para marcar esta distância, pois ela é perpendicular a <b>BC</b>: logo, encontramos os pontos <b>P</b> e <b>Q</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="440" name="sl">
			   <label for="440"></label>
			   <img src="parte4/34_02_09.png"/>
			   <figcaption>Usando os esquadros, construa as retas paralelas a <b>BC</b> que passam por <b>P</b> e <b>Q</b>. Temos 4 soluções para este exercício.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="441" name="sl">
			   <label for="441"></label>
			   <img src="parte4/34_02_10.png"/>
			   <figcaption>Escolha uma das interseções para formar o <b>&#9651;ABC</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte4/34_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0034b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos utilizar a régua, o compasso e os esquadros para fazer esta construção.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="442" name="sl" checked>
			   <label for="442"></label>
			   <img src="parte4/34_03_01.png"/>
			   <figcaption>Construa o segmento <b>AB</b> = 3,5cm, e na extremidade <b>A</b>, construa o segmento <b>A5</b> = 5cm com inclinação qualquer, correspondente ao denominador da razão <b>&lambda;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="443" name="sl">
			   <label for="443"></label>
			   <img src="parte4/34_03_02.png"/>
			   <figcaption>Usando os esquadros, construa a reta paralela a <b>A5</b> que passa por <b>B</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="444" name="sl">
			   <label for="444"></label>
			   <img src="parte4/34_03_03.png"/>
			   <figcaption>Construa os segmentos <b>B2</b> e <b>B2'</b> com medidas iguais a 2cm, correspondente ao numerador da razão <b>&lambda;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="445" name="sl">
			   <label for="445"></label>
			   <img src="parte4/34_03_04.png"/>
			   <figcaption>Unindo os pontos <b>2</b> e <b>5</b>, encontramos o 3&ordm; conjugado harmônico de <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="446" name="sl">
			   <label for="446"></label>
			   <img src="parte4/34_03_05.png"/>
			   <figcaption>>Unindo os pontos <b>2'</b> e <b>5</b>, encontramos o 4&ordm; conjugado harmônico de <b>AB</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="447" name="sl">
			   <label for="447"></label>
			   <img src="parte4/34_03_06.png"/>
			   <figcaption>Agora podemos construir a mediatriz de <b>MN</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="448" name="sl">
			   <label for="448"></label>
			   <img src="parte4/34_03_07.png"/>
			   <figcaption>Com centro no ponto médio de <b>MN</b>, construa a circunferência de raio <b>OM = ON</b>. A Circunferência de Apolônio é o primeiro lugar geométrico do ponto procurado <b>S</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="449" name="sl">
			   <label for="449"></label>
			   <img src="parte4/34_03_08.png"/>
			   <figcaption>Como o ponto "enxerga" <b>AB</b> segundo ângulo de 45&deg;, vamos construir o arco capaz deste ângulo. Podemos construí-lo de maneira mais simples construindo primeiro o arco capaz de 90&deg;...</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="450" name="sl">
			   <label for="450"></label>
			   <img src="parte4/34_03_09.png"/>
			   <figcaption>... e o centro do arco capaz de 45&deg; será a interseção do arco capaz de 90&deg; com a mediatriz de <b>AB</b>. O ponto <b>S</b> estará na interseção do arco capaz de 45&deg; com a Circunferência de Apolônio.</figcaption>
		   </li>
		</ul>
		<img src="parte4/34_03_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0035.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Neste exercício proposto, utilizamos a Circunferência de Apolônio com a razão $\mathsf{ 2 \over 3 }$.</p>
	<img src="parte4/35_01_00.png"/>
	<figcaption></figcaption>
  </details></div>
  <img src="parte4/apos_dg_0035a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Neste exercício proposto, utilizamos a Circunferência de Apolônio com a razão $\mathsf{ 7 \over 4 }$.</p>
	<img src="parte4/35_02_00.png"/>
	<figcaption></figcaption>
  </details></div>
  <img src="parte4/apos_dg_0035b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Neste exercício proposto, utilizamos a Circunferência de Apolônio com a razão $\mathsf{ 1 \over 3 }$.</p>
	<img src="parte4/35_03_00.png"/>
	<figcaption></figcaption>
  </details></div>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0036.png"/>
  <p align="center">Podemos escrever a relação de quarta proporcional de outras maneiras:
  <br>$\mathsf{ {a \cdot x} = {b \cdot c} }$ ou $\mathsf{ {a \over c} = {b \over x} }$.</p>
  <img src="parte4/apos_dg_0036a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos utilizar a régua e os esquadros para fazer esta construção. Aplicaremos o teorema de Tales para encontrar o segmento <b>x</b>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="451" name="sl" checked>
			   <label for="451"></label>
			   <img src="parte4/36_01_01.png"/>
			   <figcaption>Vamos encontrar o segmento <b>x</b> tal que $\mathsf{ {a \over b} = {c \over x} }$. Podemos construir os segmentos <b>a</b> e <b>b</b>, que são o numerador e o denominador da primeira fração, em uma mesma reta. </figcaption>
		   </li>
		   <li>
			   <input type="radio" id="452" name="sl">
			   <label for="452"></label>
			   <img src="parte4/36_01_02.png"/>
			   <figcaption>Construindo uma reta com inclinação qualquer, que passa pela extremidade <b>A</b>, podemos construir o segmento correspondente ao numerador da outra fração: <b>c</b>. Usando os esquadros, determine a reta paralela a <b>BD</b> que passa pelo ponto <b>C</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="453" name="sl">
			   <label for="453"></label>
			   <img src="parte4/36_01_03.png"/>
			   <figcaption>De acordo com o Teorema de Tales, os segmentos correspondentes são proporcionais, ou seja, $\mathsf{ {a \over b} = {c \over x} }$.</figcaption>
		   </li>
		</ul>
		<img src="parte4/36_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0036b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Neste exercício proposto, utilizamos o Teorema de Tales com as razões nas ordens especificadas em cada item.</p>
	<img src="parte4/36_02_00.png"/>
	<figcaption></figcaption>
  </details></div>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0037.png"/>
  <p align="center">Podemos escrever a relação de terceira proporcional de outras maneiras:
  <br>$\mathsf{{a \cdot x} = b^2}$ ou $\mathsf{b = \sqrt{a \cdot x} }$.</p>
  <img src="parte4/apos_dg_0037a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos utilizar a régua e os esquadros para fazer esta construção. Aplicaremos o teorema de Tales para encontrar o segmento <b>x</b>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="454" name="sl" checked>
			   <label for="454"></label>
			   <img src="parte4/37_01_01.png"/>
			   <figcaption>Vamos encontrar o segmento <b>x</b> tal que $\mathsf{ {a \over b} = {b \over x} }$. Podemos construir os segmentos <b>a</b> e <b>b</b>, que são o numerador e o denominador da primeira fração, em uma mesma reta. </figcaption>
		   </li>
		   <li>
			   <input type="radio" id="455" name="sl">
			   <label for="455"></label>
			   <img src="parte4/37_01_02.png"/>
			   <figcaption>Construindo uma reta com inclinação qualquer, que passa pela extremidade <b>A</b>, podemos construir o segmento correspondente ao numerador da outra fração: <b>b</b>. Usando os esquadros, determine a reta paralela a <b>BD</b> que passa pelo ponto <b>C</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="456" name="sl">
			   <label for="456"></label>
			   <img src="parte4/37_01_03.png"/>
			   <figcaption>De acordo com o Teorema de Tales, os segmentos correspondentes são proporcionais, ou seja, $\mathsf{ {a \over b} = {b \over x} }$.</figcaption>
		   </li>
		</ul>
		<img src="parte4/37_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0037b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Neste exercício proposto, utilizamos o Teorema de Tales com as razões nas ordens especificadas em cada item.</p>
	<img src="parte4/37_02_00.png"/>
	<figcaption></figcaption>
  </details></div>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0038.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos utilizar a régua, o compasso e os esquadros para fazer esta construção.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="457" name="sl" checked>
			   <label for="457"></label>
			   <img src="parte4/38_01_01.png"/>
			   <figcaption>Vamos encontrar o inverso de <b>a</b>, que será o segmento <b>x</b> tal que $\mathsf{ x = {1 \over a} }$ ou $\mathsf{ {x \over 1} = {1 \over a} }$.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="458" name="sl">
			   <label for="458"></label>
			   <img src="parte4/38_01_02.png"/>
			   <figcaption>Usando a terceira proporcional, com segmento de 1cm, encontramos o inverso <b>x</b> de <b>a</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="459" name="sl">
			   <label for="459"></label>
			   <img src="parte4/38_01_03.png"/>
			   <figcaption>Usando a terceira proporcional, com segmento de 1cm, encontramos o inverso <b>y</b> de <b>b</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="460" name="sl" checked>
			   <label for="460"></label>
			   <img src="parte4/38_01_04.png"/>
			   <figcaption>Agora podemos dividir o segmento <b>AB</b> em partes proporcionais aos inversos. Construa o segmento <b>AB</b> e uma reta com inclinação qualquer que passa por <b>A</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="461" name="sl">
			   <label for="461"></label>
			   <img src="parte4/38_01_05.png"/>
			   <figcaption>Construa nesta reta qualquer os segmentos <b>x</b> e <b>y</b> usando o compasso.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="462" name="sl">
			   <label for="462"></label>
			   <img src="parte4/38_01_06.png"/>
			   <figcaption>Com os esquadros, construa a reta paralela que define <b>AP &isin; AB</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte4/38_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0038a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Solução</summary>
	<p>Neste exercício proposto, podemos reescrever as relações que definem os segmentos  <b>a</b> e  <b>b</b>.</p>
	<img src="parte4/38_02_00.png"/>
	<figcaption>Estas relações são de uma quarta proporcional e uma terceira proporcional.</figcaption>
  </details></div>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0039.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos utilizar a régua, o compasso e os esquadros para fazer esta construção.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="463" name="sl" checked>
			   <label for="463"></label>
			   <img src="parte4/39_01_01.png"/>
			   <figcaption>Vamos construir as projeções dos catetos sobre a hipotenusa. Começando com a projeção do cateto <b>c</b>, construimos o segmento <b>BH<sub>a</sub> = n</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="464" name="sl">
			   <label for="464"></label>
			   <img src="parte4/39_01_02.png"/>
			   <figcaption>No prolongamento de <b>BH<sub>a</sub></b>, construimos o segmento <b>H<sub>a</sub>C = m</b>, que é a projeção do cateto <b>b</b> sobre a hipotenusa.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="465" name="sl">
			   <label for="465"></label>
			   <img src="parte4/39_01_03.png"/>
			   <figcaption>Como o vértice <b>A</b> "enxerga" a hipotenusa segundo 90&deg;, vamos construir o arco capaz de 90&deg;. Construa a mediatriz de <b>BC</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="466" name="sl" checked>
			   <label for="466"></label>
			   <img src="parte4/39_01_04.png"/>
			   <figcaption>Com centro no ponto médio <b>M</b> e raio <b>MB = MC</b>, construa o arco capaz de 90&deg;.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="467" name="sl">
			   <label for="467"></label>
			   <img src="parte4/39_01_05.png"/>
			   <figcaption>Usando os esquadros, construa a reta perpendicular a <b>BC</b> que passa pelo ponto <b>H<sub>a</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="468" name="sl">
			   <label for="468"></label>
			   <img src="parte4/39_01_06.png"/>
			   <figcaption>A interseção da reta perpendicular a <b>BC</b> com o arco capaz é o vértice <b>A</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte4/39_01_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0039a.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4cf; &#x1f4d0; Resolução</summary>
	<p>Vamos utilizar a régua, o compasso e os esquadros para fazer esta construção.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="469" name="sl" checked>
			   <label for="469"></label>
			   <img src="parte4/39_02_01.png"/>
			   <figcaption>Vamos construir a hipotenusa <b>BC</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="470" name="sl">
			   <label for="470"></label>
			   <img src="parte4/39_02_02.png"/>
			   <figcaption>A projeção do cateto <b>b</b> sobre a hipotenusa é o segmento  <b>CH<sub>a</sub> = m</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="471" name="sl">
			   <label for="471"></label>
			   <img src="parte4/39_02_03.png"/>
			   <figcaption>Como o vértice <b>A</b> "enxerga" a hipotenusa segundo 90&deg;, vamos construir o arco capaz de 90&deg;. Construa a mediatriz de <b>BC</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="472" name="sl" checked>
			   <label for="472"></label>
			   <img src="parte4/39_02_04.png"/>
			   <figcaption>Com centro no ponto médio <b>M</b> e raio <b>MB = MC</b>, construa o arco capaz de 90&deg;.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="473" name="sl">
			   <label for="473"></label>
			   <img src="parte4/39_02_05.png"/>
			   <figcaption>Usando os esquadros, construa a reta perpendicular a <b>BC</b> que passa pelo ponto <b>H<sub>a</sub></b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="474" name="sl">
			   <label for="474"></label>
			   <img src="parte4/39_02_06.png"/>
			   <figcaption>A interseção da reta perpendicular a <b>BC</b> com o arco capaz é o vértice <b>A</b>.</figcaption>
		   </li>
		</ul>
		<img src="parte4/39_02_00.png" class="fundo"/>
  </details></div>
  <img src="parte4/apos_dg_0039b.png"/>
  <div class="combo"><details class="sub"><summary>&#x1f4dd; Propriedade</summary>
	<p>Vamos mostrar as relações entre as medidas das projeções dos catetos sobre a hipotenusa e a altura de um triângulo retângulo <b>&#9651;ABC</b>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="475" name="sl" checked>
			   <label for="475"></label>
			   <img src="parte4/39_03_01.png"/>
			   <figcaption>Vamos considerar a hipotenusa <b>BC = a</b> e o <b>&angsph;CH<sub>a</sub>A = 90&deg;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="476" name="sl">
			   <label for="476"></label>
			   <img src="parte4/39_03_02.png"/>
			   <figcaption>Considere o ângulo <b>&angsph;C = &gamma;</b>. Temos que os triângulos <b>&#9651;H<sub>a</sub>AC</b> e <b>&#9651;ABC</b> são semelhantes (ângulos correspondentes iguais). Logo, os lados correspondentes são proporcionais na mesma razão, ou seja,  $\mathsf{ {h \over c} = {b \over a} = {m \over b} }$. Da última igualdade, podemos concluir que $\mathsf{ b^2 = {a \cdot m} }$.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="477" name="sl">
			   <label for="477"></label>
			   <img src="parte4/39_03_03.png"/>
			   <figcaption>Considere o ângulo <b>&angsph;B = &beta;</b>. Temos que os triângulos <b>&#9651;H<sub>a</sub>BA</b> e <b>&#9651;ABC</b> são semelhantes (ângulos correspondentes iguais). Logo, os lados correspondentes são proporcionais na mesma razão, ou seja,  $\mathsf{ {h \over b} = {c \over a} = {n \over c} }$. Da última igualdade, podemos concluir que $\mathsf{ c^2 = {a \cdot n} }$.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="478" name="sl" checked>
			   <label for="478"></label>
			   <img src="parte4/39_03_04.png"/>
			   <figcaption>Temos que os triângulos <b>&#9651;H<sub>a</sub>BA</b> e <b>&#9651;H<sub>a</sub>AC</b> são semelhantes (ângulos correspondentes iguais). Logo, temos a proporcionalidade dos lados na mesma razão, ou seja,  $\mathsf{ {c \over b} = {h \over m} = {n \over h} }$. Da última igualdade, podemos concluir que $\mathsf{ h^2 = {m \cdot n} }$.</figcaption>
		   </li>
		</ul>
		<img src="parte4/39_03_00.png" class="fundo"/>
  </details></div>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0040.png"/>
  <img src="parte4/apos_dg_0040a.png"/>
  <img src="parte4/apos_dg_0040b.png"/>
  <figcaption>Equações da resolução:
  <br>$\mathsf{\frac{z}{\sqrt{4}}=\frac{p}{\sqrt{5}}}$ ou $\mathsf{z=\frac{p\sqrt{4}}{\sqrt{5}} }$ ou $\mathsf{z=p\sqrt{\frac{4}{5}} }$ ou $\mathsf{z=\sqrt{\frac{4}{5}p.p} }$.</figcaption>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0041.png"/>
  <img src="parte4/apos_dg_0041a.png"/>
  <img src="parte4/apos_dg_0041b.png"/>
  <img src="parte4/apos_dg_0041c.png"/>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0042.png"/>
  <figcaption>Colocar demonstração do Teo Pitágoras.</figcaption>
  <img src="parte4/apos_dg_0042a.png"/>
  <img src="parte4/apos_dg_0042b.png"/>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0043.png"/>
  <img src="parte4/apos_dg_0043a.png"/>
  <img src="parte4/apos_dg_0043b.png"/>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0044.png"/>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0045.png"/>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0046.png"/>
  <img src="parte4/apos_dg_0046a.png"/>
  <img src="parte4/apos_dg_0046b.png"/>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0047.png"/>
  <img src="parte4/apos_dg_0047a.png"/>
  <img src="parte4/apos_dg_0047b.png"/>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
  <img src="parte4/apos_dg_0048.png"/>
  <img src="parte4/apos_dg_0048a.png"/>
  <p class="topop"><a href="#parte4" class="topo">voltar ao topo</a></p>
</details>

<details>
  <summary id="parte5">3. Triângulos e quadriláteros</summary>
  <p>Material da página 49 até a página 64.</p>
  <img src="parte5/apos_dg_0049.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
  <img src="parte5/apos_dg_0050.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
  <img src="parte5/apos_dg_0051.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
  <img src="parte5/apos_dg_0052.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
  <img src="parte5/apos_dg_0053.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
  <img src="parte5/apos_dg_0054.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
  <img src="parte5/apos_dg_0055.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
  <img src="parte5/apos_dg_0056.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
  <img src="parte5/apos_dg_0057.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
  <img src="parte5/apos_dg_0058.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
  <img src="parte5/apos_dg_0059.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
  <img src="parte5/apos_dg_0060.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
  <img src="parte5/apos_dg_0061.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
  <img src="parte5/apos_dg_0062.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
  <img src="parte5/apos_dg_0063.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
  <img src="parte5/apos_dg_0064.png"/>
  <p class="topop"><a href="#parte5" class="topo">voltar ao topo</a></p>
</details>

<details>
  <summary id="parte6">4. Tangência e concordância</summary>
  <p>Material da página 65 até a página 78.</p>
  <img src="parte6/apos_dg_0065.png"/>
  <p class="topop"><a href="#parte6" class="topo">voltar ao topo</a></p>
  <img src="parte6/apos_dg_0066.png"/>
  <p class="topop"><a href="#parte6" class="topo">voltar ao topo</a></p>
  <img src="parte6/apos_dg_0067.png"/>
  <p class="topop"><a href="#parte6" class="topo">voltar ao topo</a></p>
  <img src="parte6/apos_dg_0068.png"/>
  <p class="topop"><a href="#parte6" class="topo">voltar ao topo</a></p>
  <img src="parte6/apos_dg_0069.png"/>
  <p class="topop"><a href="#parte6" class="topo">voltar ao topo</a></p>
  <img src="parte6/apos_dg_0070.png"/>
  <p class="topop"><a href="#parte6" class="topo">voltar ao topo</a></p>
  <img src="parte6/apos_dg_0071.png"/>
  <p class="topop"><a href="#parte6" class="topo">voltar ao topo</a></p>
  <img src="parte6/apos_dg_0072.png"/>
  <p class="topop"><a href="#parte6" class="topo">voltar ao topo</a></p>
  <img src="parte6/apos_dg_0073.png"/>
  <p class="topop"><a href="#parte6" class="topo">voltar ao topo</a></p>
  <img src="parte6/apos_dg_0074.png"/>
  <p class="topop"><a href="#parte6" class="topo">voltar ao topo</a></p>
  <img src="parte6/apos_dg_0075.png"/>
  <p class="topop"><a href="#parte6" class="topo">voltar ao topo</a></p>
  <img src="parte6/apos_dg_0076.png"/>
  <p class="topop"><a href="#parte6" class="topo">voltar ao topo</a></p>
  <img src="parte6/apos_dg_0077.png"/>
  <p class="topop"><a href="#parte6" class="topo">voltar ao topo</a></p>
  <img src="parte6/apos_dg_0078.png"/>
  <p class="topop"><a href="#parte6" class="topo">voltar ao topo</a></p>
</details>

<details>
  <summary id="parte7">5. Polígonos regulares</summary>
  <p>Material da página 79 até a página 89.</p>
  <img src="parte7/apos_dg_0079.png"/>
  <p class="topop"><a href="#parte7" class="topo">voltar ao topo</a></p>
  <img src="parte7/apos_dg_0080.png"/>
  <p class="topop"><a href="#parte7" class="topo">voltar ao topo</a></p>
  <img src="parte7/apos_dg_0081.png"/>
  <p class="topop"><a href="#parte7" class="topo">voltar ao topo</a></p>
  <img src="parte7/apos_dg_0082.png"/>
  <p class="topop"><a href="#parte7" class="topo">voltar ao topo</a></p>
  <img src="parte7/apos_dg_0083.png"/>
  <p class="topop"><a href="#parte7" class="topo">voltar ao topo</a></p>
  <img src="parte7/apos_dg_0084.png"/>
  <p class="topop"><a href="#parte7" class="topo">voltar ao topo</a></p>
  <img src="parte7/apos_dg_0085.png"/>
  <p class="topop"><a href="#parte7" class="topo">voltar ao topo</a></p>
  <img src="parte7/apos_dg_0086.png"/>
  <p class="topop"><a href="#parte7" class="topo">voltar ao topo</a></p>
  <img src="parte7/apos_dg_0087.png"/>
  <p class="topop"><a href="#parte7" class="topo">voltar ao topo</a></p>
  <img src="parte7/apos_dg_0088.png"/>
  <p class="topop"><a href="#parte7" class="topo">voltar ao topo</a></p>
  <img src="parte7/apos_dg_0089.png"/>
  <p class="topop"><a href="#parte7" class="topo">voltar ao topo</a></p>
</details>

<details>
  <summary id="parte8">6.1. Retificação de circunferência</summary>
  <p>Material da página 89 até a página 93.</p>
  <img src="parte8/apos_dg_0089.png"/>
  <p class="topop"><a href="#parte8" class="topo">voltar ao topo</a></p>
  <img src="parte8/apos_dg_0090.png"/>
  <p class="topop"><a href="#parte8" class="topo">voltar ao topo</a></p>
  <img src="parte8/apos_dg_0091.png"/>
  <p class="topop"><a href="#parte8" class="topo">voltar ao topo</a></p>
  <img src="parte8/apos_dg_0092.png"/>
  <p class="topop"><a href="#parte8" class="topo">voltar ao topo</a></p>
  <img src="parte8/apos_dg_0093.png"/>
  <p class="topop"><a href="#parte8" class="topo">voltar ao topo</a></p>
</details>

<details style="border-bottom: 1px solid #a2dec0;">
  <summary id="parte9">6.2. Equivalência de áreas</summary>
  <p>Material da página 94 até a página 103.</p>
  <img src="parte9/apos_dg_0094.png"/>
  <p class="topop"><a href="#parte9" class="topo">voltar ao topo</a></p>
  <img src="parte9/apos_dg_0095.png"/>
  <p class="topop"><a href="#parte9" class="topo">voltar ao topo</a></p>
  <img src="parte9/apos_dg_0096.png"/>
  <p class="topop"><a href="#parte9" class="topo">voltar ao topo</a></p>
  <img src="parte9/apos_dg_0097.png"/>
  <p class="topop"><a href="#parte9" class="topo">voltar ao topo</a></p>
  <img src="parte9/apos_dg_0098.png"/>
  <p class="topop"><a href="#parte9" class="topo">voltar ao topo</a></p>
  <img src="parte9/apos_dg_0099.png"/>
  <p class="topop"><a href="#parte9" class="topo">voltar ao topo</a></p>
  <img src="parte9/apos_dg_0100.png"/>
  <p class="topop"><a href="#parte9" class="topo">voltar ao topo</a></p>
  <img src="parte9/apos_dg_0101.png"/>
  <p class="topop"><a href="#parte9" class="topo">voltar ao topo</a></p>
  <img src="parte9/apos_dg_0102.png"/>
  <p class="topop"><a href="#parte9" class="topo">voltar ao topo</a></p>
  <img src="parte9/apos_dg_0103.png"/>
  <p class="topop"><a href="#parte9" class="topo">voltar ao topo</a></p>
</details>


<h4>página desenvolvida por:</h4> 
<p>Paulo Henrique Siqueira</p>  
<p><b>contato:</b> paulohscwb@gmail.com </p>

<h4>O desenvolvimento deste material de construções geométricas faz parte do Grupo de Estudos em Expressão Gráfica (GEEGRAF) da Universidade Federal do Paraná (UFPR)</h4>  

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Licença Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png"/></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Desenho Geométrico</span> de <a xmlns:cc="http://creativecommons.org/ns#" href="https://paulohscwb.github.io/desenho-geometrico/" property="cc:attributionName" rel="cc:attributionURL">Paulo Henrique Siqueira</a> está licenciado com uma Licença <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons - Atribuição-NãoComercial 4.0 Internacional</a>.

<h4>Como citar este trabalho:</h4> 
<p>Siqueira, P.H., "Desenho Geométrico". Disponível em: <https://paulohscwb.github.io/desenho-geometrico/>, Setembro de 2020.</p>

<h4>Referências:</h4>
<ol>
	<li></li>
	<li></li>
	<li></li>
<ol>