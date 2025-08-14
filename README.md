# Desafio DIO - Classe de Herói

Projeto em JavaScript para criar uma classe de herói com propriedades e ataques diferentes de acordo com o tipo.

## Propriedades
- nome
- idade
- tipo (guerreiro, mago, monge, ninja)

## Método
**atacar()** → exibe:  
`O {tipo} atacou usando {ataque}`

Tipos de ataque:
- mago → magia  
- guerreiro → espada  
- monge → artes marciais  
- ninja → shuriken  

## Exemplo de uso
```javascript
const heroi1 = new Heroi('Arthas', 30, 'guerreiro');
heroi1.atacar(); // O guerreiro atacou usando espada
