# Portfólio de Quality Assurance (QA)

Este repositório reúne projetos, exercícios e desafios práticos desenvolvidos durante meus estudos de **Quality Assurance (QA) na EBAC — Escola Britânica de Artes Criativas e Tecnologia**. A organização segue as áreas técnicas propostas no projeto final do curso e facilita a consulta dos trabalhos por recrutadores e profissionais de tecnologia.

> **Nota:** os projetos fazem parte de atividades de estudo e prática. A presença de uma ferramenta neste portfólio não significa experiência profissional ou uso em produção. O escopo e o nível de implementação variam entre os repositórios; consulte o README de cada projeto para conhecer seus requisitos e instruções.

## 📂 Projetos

### 1. Automação de UI com Cypress

Automação de testes de interface e fluxos de usuário usando Cypress e JavaScript.

- **[cypress-ui-automation](https://github.com/Nickgdm/cypress-ui-automation)** — testes E2E para a interface do Hub de Leitura, com configuração de testes e arquivos relacionados à execução em pipeline.
- **[cypress-ui-automation-task](https://github.com/Nickgdm/cypress-ui-automation-task)** — atividade prática de automação da interface do Hub de Leitura, com cenários e verificações do comportamento da aplicação.

### 2. Testes Automatizados de API REST

Testes de endpoints HTTP e validação de respostas de APIs, utilizando ferramentas de automação e clientes de API.

- **[cypress-api-testing](https://github.com/Nickgdm/cypress-api-testing)** — testes automatizados da API do Hub de Leitura com Cypress, incluindo requisições GET, POST, PUT e DELETE e validações das respostas.
- **[cypress-api-testing-task](https://github.com/Nickgdm/cypress-api-testing-task)** — atividade prática de testes de API REST; consulte os arquivos do projeto para identificar os endpoints e cenários implementados.
- **[book-catalog-api-postman](https://github.com/Nickgdm/book-catalog-api-postman)** — coleção e ambiente do Postman para realizar requisições a uma API de catálogo de livros e verificar códigos de status e respostas JSON.

### 3. DevOps — Integração Contínua (CI/CD)

Exemplos de integração de testes automatizados em pipelines para organizar e repetir execuções.

- **[jenkins-cypress-ci-pipeline](https://github.com/Nickgdm/jenkins-cypress-ci-pipeline)** — pipelines Jenkins para executar testes Cypress, incluindo arquivos relacionados à execução paralela e relatórios Allure.
- **[jenkins-docker-cypress-pipeline](https://github.com/Nickgdm/jenkins-docker-cypress-pipeline)** — exemplo de integração entre Jenkins, Docker e Cypress para execução de testes em pipeline.

### 4. Projeto com Docker

Uso de containers para preparar e executar aplicações e testes em ambientes definidos por configuração.

- **[golden-movie-studio-docker-e2e](https://github.com/Nickgdm/golden-movie-studio-docker-e2e)** — configuração com Docker Compose para executar os serviços do Golden Movie Studio e testes E2E com Cypress.
- **[hub-de-leitura-docker-compose](https://github.com/Nickgdm/hub-de-leitura-docker-compose)** — configuração Docker Compose para integrar a aplicação Hub de Leitura e os testes de interface.

### 5. Automação de UI com Cypress — Avançado

Projetos e exercícios relacionados a BDD, Gherkin, interceptação de chamadas de rede e organização de testes por comportamento.

- **[cypress-cucumber-bdd](https://github.com/Nickgdm/cypress-cucumber-bdd)** — integração de Cypress com Cucumber/Gherkin para estruturar cenários orientados a comportamento.
- **[ebac-bdd-gherkin-scenarios](https://github.com/Nickgdm/ebac-bdd-gherkin-scenarios)** — especificações de cenários em Gherkin para fluxos como cadastro, configuração e login; verifique no repositório quais itens são especificações e quais são testes executáveis.
- **[cypress-intercept-app-actions](https://github.com/Nickgdm/cypress-intercept-app-actions)** — exercícios com interceptação de chamadas de rede e App Actions para interagir com a aplicação durante os testes.

### 6. Testes de Performance

Exercícios de carga e performance para observar o comportamento de aplicações e APIs sob diferentes condições.

- **[blazedemo-jmeter-performance](https://github.com/Nickgdm/blazedemo-jmeter-performance)** — plano de teste com Apache JMeter para exercitar a busca de voos no BlazeDemo, com dados CSV e configuração de usuários virtuais.
- **[hub-de-leitura-k6-performance](https://github.com/Nickgdm/hub-de-leitura-k6-performance)** — scripts de performance para a API do Hub de Leitura com k6, incluindo cenários de carga e estresse.

### 7. Automação Mobile com Appium

Prática de automação de testes em dispositivos ou aplicações Android com Appium e ferramentas do ecossistema WebdriverIO.

- **[appium-webdriverio-mobile-tests](https://github.com/Nickgdm/appium-webdriverio-mobile-tests)** — exercícios em JavaScript com Appium e WebdriverIO, incluindo um cenário de Drag and Drop na Native Demo App para Android.

### 8. Testes de Unidade com JavaScript

Prática de testes unitários para verificar funções e comportamentos específicos do código.

- **[javascript-jest-unit-tests](https://github.com/Nickgdm/javascript-jest-unit-tests)** — exercícios de testes unitários com Jest, voltados à validação de funções de cadastro e à análise de cenários e cobertura de código, incluindo conceitos de teste de caixa branca.

### 9. Testes com Inteligência Artificial

Exploração de IA como ferramenta auxiliar no trabalho de QA, com revisão humana dos resultados gerados.

- **[qa-prompt-assistant](https://github.com/Nickgdm/qa-prompt-assistant)** — ferramenta de linha de comando em Python para apoiar tarefas como criação de casos de teste, análise de requisitos e elaboração de relatos de bugs. As sugestões produzidas por IA devem ser revisadas antes de serem utilizadas.

## 📚 Projetos complementares

Estes repositórios complementam a formação com exercícios de dados, versionamento, aplicação de teste e apresentação dos trabalhos.

- **[sql-query-practice](https://github.com/Nickgdm/sql-query-practice)** — exercícios de SQL com o banco de exemplo Chinook, incluindo filtros, ordenação, junções e agregações.
- **[mongodb-nosql-practice](https://github.com/Nickgdm/mongodb-nosql-practice)** — prática de consultas MongoDB com filtros, projeções, ordenação, expressões regulares e agregações.
- **[git-github-practice](https://github.com/Nickgdm/git-github-practice)** — exercícios introdutórios de Git e GitHub para praticar commits e envio de alterações para um repositório remoto.
- **[hub-de-leitura-application](https://github.com/Nickgdm/hub-de-leitura-application)** — aplicação educacional de gerenciamento de biblioteca utilizada como base para atividades de teste e automação.
- **[qa-toolbox](https://github.com/Nickgdm/qa-toolbox)** — índice complementar de projetos de QA organizado por categorias técnicas.
- **[Nickgdm.github.io](https://github.com/Nickgdm/Nickgdm.github.io)** — site de portfólio para apresentar projetos e links.
- **[Nickgdm](https://github.com/Nickgdm/Nickgdm)** — repositório de apresentação do perfil GitHub.

## 🧰 Tecnologias e ferramentas

Conforme o projeto, são explorados JavaScript, Node.js, Cypress, Jest, Postman, Appium, WebdriverIO, Cucumber/Gherkin, k6, Apache JMeter, SQL, MongoDB, Docker, Docker Compose, Jenkins, Allure, Python e ferramentas de IA.

## ▶️ Como explorar e executar os projetos

1. Abra o repositório do projeto desejado pelos links acima.
2. Leia o README específico para conhecer o objetivo, os pré-requisitos e as instruções de instalação.
3. Instale as dependências e configure variáveis de ambiente, quando necessário.
4. Execute os comandos descritos no README do projeto.
5. Consulte os testes, configurações, relatórios e evidências disponíveis no repositório.

Os comandos e pré-requisitos podem variar entre projetos; siga sempre a documentação de cada repositório.

## 🧪 Desafios práticos

Os projetos permitem praticar diferentes etapas do trabalho de QA: compreender requisitos, definir cenários, validar interfaces e APIs, automatizar testes, preparar ambientes, analisar resultados e documentar procedimentos. O escopo de cada desafio deve ser conferido no respectivo repositório.

## ✅ Boas práticas adotadas

- Organização dos projetos por área técnica.
- Documentação em Markdown e links diretos para os repositórios.
- Versionamento dos trabalhos com Git e GitHub.
- Descrições alinhadas ao conteúdo de cada projeto, sem presumir funcionalidades não demonstradas.
- Revisão humana dos resultados produzidos por ferramentas de automação e inteligência artificial.

## 📖 Aprendizados

A construção deste portfólio reúne práticas de automação web, testes de API e unidade, BDD, performance, automação mobile, bancos de dados, containers e CI/CD. Também reforça a importância de registrar objetivos, requisitos, limitações e procedimentos para facilitar a análise e a reprodução dos testes.

## 🎓 Formação

Projetos desenvolvidos durante os estudos de **Quality Assurance (QA) na EBAC — Escola Britânica de Artes Criativas e Tecnologia**.

---

Este portfólio é um trabalho de estudo em evolução e poderá ser ampliado conforme novos projetos e melhorias forem realizados.
