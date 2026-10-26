# Portfólio de Quality Assurance (QA)

Este repositório reúne projetos, exercícios e desafios práticos desenvolvidos durante meus estudos de **Quality Assurance (QA)** na EBAC — Escola Britânica de Artes Criativas e Tecnologia. Ele funciona como um índice para explorar cada trabalho por área técnica.

> **Nota:** os projetos são atividades de estudo e prática. A presença de uma tecnologia neste portfólio não significa, por si só, experiência profissional ou uso em produção. Consulte o README de cada repositório para detalhes, pré-requisitos e instruções de execução.

## Objetivos

- Centralizar os projetos e facilitar a navegação entre os repositórios.
- Demonstrar a aplicação prática de conceitos de testes, automação, performance, dados e CI/CD.
- Documentar o objetivo e o escopo de cada atividade com descrições objetivas.
- Manter os trabalhos versionados e disponíveis para consulta.

## Estrutura

```text
Portfólio QA
├── Automação Web e BDD
├── Testes de API
├── Testes de Unidade
├── Testes de Performance
├── Automação Mobile
├── CI/CD e Containers
├── Bancos de Dados e Versionamento
└── Ferramentas de apoio e portfólio
```

## Projetos

### 1. Automação de testes de interface (UI)

- **[cypress-ui-automation](https://github.com/Nickgdm/cypress-ui-automation)**  
  Projeto de testes E2E para a interface do Hub de Leitura com Cypress e JavaScript. Inclui configuração de testes e arquivos relacionados à execução em pipeline.

- **[cypress-ui-automation-task](https://github.com/Nickgdm/cypress-ui-automation-task)**  
  Atividade prática de automação da interface do Hub de Leitura com Cypress, com cenários e verificações de comportamento da aplicação.

- **[cypress-intercept-app-actions](https://github.com/Nickgdm/cypress-intercept-app-actions)**  
  Exercício de recursos avançados do Cypress, com interceptação de chamadas de rede e uso de App Actions para interagir com a aplicação durante os testes.

### 2. Testes de API REST

- **[cypress-api-testing](https://github.com/Nickgdm/cypress-api-testing)**  
  Testes automatizados de API do Hub de Leitura com Cypress, cobrindo requisições HTTP como GET, POST, PUT e DELETE e validações de status e conteúdo das respostas.

- **[cypress-api-testing-task](https://github.com/Nickgdm/cypress-api-testing-task)**  
  Atividade prática de testes de API REST. Consulte os arquivos do repositório para conferir os endpoints e cenários efetivamente implementados.

- **[book-catalog-api-postman](https://github.com/Nickgdm/book-catalog-api-postman)**  
  Coleção e ambiente do Postman para enviar requisições a uma API de catálogo de livros, trabalhar com variáveis e validar códigos de status e respostas JSON.

### 3. BDD e Gherkin

- **[cypress-cucumber-bdd](https://github.com/Nickgdm/cypress-cucumber-bdd)**  
  Projeto que combina Cypress com Cucumber/Gherkin para estruturar testes de interface em cenários orientados a comportamento. Também inclui arquivos relacionados a relatórios e pipeline.

- **[ebac-bdd-gherkin-scenarios](https://github.com/Nickgdm/ebac-bdd-gherkin-scenarios)**  
  Cenários escritos em Gherkin para fluxos como cadastro, configuração e login. O foco está na especificação legível dos comportamentos esperados; verifique o conteúdo do repositório para distinguir especificações de testes executáveis.

### 4. Testes de unidade

- **[javascript-jest-unit-tests](https://github.com/Nickgdm/javascript-jest-unit-tests)**  
  Exercícios de testes unitários em JavaScript com Jest, voltados à validação de funções de cadastro e à análise de cenários e cobertura de código, incluindo conceitos de teste de caixa branca.

### 5. Testes de performance

- **[hub-de-leitura-k6-performance](https://github.com/Nickgdm/hub-de-leitura-k6-performance)**  
  Scripts de performance para a API do Hub de Leitura com k6. Inclui cenários de carga e estresse e geração de relatórios para análise dos resultados.

- **[blazedemo-jmeter-performance](https://github.com/Nickgdm/blazedemo-jmeter-performance)**  
  Plano de teste com Apache JMeter para exercitar a busca de voos no BlazeDemo, usando dados CSV e configuração de usuários virtuais, ramp-up e duração do teste.

### 6. Automação mobile

- **[appium-webdriverio-mobile-tests](https://github.com/Nickgdm/appium-webdriverio-mobile-tests)**  
  Exercícios de automação mobile com Appium e WebdriverIO em JavaScript, incluindo um cenário de Drag and Drop na Native Demo App para Android.

### 7. Integração contínua (CI/CD)

- **[jenkins-cypress-ci-pipeline](https://github.com/Nickgdm/jenkins-cypress-ci-pipeline)**  
  Pipelines Jenkins para executar conjuntos de testes Cypress, com execução paralela e integração com Allure. O repositório contém arquivos de pipeline para ambientes distintos.

- **[jenkins-docker-cypress-pipeline](https://github.com/Nickgdm/jenkins-docker-cypress-pipeline)**  
  Exemplo de integração entre Jenkins, Docker e Cypress para organizar a execução automatizada de testes em pipeline. Consulte o README para configuração e requisitos do ambiente.

### 8. Docker e ambientes de teste

- **[golden-movie-studio-docker-e2e](https://github.com/Nickgdm/golden-movie-studio-docker-e2e)**  
  Ambiente com Docker Compose para executar os serviços do Golden Movie Studio e testes E2E com Cypress, incluindo armazenamento de vídeos e capturas de tela de execução.

- **[hub-de-leitura-docker-compose](https://github.com/Nickgdm/hub-de-leitura-docker-compose)**  
  Configuração com Docker Compose para integrar a aplicação Hub de Leitura e os testes de interface, facilitando a preparação do ambiente de execução.

### 9. Bancos de dados

- **[sql-query-practice](https://github.com/Nickgdm/sql-query-practice)**  
  Exercícios de SQL com o banco de exemplo Chinook, incluindo consultas, filtros, ordenação, junções, agregações e pesquisa textual.

- **[mongodb-nosql-practice](https://github.com/Nickgdm/mongodb-nosql-practice)**  
  Prática de consultas MongoDB usando dados de exemplo de estudantes e professores, com filtros, projeções, ordenação, expressões regulares e agregações.

### 10. Versionamento e Git

- **[git-github-practice](https://github.com/Nickgdm/git-github-practice)**  
  Exercício introdutório de Git e GitHub para praticar edição de arquivos, commits e envio de alterações para um repositório remoto.

### 11. Aplicação usada em atividades de QA

- **[hub-de-leitura-application](https://github.com/Nickgdm/hub-de-leitura-application)**  
  Aplicação educacional de gerenciamento de biblioteca, construída com tecnologias web e utilizada como base para exercícios de testes e automação.

### 12. Ferramenta de apoio a QA com IA

- **[qa-prompt-assistant](https://github.com/Nickgdm/qa-prompt-assistant)**  
  Ferramenta de linha de comando em Python para apoiar tarefas de QA, como criação de casos de teste, análise de requisitos e elaboração de relatos de bugs. Integra provedores de IA e modelos locais; as sugestões precisam ser revisadas por uma pessoa.

### 13. Índices e apresentação do portfólio

- **[qa-toolbox](https://github.com/Nickgdm/qa-toolbox)**  
  Índice de projetos de QA organizado por categorias técnicas, com links para os repositórios relacionados.

- **[Nickgdm.github.io](https://github.com/Nickgdm/Nickgdm.github.io)**  
  Site de portfólio desenvolvido com HTML, CSS e JavaScript para apresentar projetos, links profissionais e recursos de navegação, publicado por meio do GitHub Pages.

- **[Nickgdm](https://github.com/Nickgdm/Nickgdm)**  
  Repositório de perfil do GitHub, com apresentação dos estudos em QA, áreas de interesse e links para projetos.

## Tecnologias e ferramentas

Conforme o projeto, o portfólio utiliza ou explora JavaScript, Node.js, Cypress, Jest, Postman, Appium, WebdriverIO, Cucumber/Gherkin, k6, Apache JMeter, SQL, MongoDB, Docker, Docker Compose, Jenkins, Allure e ferramentas de IA.

## Como explorar os projetos

1. Escolha a categoria de interesse e abra o repositório.
2. Leia o README específico antes de executar qualquer atividade.
3. Confira os pré-requisitos, dependências, variáveis de ambiente e comandos disponíveis.
4. Examine os cenários, testes, arquivos de configuração e evidências existentes.
5. Considere que os requisitos e o nível de implementação variam de um projeto para outro.

## Desafios práticos

Os projetos permitem exercitar diferentes etapas do trabalho de QA: interpretar requisitos, definir cenários, verificar interfaces e APIs, criar testes automatizados, preparar ambientes, observar resultados e documentar procedimentos. O escopo de cada desafio está descrito no respectivo repositório.

## Boas práticas

- Organização dos projetos por área técnica.
- Documentação em Markdown e links diretos para os repositórios.
- Versionamento dos trabalhos com Git e GitHub.
- Descrições alinhadas ao conteúdo disponível, sem presumir funcionalidades não demonstradas.
- Revisão humana dos resultados produzidos por ferramentas de automação e inteligência artificial.

## 📚 Aprendizados

A construção do portfólio reúne práticas de automação web, testes de API e unidade, BDD, performance, automação mobile, bancos de dados, containers e CI/CD. Também reforça a importância de documentar o objetivo, os requisitos e as limitações de cada projeto para facilitar sua análise e reprodução.

## Considerações finais

Este repositório é o ponto de entrada para os projetos desenvolvidos durante meus estudos de QA. Os trabalhos estão distribuídos em repositórios independentes e podem evoluir conforme novas atividades, revisões e melhorias forem realizadas.

---

## 🎓 Formação

Projetos desenvolvidos durante os estudos de **Quality Assurance (QA) na EBAC — Escola Britânica de Artes Criativas e Tecnologia**.
