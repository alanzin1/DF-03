# Sistema de Jogo de Heróis

Este é um sistema simples em JavaScript que simula um jogo de aventura, onde diferentes tipos de heróis podem atacar usando habilidades específicas. O sistema é baseado em **classes e objetos**, com o objetivo de ensinar conceitos de programação como **variáveis**, **estruturas de decisão**, **laços de repetição**, **funções**, e **classes**.

## Funcionalidade

A classe `Heroi` representa um herói de aventura, e cada herói possui três propriedades principais:
- `nome`: O nome do herói.
- `idade`: A idade do herói.
- `tipo`: O tipo do herói (guerreiro, mago, monge e ninja).

Além disso, a classe possui o método `atacar()`, que realiza um ataque de acordo com o tipo de herói. Dependendo do tipo, o ataque varia:
- **Mago**: Usará magia.
- **Guerreiro**: Usará espada.
- **Monge**: Usará artes marciais.
- **Ninja**: Usará shuriken.
