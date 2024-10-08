#### Tarefa 02 - Teste de Unidade

#### Nome: Gabriel Wallace Canuto dos Santos
#### Usuário github: Japagabriel
#### E-mail: gcanutosantos@gmail.com

#### Repositório do projeto: https://github.com/GomesLuan/SigBordado


## Testes de Software

Testes de software são cruciais para garantir a qualidade e o funcionamento correto de um sistema. Dentre os diferentes tipos de testes, os testes de unidade se destacam por focarem na verificação de componentes individuais, como funções ou métodos, de forma isolada. Esses testes são realizados durante o desenvolvimento, permitindo a detecção e correção precoce de erros, assegurando que cada parte do código funcione conforme esperado. Além disso, os testes de unidade são geralmente automatizados, o que facilita a verificação rápida de que alterações no código não introduzem novos defeitos, tornando a manutenção e evolução do software mais eficiente.

## Informações do projeto

### Linguagem: Javascript

JavaScript é uma linguagem de programação de alto nível, interpretada e multi-paradigma, amplamente utilizada para o desenvolvimento de páginas web interativas e dinâmicas. Ela pode ser executada tanto no lado do cliente (navegador) quanto no lado do servidor (usando plataformas como Node.js), permitindo a criação de aplicações web completas utilizando uma única linguagem. Além disso, JavaScript suporta operações assíncronas, o que é fundamental no desenvolvimento web para lidar com interações do usuário e solicitações de rede de maneira simultânea e eficiente. A equipe possui conhecimento básico em JavaScript, tendo a utilizado em projetos anteriores na disciplina de Programação Web.

### Linguagem: Python

Python é uma linguagem de programação de alto nível, interpretada e de propósito geral, conhecida por sua simplicidade, legibilidade e facilidade de aprendizado. Python suporta múltiplos paradigmas de programação, como a programação orientada a objetos, imperativa e funcional, oferecendo flexibilidade na abordagem de problemas. A popularidade de Python se deve em grande parte ao seu vasto ecossistema de bibliotecas de terceiros, que aceleram o desenvolvimento de software ao fornecer funcionalidades prontas para uso. A equipe possui um conhecimento intermediário em Python, adquirido em disciplinas como Algoritmos e Lógica de Programação, além de diversos projetos práticos.

### Framework

Para o Frontend, será utilizado o framework ReactJS, amplamente usado para a construção de interfaces de usuário (UI), especialmente em aplicações web. ReactJS é conhecido por sua abordagem de componentização e pela eficiência na atualização do DOM (Document Object Model). No Backend, será utilizado o Django, um framework de desenvolvimento web em Python reconhecido por sua simplicidade, eficiência e escalabilidade.


### Tecnologias

Front-End: ReactJS

Back-End: Django

Banco de dados: Postgres e Docker

## IDE utilizada

Será utilizada a IDE Visual Studio Code, conhecida por sua leveza, rapidez e extensibilidade. O VS Code possui um depurador integrado para debug, permitindo que os desenvolvedores inspecionem variáveis, definam pontos de interrupção, executem passo a passo e monitorem o estado do aplicativo durante a execução. Além disso, a IDE possui integração nativa com o Git, o sistema de controle de versão mais popular. Ele fornece uma interface gráfica para executar operações Git comuns, como commit, pull, push, merge, entre outras. Os desenvolvedores podem visualizar as alterações nos arquivos, comparar versões, e gerenciar branches diretamente no editor.


## Framework: QUnit

QUnit é um framework de testes de unidade em JavaScript amplamente utilizado para testar código JavaScript em navegadores e Node.js. Ele é simples de usar e permite a escrita de testes de forma concisa e legível. Com QUnit, é possível organizar testes em módulos, fornecer asserções claras e detalhadas, e executar testes tanto em ambientes de desenvolvimento quanto de produção. Além disso, QUnit é extensível, suportando a adição de plugins para estender sua funcionalidade conforme necessário.

Mais informações em:  https://qunitjs.com




## Link de Documentação usada para fazer testes na tecnologia escolhida

* [Documentação](https://qunitjs.com/api/)

A documentação oficial do QUnit oferece um guia completo sobre como configurar o ambiente de testes, escrever testes de unidade, e executar testes tanto em navegadores quanto em ambientes de integração contínua. Além disso, são fornecidos exemplos práticos de testes de unidade e de integração, facilitando o aprendizado e a aplicação do framework em diferentes cenários.

## Mocks Objects

Mock Objects são simulacros de objetos reais usados em testes de unidade para isolar o código que está sendo testado. No contexto do QUnit, mocks são frequentemente utilizados para substituir dependências externas, como APIs, serviços ou interações com o DOM, com versões controladas e previsíveis. Isso permite que os testes se concentrem exclusivamente na lógica interna do componente, garantindo que os resultados sejam consistentes e que o comportamento esperado seja verificado de forma precisa. Para facilitar o uso de mocks no QUnit, podem ser utilizados frameworks como Sinon.js, que oferece funcionalidades avançadas para criar e gerenciar mocks, stubs e spies, permitindo uma verificação detalhada das interações dentro dos testes.

## Descrição de CRUD - Manter Funcionário

Um CRUD que implementei foi o de Funcionário, com as operações incluir, consultar, alterar e deletar. Um funcionário armazena informações uma pessoa que trabalha na casa de bordados, que tem acesso ao sistema.

## Implementação dos testes

Implementei testes de unidade para model, serializer e view de Funcionário. De modo geral, os testes tentam realizar as operações básicas do CRUD para conjuntos de dados válidos e inválidos.

Disponível em: https://github.com/GomesLuan/SigBordado/blob/dev/frontend/src/tests.js

## Testes de Integração

Testes de integração são uma etapa do processo de testes de software focada em verificar a interação e integração entre diferentes módulos ou componentes do sistema. Ao contrário dos testes de unidade, que isolam e testam partes individuais do código, os testes de integração verificam se os módulos funcionam corretamente juntos, garantindo que a comunicação, as interfaces e as dependências entre eles estejam funcionando conforme esperado. No projeto, os testes implementados até o momento se concentram principalmente em testes de unidade.