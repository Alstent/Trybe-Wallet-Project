# Trybe Wallet Project

  Uma carteira de controle de gastos com conversor de moedas, ao utilizar essa aplicação um usuário deverá ser capaz de:
  - Adicionar, remover e editar um gasto;
  - Visualizar uma tabelas com seus gastos;
  - Visualizar o total de gastos convertidos para uma moeda de escolha;

# Sumário

- [Habilidades](#habilidades)
- [Desenvolvimento](#desenvolvimento)
- [Instruções do projeto](#instruções-do-projeto)
- [Linter](#linter)
- [Documentação da API de Cotações de Moedas](#documentação-da-api-de-cotações-de-moedas)
- [Execução de testes unitários](#execução-de-testes-unitários)
- [Avisos Finais](#avisos-finais)

---

# Habilidades

  * Criar um store Redux em aplicações React

  * Criar reducers no Redux em aplicações React

  * Criar actions no Redux em aplicações React

  * Criar dispatchers no Redux em aplicações React

  * Conectar Redux aos componentes React

  * Criar actions assíncronas na sua aplicação React que faz uso de Redux.

---

# Desenvolvimento

Uma aplicação em React que use Redux como ferramenta de manipulação de estado.

Através dessa aplicação, será possível realizar as operações básicas de criação e manipulação de um estado de redux.

---

# Instruções do projeto

1. Clone ou download o repositório

2. Mude para a branch de desenvolvimento
  * Va para a branch `dev`
    * `git checkout dev`
3. Instale as dependências e inicialize o projeto
  * Instale as dependências:
    * `npm install`
  * Inicialize o projeto:
    * `npm start` (uma nova página deve abrir no seu navegador com um texto simples)
  * Verifique que os testes estão executando:
    * `npm test` (os testes devem rodar e falhar)

---

# Linter

Para garantir a qualidade do código, utilizei neste projeto o linter ESLint. Assim o código estará alinhado com as boas práticas de desenvolvimento, sendo mais legível e de fácil manutenção! Para rodar o *linter* localmente no projeto, execute o comando abaixo: 

`npm run lint`

---

# Documentação da API de Cotações de Moedas

O _site_ irá consumir os dados da API do _awesomeapi API de Cotações_ para realizar a busca de câmbio de moedas. Com o _endpoint_:

- https://economia.awesomeapi.com.br/json/all

Mais sobre a API, poderá encontra na [documentação](https://docs.awesomeapi.com.br/api-de-moedas).

---

# Execução de testes unitários

Utilizei [React Testing Library](https://testing-library.com/docs/react-testing-library/intro) para execução dos testes unitários.

Para rodar todos os testes, basta usar o seguinte código:

```bash
npm test
```

### © Rafael Alstent