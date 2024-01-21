# HORARIO ATUAL
⏰EXIBE O HORÁRIO ATUAL JUNTO COM A INTERFACE CORRESPODENTE. 

<img src="FOTO.png" align="center" width="500"> <br>

## DESCRIÇÃO:
Esse código HTML, CSS e JavaScript cria uma página simples que exibe informações sobre o horário atual e uma imagem correspondente à parte do dia (manhã, tarde ou noite). Vamos analisar cada parte:

1. **HTML:**
   - A página HTML contém uma estrutura básica com as tags `<html>`, `<head>`, `<meta>`, `<title>`, `<script>`, `<link>`, `<body>`, `<header>`, `<section>`, `<div>`, `<img>`, e `<footer>`.
   - O JavaScript (`CODIGO.js`) é vinculado na seção `<head>`, e o CSS (`CODIGO.css`) é vinculado abaixo do script.
   - O corpo da página contém um cabeçalho (`<header>`), uma seção (`<section>`) dividida em duas partes (`<div id="msg">` e `<div id="imagem">`), e um rodapé (`<footer>`).

2. **CSS (`CODIGO.css`):**
   - Define estilos de formatação para o corpo da página, cabeçalho, seção, divs, imagens e rodapé.
   - Configura um plano de fundo azul para o corpo da página, estilos de texto e outras propriedades visuais.

3. **JavaScript (`CODIGO.js`):**
   - A função `carregar()` é chamada quando a página é carregada (`onload="carregar()"`).
   - Dentro da função, é obtida a referência ao elemento com o id 'msg'.
   - A hora atual é obtida usando `new Date()`, e a mensagem é atualizada para mostrar o horário atual no formato "AGORA SÃO horas:minutos".
   - Com base na hora atual, são feitas condições para determinar se é manhã, tarde ou noite. Dependendo do período, a visibilidade das imagens (`MANHA`, `TARDE` e `NOITE`) e a cor de fundo do corpo da página são ajustadas.

4. **Imagens:**
   - O código HTML contém três imagens (`MANHA.jpg`, `TARDE.jpg` e `NOITE.jpg`) dentro da `<div id="imagem">`. Essas imagens representam diferentes partes do dia.

5. **Estilos visuais:**
   - As definições visuais incluem cores de fundo, fontes e outros estilos que proporcionam uma aparência agradável à página.

Em resumo, este código cria uma página que exibe a hora atual, determina se é manhã, tarde ou noite, e exibe uma imagem correspondente a essa parte do dia, além de aplicar estilos visuais para melhorar a apresentação da página.

## COMO USAR?
* Clone o repositório para o seu sistema local:

```bash
git clone https://github.com/VILHALVA/HORARIO-ATUAL.git
```

* Navegue até o diretório do projeto.

```bash
cd HORARIO-ATUAL
```

* Descompacte o arquivo ZIP (se você baixou manualmente):

```bash
unzip HORARIO-ATUAL.zip
```
* Abra o arquivo `CODIGO.html` em seu navegador de preferência.

## NÃO SABE?
- Entendemos que para manipular arquivos em `HTML`, `CSS` e outras linguagens relacionadas, é necessário possuir conhecimento nessas áreas. Para auxiliar nesse aprendizado, oferecemos cursos gratuitos disponíveis:
* [Curso de HTML e CSS](https://github.com/VILHALVA/CURSO-DE-HTML-E-CSS)
* [Curso de JavaScript](https://github.com/VILHALVA/CURSO-DE-JAVASCRIPT)
* [Confira mais cursos](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)

## CREDITOS:
- [PROJETO CRIADO PELO VILHALVA](https://github.com/VILHALVA)

