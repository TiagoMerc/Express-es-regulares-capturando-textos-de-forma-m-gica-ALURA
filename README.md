## Curso de Expressões regulares: capturando textos de forma mágica |ALURA

Faça esse curso de JavaScript e:

 - Entenda o que são expressões regulares
 - Valide formulários HTML
 - Aprenda a identificar CPF, CEP, emails e outros documentos
 - Crie expressões regulares eficientes
 - Use classes, âncoras, quantifiers e grupos
 - Execute expressões regulares na sua linguagem

### 01. Começando com Regex

Pesquisando CPF | Expressão regular
\d\d\d\.\d\d\d\.\d\d\d-\d\d

quantifer
\d{3}\.\d{3}\.\d{3}-\d{2}

O que aprendemos?

- Regex, ou expressões regulares, é uma linguagem para encontrar padrões de texto.

- Sendo uma linguagem independente, existem interpretadores para a maioria das plataformas de desenvolvimento, como JavaScript, C#, Python ou Ruby.

- Uma classe de caracteres predefinida é **\d**, que significa qualquer dígito.

- Existem vários meta-char, como **.** ou *****.

- Existem quantifiers que definem quantas vezes um caractere deve aparecer:
  - {1} é um quantifier que significa uma vez.
  - * é um quantifier que significa zero, uma ou mais vezes

- . é um meta-char que significa qualquer char.

- Com \ podemos escapar meta-chars, por exemplo \..

**Encontrando o CEP**

![Encontrando o CEP](./imgs/prints/EncontrandoCEP.png)

### 02. Classes de caracteres 
