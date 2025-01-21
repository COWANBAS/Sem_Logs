*FUNÇÃO*

UserScript que redefine todas as funções do console do navegador para funções "noop" (no-operation), ou seja, funções que não fazem nada.

![image](https://github.com/user-attachments/assets/168b4989-1e86-4cef-acd1-07f8eac78c86)

*As funções console.log, console.warn, console.error, console.info, console.debug e console.trace são redefinidas para a função noop, que não faz nada.

*Além disso, o script percorre todas as propriedades do objeto console e redefine qualquer propriedade que seja uma função para noop.
Isso efetivamente remove todos os logs do console do navegador, pois qualquer tentativa de usar essas funções de log não produzirá saída alguma.

![image](https://github.com/user-attachments/assets/58d29f95-be52-417f-8c5b-ee745f3725cb)

Isso efetivamente remove todos os logs do console do navegador, pois qualquer tentativa de usar essas funções de log não produzirá saída alguma.
