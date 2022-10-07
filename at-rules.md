# At-rules 

* Está relacionado ao comportamento do css
* Começa com o sinal de '@' seguido do identificador e valor

## Exemplos comuns

- @import       /* incluir um css externo */

- @media        /* regras condicionadas para dispositivos */

- @font-face        /* fontes externas */ 

- @keyframes        /* animation */

ex:

@import "https://local.com/styless.css" ou url("https://local.com/styless.css");

@media (min-width: 500px) {
    /* rules here */
}

@font-face {
    /* rules here */
}

*keyframes nameofanimation {
    /* rules here */
}