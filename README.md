<a name="readme-top"></a>
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

## About The Project
<div align="center">

  <h3 align="center">
    This repository is only for my studies of the book.
    It contains my notes in my words and not exactly as it is in the book.
  </h3>

  <br />
  <a href="https://github.com/uiratan/book-effective-java">
    <img src="https://m.media-amazon.com/images/I/7167aaVxs3L._SY466_.jpg" alt="Logo" width="120" height="150">
  </a>

  <a href="https://www.amazon.com.br/Effective-Java-3rd-Joshua-Bloch/dp/0134685997">
  <h4 align="center">    
    Effective Java, Third Edition - The definitive guide to Java programming language best practices from Josh Bloch
  </h4>
  </a>
  <br />

</div>

<!-- TABLE OF CONTENTS -->
## Table of Contents

  <ul>
    <li>
      <a href="#create-destroy">2. Criar e Destruir Objetos</a>
      <ul>
        <li><a href="#create-destroy">Item 1: Considere os métodos static factory em vez dos construtores</a></li>
        <li><a href="chapter1/item2">Item 2: Cogite o uso de um builder quando se deparar com muitos parâmetros no construtor</a></li>
        <li><a href="#create-destroy">Item 3: Implemente a propriedade de um singleton com um construtor privado ou um tipo enum</a></li>
        <li><a href="#create-destroy">Item 4: Implemente a não instanciação através de construtores privados</a></li>
        <li><a href="#create-destroy">Item 5: Dê preferência à injeção de dependência para integrar recursos</a></li>
        <li><a href="#create-destroy">Item 6: Evite a criação de objetos desnecessários</a></li>
        <li><a href="#create-destroy">Item 7: Elimine referências obsoletas de objetos</a></li>
        <li><a href="#create-destroy">Item 8: Evite o uso dos finalizadores e dos cleaners</a></li>
        <li><a href="#create-destroy">Item 9: Prefira o uso do try -with-resources ao try - finally</a></li>
      </ul>
    </li>
    <li>
      <a href="#commom-methods">3. Métodos Comuns para Todos os Objetos</a>
      <ul>
        <li><a href="#commom-methods">Item 10: Obedeça ao contrato geral ao sobrescrever o equals</a></li>
        <li><a href="#commom-methods">Item 11: Sobrescreva sempre o método hashCode ao sobrescrever o método equals</a></li>
        <li><a href="#commom-methods">Item 12: Sobrescreva sempre o toString</a></li>
        <li><a href="#commom-methods">Item 13: Sobrescreva o clone de modo sensato</a></li>
        <li><a href="#commom-methods">Item 14: Pense na possibilidade de implementar a Comparable</a></li>
      </ul>
    </li>
    <li>
      <a href="#class-interface">4. Classes e Interfaces</a>
      <ul>
        <li><a href="#class-interface">Item 15: Reduza ao mínimo a acessibilidade das classes e de seus membros</a></li>
        <li><a href="#class-interface">Item 16: Use os métodos getters em classes públicas e não os campos públicos</a></li>
        <li><a href="chapter4/item17">Item 17: Reduza a mutabilidade das classes ao mínimo</a></li>
        <li><a href="#class-interface">Item 18: Prefira a composição à herança</a></li>
        <li><a href="#class-interface">Item 19: Projete e documente as classes para a herança ou a iniba</a></li>
        <li><a href="#class-interface">Item 20: Prefira as interfaces em vez das classes abstratas</a></li>
        <li><a href="#class-interface">Item 21: Projete as interfaces para a posteridade</a></li>
        <li><a href="#class-interface">Item 22: Use as interfaces somente para definir tipos</a></li>
        <li><a href="#class-interface">Item 23: Dê preferência às hierarquias de classes em vez das classes tagged</a></li>
        <li><a href="#class-interface">Item 24: Prefira as classes membro estáticas às não estáticas</a></li>
        <li><a href="#class-interface">Item 25: Limite os arquivos fonte a uma única classe de nível superior</a></li>
      </ul>
    </li>

      5. Genéricos
      Item 26: Não use tipos brutos
      Item 27: Elimine as advertências não verificadas
      Item 28: Prefira as listas aos arrays
      Item 29: Priorize os tipos genéricos
      Item 30: Priorize os métodos genéricos
      Item 31: Use os wildcards limitados para aumentar a flexibilidade da API
      Item 32: Seja criterioso ao combinar os genéricos com os varargs
      Item 33: Pense na possibilidade de usar contêineres heterogêneos typesafe

      6. Enums e Anotações
      Item 34: Use enums em vez de constantes int
      Item 35: Use os campos de instância em vez dos valores ordinais
      Item 36: Use a classe EnumSet em vez dos campos de bits
      Item 37: Use EnumMap em vez da indexação ordinal
      Item 38: Emule enums extensíveis por meio de interfaces
      Item 39: Prefira as anotações aos padrões de nomenclatura
      Item 40: Use a anotação Override com frequência
      Item 41: Use as interfaces marcadoras para definir tipos

      7. Lambdas e Streams
      Item 42: Prefira os lambdas às classes anônimas
      Item 43: Dê preferência às referências para métodos em vez dos lambdas
      Item 44: Prefira o uso das interfaces funcionais padrão
      Item 45: Seja criterioso ao utilizar as streams
      Item 46: Dê preferência às funções sem efeitos colaterais nas streams
      Item 47: Dê preferência à Collection como um tipo de retorno em vez da Stream
      Item 48: Tenha cuidado ao fazer streams paralelas

      8.Métodos
      Item 49: Verifique a validade dos parâmetros
      Item 50: Faça cópias defensivas quando necessário
      Item 51: Projete as assinaturas de método com cuidado
      Item 52: Utilize a sobrecarga com critério
      Item 53: Use os varargs com sabedoria
      Item 54: Retorne coleções ou arrays vazios, em vez de nulos
      Item 55: Seja criterioso ao retornar opcionais
      Item 56: Escreva comentários de documentação para todos os elementos da API
      exposta

      9. Programação Geral
      Item 57: Minimize o escopo das variáveis locais
      Item 58: Dê preferência aos loops for-each em vez dos tradicionais loops for
      Item 59: Conheça e utilize as bibliotecas
      Item 60: Evite o float e o double caso sejam necessárias respostas exatas
      Item 61: Dê preferência aos tipos primitivos em vez dos tipos primitivos
      empacotados
      Item 62: Evite as strings onde outros tipos forem mais adequados
      Item 63: Cuidado com o desempenho da concatenação de strings
      Item 64: Referencie os objetos através das interfaces deles
      Item 65: Dê preferência às interfaces em vez da reflexão
      Item 66: Utilize os métodos nativos com sabedoria
      Item 67: Seja criterioso ao otimizar
      Item 68: Adote as convenções de nomenclatura geralmente aceitas

      10. Exceções
      Item 69: Utilize as exceções somente em circunstâncias excepcionais
      Item 70: Utilize as exceções verificadas para condições recuperáveis e exceções
      de runtime para erros de programação
      Item 71: Evite o uso desnecessário das exceções verificadas
      Item 72: Priorize o uso das exceções padrões
      Item 73: Lance exceções adequadas para a abstração
      Item 74: Documente todas as exceções lançadas por cada método
      Item 75: Inclua as informações a respeito das capturas de falhas nos detalhes da
      mensagem
      Item 76: Empenhe-se para obter a atomicidade de falha
      Item 77: Não ignore as exceções

      11.Concorrência
      Item 78: Sincronize o acesso aos dados mutáveis compartilhados
      Item 79: Evite a sincronização excessiva
      Item 80: Dê preferência aos executores, às tarefas e às streams em vez das
      threads
      Item 81: Prefira os utilitários de concorrência ao wait e ao notify
      Item 82: Documente a thread safety
      Item 83: Utilize a inicialização preguiçosa com parcimônia
      Item 84: Não dependa do agendador de threads

      12. Serialização
      Item 85: Prefira alternativas à serialização Java
      Item 86: Tenha cautela ao implementar a Serializable
      Item 87: Pense na possibilidade de usar uma forma serializada customizada
      Item 88: Escreva métodos readObject defensivamente
      Item 89: Dê preferência aos tipos enum em vez do readResolve para controle
      de instância
      Item 90: Pense em usar proxies de serialização em vez de instâncias serializadas

  </ul>




### Built With

<!-- GETTING STARTED -->
## Getting Started


### Prerequisites


### Installation




<!-- ROADMAP -->
## Roadmap

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
