# HTML5 - 14/02/2019(Quiinta-Feira)

## Tópicos estudados:

- O que é HTML5;
- HTML vs HTML5;
- O que são tags, elementos e atributos;
- tags principais;
- Estrutura;
- Semântica;
- Referência;
- Exercício;
- Estudos em casa.


<hr/>

## HTML5

Segundo a Wikipédia, HTML5 (Hypertext Markup Language, versão 5) é uma linguagem de marcação para a World Wide Web (WWW) e é uma tecnologia chave da Internet.<br/>
[...] adiciona várias novas funções sintáticas. [...] novos elementos, como `<section>`, `<article>`, `<header>` e `<nav>`, são projetados para enriquecer o conteúdo semântico dos documentos.
<hr/>

## HTML vs HTML5

Em virtude da semântica da nova versão do HTML, muitas tags passaram a ser depreciadas e novas tags, como citado acima, passaram a ter um grande valor semântico no documento. (Referências no final do Readme).
<hr/>

## O que são tags, elementos e atributos

" **TAGS** são rótulos usados para informar ao navegador como  deve ser apresentado o site. Ou seja, quando começo a escrever **HTML**  estou escrevendo tags que serão interpretadas pelo navegador, produzindo assim o visual do seu site. "

"**Elementos** são formados a partir de Tags e entre as Tags é que está o conteúdo do Elemento.
Se quisermos exibir um parágrafo em um site utilizamos a Tag `<p>` que semanticamente quer dizer que o conteúdo que se espera nesse Elemento é um parágrafo."

"**Atributos** são informações que passamos na Tag para que ela se comporte da maneira esperada. Existem atributos globais (que funcionam em todas as Tags) e específicos (que são direcionados para cada Tag, através de especificação).
Os Atributos possuem nome e um valor, existem Atributos que você vai usar praticamente sempre e existem outros que serão mais raros."

> **Atenção:**
Não confunda Tags com Elementos<br/>
As Tags servem para marcar onde começam e terminam os Elementos. Já os Elementos são uma parte conceitual/semântica que têm um começo e fim determinados. Parece uma diferença boba, mas mantenha ela sempre em mente e isso vai fazer toda a diferença no seu entendimento de HTML.
<hr/>

## Tags Principais e Estrutura
```
<!DOCTYPE html>
<html>
<head>
    <title> My Title </title>
</head>
<body>
    <h1>My First Heading</h1>

    <p>My first paragraph.</p>

</body>
</html>
```
<hr/>

## Semântica

Segundo W3Schools, semântica é o estudo dos significados de palavras e frases em uma linguagem. Elementos semânticos = elementos com um significado.
<hr/>



## Referências
HTML5Doctor: [http://html5doctor.com/](http://html5doctor.com/)<br/>
W3Schools: [https://www.w3schools.com/html/default.asp](https://www.w3schools.com/html/default.asp)<br/>
Devmedia: [https://www.devmedia.com.br/comandos-e-tags-html5/23618](https://www.devmedia.com.br/comandos-e-tags-html5/23618)<br/>
CursosWL: [https://www.cursos.wlconsultoria.net/blog/o-que-sao-tags-html/](https://www.cursos.wlconsultoria.net/blog/o-que-sao-tags-html/)<br/>
GETTING STARTED, um guia para iniciantes na área de web: [http://tableless.github.io/iniciantes/manual/html/oquetags.html](http://tableless.github.io/iniciantes/manual/html/oquetags.html)

## Exercicio

<a href="[Exercício] Página HTML - Receita de bolo.pdf" download style="border: solid 2px black; border-radius: 20px; padding: 10px; color: black; text-decoration: none;">Clique aqui para baixar o PDF</a>

*Após o download do PDF, siga as instruções e, com o auxílio das referências, replique a receita de bolo em HTML5 semânticamente correto.*

## Estudos em casa😁📚

Responda em uma folha
1. Com suas palavras, o que é escrever um código HTML semânticamente correto?
2. Por que, nos dias atuais é tão importante que seus códigos sejam semânticos?
3. Se eu desejo dar ênfase no nome do site, qual tag é mais apropriada para colocá-lo?
4. Qual dessas tags está depreciada:<br/> 
`<strong>`<br/>
`<b>`<br/>
`<figure>`<br/>
`<section>`
5. Qual o significado semântico das tags `<div>` e `<span>`?