# Item 17: Reduza a mutabilidade das classes ao mínimo

## Resumo

## Vantagens

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

## Desvantagens

## Padrões e conceitos

## Itens relacionados


1.	Item 15: Reduza ao mínimo a acessibilidade das classes e de seus membros
2.	Item 16: Use os métodos getters em classes públicas e não os campos públicos
> alteração da representação interna em uma versão posterior (Itens 15 e 16).

3.	Item 50: Faça cópias defensivas quando necessário
> Faça cópias defensivas (Item 50) em construtores, getters e 

4.	Item 88: Escreva métodos readObject defensivamente
> métodos readObject (Item 88)

5.	Item 1: Considere os métodos static factory em vez dos construtores
> Uma classe imutável pode disponibilizar static factories (Item 1)

6.	Item 13: Sobrescreva o clone de modo sensato
> você não precisa e não deve fornecer um método clone ou um construtor de cópia (Item 13)

7.	Item 6: Evite a criação de objetos desnecessários
> String tem um construtor de cópia, mas quase nunca, ou nunca, deve ser usado (Item 6) 
> a.	Nenhuma referência a ele antes

8.	Item 76: Empenhe-se para obter a atomicidade de falha
> Os objetos imutáveis fornecem atomicidade de falha de graça (Item 76). O estado deles nunca muda; desse modo, não há possibilidade de uma inconsistência temporária

9.	Item 83: Utilize a inicialização preguiçosa com parcimônia
> inicialização preguiçosa (Item 83)

10.	Item 67: Seja criterioso ao otimizar
> desempenho satisfatório (Item 67)

## Conclusões 

## Outras referências

* https://refactoring.guru/pt-br/design-patterns/builder
* https://www.zup.com.br/blog/fluent-api