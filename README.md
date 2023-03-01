# HTML e CSS

## Sobre este repositório
<p align="justify">
Este respositório tem como objetivo reunir meus estudos sobre front-end, principalmente a parte sobre HTML e CSS

## Conteúdo
<p align="justify">

### HTML

#### TAGS Estruturais:

- `<!DOCTYPE html>`
```js
// Informa qual a versão do HTML que estou usando.
```

 - `<head></head>`
```js
// Define o cabeçalho de um documento HTML, que traz informações sobre o documento que está sendo aberto. Além de informar ao navegador quais informações quero passar.
```

- `<meta charset="UTF-8">`
```js
/* Define propriedades da página, como codificação de caracteres, descrição da página, autor etc. O charset deixa claro qual o dicionário estamos usando. Neste caso, o UTF-8 é o dicionário que aceita acentuação. */
```

- `<title></title>`
```js
// Informa/define o título na aba do meu navegador.
```

- `<link rel="" href="">`
```js
// link: Define ligações da página com outros arquivos.
// rel: relacionamento.
// href: arquivo de referência ou arquivo para qual será o direcionamento assim que clicar na página
```

#### TAGS de Conteúdo:

- `<body></body>`
```js
/* define o conteúdo principal, o corpo do documento. Esta é a parte do documento HTML que é exibida no navegador. No corpo podem-se definir atributos comuns a toda a página, como cor de fundo, margens, e outras formatações */
```

- `<header></header>`
```js
// Cabeçalho e onde fica o título principal de abertura da página
```

- `<div></div>`
```js
// divisão utilizada apenas para fazer a divisão visual
```

- `<img>`
```js
// imagem
```

- `<h1></h1>`
```js
// Título principal
```

- `<nav></nav>`
```js
// Utilizado para marcar a navegação
```

- `<ul></ul>`
```js
/* Utilizado para fazer uma lista não ordenada de itens. 
<ol></ol> → Utilizado para lista ordenada
*/
```

- `<li></li>`
```js
// Separa cada elemento da lista.
```

- `<a></a>`
```js
// É uma  âncora → essa âncora permite que eu consiga linkar páginas umas com as outras.
```

#### Outras TAGS:

- `<main></main>`
```js
// A parte principal do meu conteúdo. 
```

- `<section></section>`
```js
// Utilizamos quando queremos demarcar um conteúdo fechado em si mesmo. 
```

- `<h2></h2>`
```js
// Outro nível de título.
```

- `<p></p>`
```js
// Parágrafo.
```

- `<form></form>`
```js
// Usado para criar formulários
```

- `<label></label>`
```js
// É usado como uma etiqueta para o meu input. É aquele texto que informa para o que serve aquele campo de entrada(input)
```

- `<input></input>`
```js
/* Informa qual informação será enviada pelo meu formulário; precisa de um type e um id. 
Existem diversos tipos de inputs: 
type="submit" | type="tel" | type="text" | type="email" | type="radio"
Cada um deles significa: campo de tipo submissão; campo de tipo telefone; campo de tipo texto; campo de tipo email; campo de tipo radio(círculo clicável)
*/
```

- `<textarea></textarea>`
```js
/* Para textos além de uma linha. Para tanto é necessário informar o número de colunas e linhas que esse campo deve ter: 
exemplo: <textarea> cols="70" rows="10" </textarea> */
```

- `<fieldset></fieldset> | <legend></legend>`
```js
/* Caixa de texto selecionável. Dentro de um form, os dados de um mesmo conjunto agrupados vão dentro de um <fieldset></fieldset>, e dentro de um fieldset não temos parágrafos, temos o <legend></legend>.
Exemplos:  
<fieldset>
<legend>Como prefere o nosso contato?</legend>
</fieldset>               
*/
```

- `<select></select> | <option></option>`
```js
/* Dentro de um fieldset, existe a possibilidade de criar uma caixa seletora, com opções. Para isso servem o select e o option. 
Exemplo:
<select>
 <option>Manhã</option>
 <option>Tarde</option>
 <option>Noite</option>
</select>

*/
```

- `<table></table> | <thead></thead> | <tbody></tbody> |<th></th> |<tr></tr> | <td></td> `
```js
/* 
Table → serve para criar tabelas;  
thead → é o cabeçalho da tabela;
th → representa a célula do cabeçalho da tabela;
tbody → representa o corpo da tabela;
tr → é a linha da tabela;
td → representa a célula da tabela;
tfoot → representa o rodapé da tabela. 

*/
```

- `<footer></footer>`
```js
// Rodapé.
```


### CSS

#### FORMAS DE MARCAR UM ELEMENTO


- `De maneira direta`
```js
/* Quando quero selecionar um elemento para aplicar um estilo, eu posso marcálo diretamene pela tag: 
body {
    
}

E neste caso eu aplico todo o estilo que eu colocar dentro das chave spara todos os elementos dentron do body.

*/
```        

- `Classe`
```js
/* Utilizando a classe, eu primeiro marco o meu elemento no HTML e depois utilizo .nomedaclase{}:

.nomeclasse {

}
E aplico o estilo que eu desejo

*/
```  

- `Id`
```js
/* Utilizando o id, primeiro marco o meu elemento no HTML e depois utilizo #nomeid{}:

#nomdeid {

}
E aplico o estilo que eu desejo

*/
```

#### POSSÍVEIS ESTILOS E MEDIÇÕES

- `Estilos mais utilizados neste projeto`
```js
/* 
font-size(tamanhodafonte) → tamanho da fonte em px;

font-weight(pesodafonte) → negrito;

font-family(famíliadafonte) → utilizei neste caso uma fonte extraída do Google Fonts, juntamente com o link HTML:  
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300&display=swap" rel="stylesheet"> | font-family: 'Montserrat', sans-serif;

font-style(estilodefont) → colocar estilo na fonte: italic;

text-align(alinhamentodetexto) → alinhamento no centro, para cima, para baixo, direita, esquerda;

text-decoration(decoraçãodetexto) → formatação de sublinhado (underline, overline , line-through ou blink);

text-transform(transformaçãodotexto) → utilizado para transformar o texto assim que a página carregar: uppercase;

:hover → Possibilita uma transformação no comportamento do elemento assim que o mouse estiver por cima do elemento;

width(comprimento) → definir o comprimento;

margin(margem) → margem externa;

padding(margem) → margem interna;

display(disposição) → disposição do elemento quanto ao espaço ocupado (inline, inline-block, block);

float(flutuação) → Desprendimento do elemento quanto ao fundo: left;

line-height(linhaaltura) → espaçamento entre uma linha e outra: (1.5em/ 1.5 em relação ao padrão);

border(borda) → borda (tamanho, textura e cor);

border-radius → arredondamento de borda: 10px;

*/
```


