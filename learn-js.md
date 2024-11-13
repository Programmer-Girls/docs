# Aprendendo JavaScript

Antes de começar, é importante saber que toda documentação oficial do JavaScript fica no site [MDN Web Docs](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) e a chave para aprender qualquer coisa é ler a documentação oficial da coisa que você quer aprender. Todo guia ou tutorial que você encontrar na internet é uma tentativa de explicar a documentação oficial em um formato mais fácil de entender para as pessoas.

> [!IMPORTANT]
> O site existe em português, mas a documentação oficial é em inglês. Usaremos a versão em inglês por ser mais completa e atualizada.

## Rodando JavaScript

O jeito mais fácil de rodar JavaScript é apertando F12 no seu navegador, acessando a aba "Console" e escrevendo seu código.

![rodando js](assets/images/rodando-js.png)

## [Variáveis e Tipos de Dados](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Data_structures)

### Declaração de Variáveis

As palavras-chave `let`, `const` ou `var` são usadas para declarar variáveis. `var` é a forma antiga de declarar variáveis, `let` e `const` são a forma moderna. `const` é usado para declarar constantes e `let` para declarar variáveis. Por via de regra, **sempre** use `const` e em casos específicos use `let`.

```js
const idade = 20;
let nome = "Alicx";

// Isso é válido
nome = "Alice";

// Isso não é válido e vai dar o erro:
// Uncaught TypeError: Assignment to constant variable.
idade = 21;
```

### Tipos de Dados

No JavaScript existem 7 tipos de dados:

- [undefined](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#undefined_type)
- [null](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#null_type)
- [boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#boolean_type)
- [string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#string_type)
- [number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#number_type)
- [object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#object_type)
- [symbol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#symbol_type)
- [bigint](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#bigint_type)
- [function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

Para checar o tipo de um dado, use a função `typeof`.

![typeof](assets/images/typeof.png)

> [!NOTE]
> Dica da mamãe, não precisa aprender tudo de uma vez, aprenda quando precisar da coisa específica. Só lembre que os tipos existem e quando precisar de algum, aí sim vá ler a documentação oficial.

### Funções

As funções são parecidas com formulas matemáticas. Você passa um valor para a função e ela retorna um valor. Ou uma forma de bolo, você passa os ingredientes e ela retorna o bolo pronto.

```js
// "Declaração de função"
function soma(a, b) {
  return a + b;
}

// "Expressão de função"
const bolo = function () {
  return "🎂";
};

const boloMorango = () => {
  return "🍓🎂";
};

const boloChocolate = () => "🍫🎂";

const boloCustom = (sabor) => sabor + "🎂";

console.log(soma(1, 2)); // 3
console.log(bolo()); // 🎂
console.log(boloChocolate()); // 🍫🎂
console.log(boloMorango()); // 🍓🎂
console.log(boloCustom("🍉")); // 🍉🎂
```

> [!NOTE]
> Se quiser saber a diferença entre declaração e expressão de função, procure `js function declaration vs function expression` no Google.
