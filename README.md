<html>
## Markdown Basics 
<p><a href="http://daringfireball.net/projects/markdown/">Markdown </a> permite-lhe escrever usando um formato de texto simples, fácil para ler e escrever, do qual então se converte em HTML válido para visualização no GITHUB.</p>
### Escrita Básica 
####Parágrafos
<p>Parágrafos em Markdown são apenas uma ou mais linhas de texto consecutivos seguidos por uma ou mais linhas em branco.</p>
<pre><code>
Em 2 de julho, uma nave-mãe alienígena entrou em órbita da Terra e implantado várias dezenas nave espacial em forma de pires "destruidor", a cada 15 milhas (24 km) de largura. 

Em 3 de julho, os Cavaleiros Negros, um esquadrão de Marine Corps F / A-18 Hornets , participou de uma investida ao destruidor perto da cidade de Los Angeles.
</code></pre>
####Cabeçalhos
<p>Você pode criar um cabeçalho adicionando um ou mais <code>#</code> símbolos antes do seu texto de cabeçalho.</P>
 Número de <code>#</code> que você usa vão determinar o tamanho do seu cabeçalho.</p>
<pre><p># O maior título (uma tag <code>&lt;/h1&gt;</code>)
## O segundo maior título  (uma tag <code>&lt;/h2&gt;</code>)
... 
###### O 6º maior título (uma tag <code>&lt;/h6&gt;</code> ) </p> </pre>
#### Bloco de Citação
<p> Você pode criar uma <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote">Bloco de Citação</a> com um <code>></code>.
<pre>Nas palavras de Abraham Lincoln:
<code>></code> Pardon My French</pre></p>
####Texto Styling
<p>Você pode fazer o texto <strong><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong">em negrito</a></strong> ou <em>itálico</em>.</p>
<pre> 
*Este texto pode ser itálico* 
**Este texto pode ser em negrito** </pre>
<p> Ambos <strong>negrito</strong> e <em>itálico</em> pode usar um <code>*</code> ou um <code>_</code> em torno do texto para o estilo. Isso permite que você combine os dois em negrito e itálico, se for necessário. </p>
<pre>** Todos _devem_ participar da reunião às 5 horas de hoje. **</pre>
###Listas
####Listas não ordenadas
<p>Você pode fazer uma <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul">lista desordenada</a> precedendo itens da lista ou com um <code>*</code> ou com um <code>-</code>.</p>
<pre>
* Item
* Item
* Item

- Item
- Item
- Item </pre>
####Listas ordenadas
<p>Você pode fazer uma <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol"> lista ordenada</a> precedendo alguns itens da lista com um número.</p>
<pre><code>1. Item 1
2. Item 2
3. Item 3</code></pre>
####Listas aninhadas
<p>Você pode criar listas aninhadas pelo recuo dos itens da lista por dois espaços.</p>
<pre><code>1. Item 1
 1. Um corolário do item acima.
 2. No entanto, outro ponto a considerar
2. O Item 2
 * Um corolário que não precisa ser solicitado.
   * Este é recuado em quatro espaços, porque dois espaços são mais longe do que o item acima.
   * Você pode querer fazer uma nova lista.
3. O Item 3</code></pre>
###A formatação do código
####Formatos em linha
<p>Use apóstrofos (<code>`</code>) para formatar o texto em um formato especial em um espaço único. Tudo dentro dos apóstrofos, sem nenhuma formatação especial.</p>
 <pre>Aqui está uma ideia: por que não vamos tomar \`ProjetoSuperior\` e transformá-lo em \`projeto ** razoável **\`.</pre>
###Linhas Múltiplas
 <p>Você pode usar apóstrofos triplos (<code>\`\`\`</code>) para formatar o texto com o seu próprio bloco distinto.</p>
 Confira este programa que eu  escrevi:
 <pre><code> \`\`\`
 x = 0
 x = 2+2
 o que é x
 \`\`\` </code></pre>
###Links
<p>Você pode criar uma ligação com uma linha por envolvimento de links texto entre colchetes ( <code>[ ]</code> ), em seguida, envolver uma ligação entre parênteses ( <code>( )</code> ).</p>
<p>Por exemplo, para criar um hiperlink para www.github.com, com o link que diz, Visite Github !, você escreveria isso em Markdown: <code>[Visit GitHub!](www.github.com)</code>.</p>
###Veja Também
<ul><li><a href="https://help.github.com/articles/github-flavored-markdown/">GitHub Flavored Markdown</a></li>
<li><a href="https://help.github.com/articles/writing-on-github/">Escrevendo no GitHub</a>
<li><a href="http://guides.github.com/features/mastering-markdown/">Dominando Markdown</a></li></ul>
</html>
