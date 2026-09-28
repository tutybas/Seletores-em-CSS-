# Seletores

Página de estudo em HTML e CSS que demonstra diferentes formas de selecionar e estilizar elementos. Os exemplos incluem formatação de textos, seleção por atributos e efeitos ao passar o mouse.

## Funcionalidades

| Funcionalidade | Descrição |
| --- | --- |
| Formatação de textos | Aplica cor e tamanho ao título principal, fonte monoespaçada a parágrafos e destaque vermelho a um trecho com `span`. |
| Estilização de seção | Define fundo violeta para `section` e texto azul para o parágrafo identificado dentro dela. |
| Links externos | Disponibiliza links para o GitHub do autor e o UOL, sendo o segundo configurado para abrir em uma nova aba e receber uma borda. |
| Efeito ao passar o mouse | Altera a cor de uma `div` de azul para vermelho e amplia seu tamanho em 10%, com transição de 0,3 segundo. |
| Destaque da primeira letra | Estiliza a primeira letra do `h2` com a classe `titulo-destaque`, aplicando cor aqua e tamanho de 16px. |

## Sobre a organização do código

O `Index.html` reúne o conteúdo e os elementos usados nos exemplos, enquanto o `estilos.css` concentra as regras de apresentação. A folha de estilos externa permite ajustar a aparência sem misturar as declarações CSS ao conteúdo HTML.

As classes permitem reaproveitar estilos, como a fonte aplicada a mais de um parágrafo por `.fonte`. Os identificadores direcionam regras a elementos específicos, enquanto os seletores de tipo e de atributo agrupam elementos pelas suas características.

## Seletores CSS na prática

O projeto reúne exemplos de seletores com diferentes critérios:

| Tipo | Exemplo no código | Aplicação |
| --- | --- | --- |
| Tipo de elemento | `section` | Aplica fundo violeta às seções. |
| Classe | `.destaque` e `.fonte` | Destaca um trecho de texto e define uma fonte monoespaçada. |
| Identificador | `#id12` e `#idpsec` | Estiliza o título principal e o parágrafo da seção. |
| Atributo | `a[target="_blank"]` | Aplica borda aos links que possuem esse valor de `target`. |
| Pseudoclasse estrutural | `p:first-of-type` | Seleciona o primeiro parágrafo entre os elementos irmãos de cada contêiner. |
| Pseudoclasse de interação | `.minha-div:hover` | Modifica a aparência da `div` quando o ponteiro está sobre ela. |
| Pseudoelemento | `h2.titulo-destaque::first-letter` | Estiliza apenas a primeira letra do título selecionado. |

A regra `p:first-of-type` define a cor preta, mas o parágrafo da seção permanece azul porque `#idpsec` possui maior especificidade. Esse encontro de regras permite observar como o CSS resolve estilos concorrentes.

## Aprendizados aplicados

- Vinculação de uma folha de estilos externa ao HTML.
- Uso de seletores de tipo, classe, identificador e atributo.
- Aplicação de pseudoclasses e pseudoelementos.
- Especificidade de seletores na definição da cor dos parágrafos.
- Formatação de textos, cores de fundo, bordas e dimensões.
- Uso de `span` para estilizar um trecho dentro de um parágrafo.
- Combinação de `:hover`, `transition` e `transform: scale()` para criar um efeito visual.
- Criação de links externos com `href` e uso de `target="_blank"`.
