# aluraplus

## Resumo do curso de : HTML e CSS: praticando HTML/CSS

### Modulo 1: Iniciando o projeto
Resumo:
- Preparando o Ambiente:  
Criamos uma cópia do projeto feito em FIGMA para utilizarmos durante o curso.
- Base de HTML
Analisamos o FIGMA do projeto "Alura+". 
Criamos uma pasta para colocar os arquivos. 
Abrimos a pasta no VSCode e criamos dois arquivos: Criando o index.html e o styles.css.
Criamos a base do projeto, a estrutura básica com head, body, importações, links e metadados em HTML.

- Começando com CSS
 Criamos variáveis CSS analisando o projeto em Figma. Salvamos as mensagens de texto e os códigos das cores no arquivo para criarmos variáveis de cores dos elementos do projeto. Uma usando a variável "color" e outra usando a propriedade "background-color". 
Instalamos a extensão Live-Server que abre uma nova janela no navegador com a URL.

- Variável CSS
"Variáveis CSS auxiliam no entendimento do uso das cores por terem nomes que fazem sentido com o seu uso, consequentemente isso também facilita a atribuição nos elementos HTML. Além desses dois benefícios, facilita na manutenção do código: é possível alterar o valor de alguma cor reescrevendo um único lugar do código."

- Inserindo imagens:
Baixamos e gravamos as imagens do FIGMA na pasta "img" da pasta do projeto do computador. Entendemos a diferenças de utilização em inserir imagem de fundo com background-image e de inserir com a tag <img> .
Inserimos e aplicamos a imagem de fundo e a imagem do "Combo+" no projeto.

- A motivação da Imagem:
  "Quando estamos inserindo uma imagem, é importante pensar: essa imagem faz parte do conteúdo da página? Se não, é possível colocá-la como background-image() de algum elemento."

### Para saber mais: primeiros passos no front-end
- Outras extensões no artigo [Extensões VS Code: descubra quais são as mais usadas](https://www.alura.com.br/artigos/extensoes-vs-code-descubra-as-mais-usadas).
- Artigo [“O que é o HTML e suas tags? Parte 1: estrutura básica”](https://www.alura.com.br/artigos/o-que-e-html-suas-tags-parte-1-estrutura-basica)


### Modulo 2: A dupla HTML e CSS
Resumo:
- Criando um botão:
  Criamos um botão usando uma âncora para o link do site da Alura, estilizamos o botão e definimos o display do botão para block, para ele ocupar todo o bloco.

- Grid e continuação:  
Conseguimos definir o espaço do botão, sem que ele ocupe todo o espaço do bloco(porque não é isso que está no layout) utilizando display: grid e grid-template-columns.

- Lidando com fontes: 
Importamos a fonte geral no site chamada 'Inter', com 16px, peso 400 e 700. Depois alteramos o tamanho do aviso, do título e retiramos a decoração dos botões. 

### Material de estudo complementar:
1 - padrão de nomenclatura: o Block Element Modifier (BEM): artigo [“Nome de classes no CSS”](https://www.alura.com.br/artigos/nomes-de-classes-no-css), produzido pelo instrutor Yuri Padilha.\
2 - Uso de classes: artigo [“Qual a diferença entre id e class”](https://www.alura.com.br/artigos/qual-diferenca-entre-id-e-class).\
3 - Unidade de medida relativa “em” na criação do botão: artigo [“Guia de unidades no CSS” do instrutor Paulo Scalercio](https://www.alura.com.br/artigos/guia-de-unidades-no-css).\
4 - Uso de Grid  [“Criando layouts com CSS Grid Layout”](https://www.alura.com.br/artigos/criando-layouts-com-css-grid-layout), produzido pelo Matheus Castiglioni.

### Modulo 3: Posicionando elementos
Resumo:
- Margins e paddings: 
Ajustamos o espaçamento. Aprendemos a diferença entre margin e padding;
Afastamos elementos dos cantos da tela e de outros elementos; Aprendemos diversas maneiras de determinar os valores e as direções das margens dentro da propriedade margin;
- Separando elementos: 
"Margins criam espaço ao redor do elemento e paddings criam dentro dele, ou seja, o padding afasta o conteúdo da borda e não um elemento do outro. Por fim, também podemos configurar valores diferentes para cada lado do elemento."
- Alinhamentos: Alinhamos o texto e imagem no centro da coluna, porque nós definimos apenas as colunas no grid. E centralizamos o texto, usando:
    align-items: center;
    text-align: center;

- Centralizando elementos:
<div class="container"><h2 class="container__titulo">Alura Cats!</h2><img src="https://thecatapi.com/api/images/get?format=src&type=gif" alt=”imagem de gatos” class="container__imagem"><p>Para mais informações:</p><a href="www.alura.com.br" class="container__botao">Acesse a Alura<a></div>

- Construindo nova section e Reutilizando estilos: Aprendemos a reutilizar elementos e seus estilos além de alterar os elementos, para personalizá-los, atribuindo mais de uma classe nos elementos para incluir novas estilizações além das existentes.

- Para saber mais: Inline-block:
Sugestão de leitura do artigo [“Pare de chutar e aprenda como funciona o display: inline-block”](https://medium.com/collabcode/pare-de-chutar-e-aprenda-como-funciona-o-display-inline-block-4e6cba2f19d4)


### Modulo 4: Finalizando nossa página
Resumo:
- Flexbox: Aprendemos a alinhar itens com o Flexbox e a tirar os estilos de listas, os pontinhos, aplicando "list-style-type: none;". Usamos flex-containers, flex-itens, flex-direction;
- O desafio do footer: Criamos o container footer e reforçamos o que foi ensinado adicionando imagem (logomarca), criando a lista de links e textos. 
- Faça como eu fiz: estilizando o footer: Estilizamos o footer com CSS.
- Pseudo-classes: Acrescentamos estilos que não existem no protótipo, que é passar o mouse por cima do link e ele troca de cor utilizando pseudo-classes ( "a:" {})
- Para saber mais: CSS interativo?: Sobre as pseudo-classes hover e active.

```
:focus: é aplicada quando um elemento está em foco, pode ser pelo clique do mouse ou seleção pelo teclado. Um exemplo é quando os campos de escrita em formulários estão selecionados para o usuário escrever.

:hover: detecta quando um usuário está com o mouse em cima do elemento, sem necessariamente estar clicando.

:active: detecta quando o elemento está ativo, quando há uma interação, por exemplo: o link <a> está sendo clicado.

:visited: detecta quando o link <a> já foi visitado, ou seja, se você já clicou anteriormente naquele link.

:link: detecta quando é um link <a> que nunca foi clicado antes.
```

 Para quem quiser er mais sobre pseudo-classes no MDN Web Docs

