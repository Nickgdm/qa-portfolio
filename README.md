# Portfólio de Quality Assurance (QA)

Este repositório reúne projetos e desafios práticos desenvolvidos durante a formação em **Quality Assurance (QA) pela EBAC — Escola Britânica de Artes Criativas e Tecnologia**. O objetivo é centralizar os trabalhos em um único ponto de entrada, facilitando a navegação por área técnica e a consulta aos arquivos de cada projeto.

> **Sobre o portfólio:** os links abaixo direcionam para repositórios independentes. São atividades de estudo e prática; a inclusão de uma ferramenta indica que ela faz parte do projeto relacionado, não uma experiência profissional ou uso em produção. Consulte o README de cada repositório para conhecer o escopo, os pré-requisitos e as instruções de execução.

## Objetivo do portfólio

- Organizar os projetos desenvolvidos ao longo do curso.
- Facilitar a consulta ao código, aos cenários de teste e às configurações de cada atividade.
- Demonstrar a aplicação prática dos conceitos estudados em QA, automação, performance, integração contínua e documentação.
- Manter uma apresentação clara, navegável e versionada dos trabalhos.

## Estrutura do portfólio

A organização segue as categorias sugeridas na atividade final da formação. Como os projetos estão em repositórios GitHub separados, os links abaixo funcionam como índice central.

```text
Portfólio QA
├── Projetos
│   ├── Automação Web
│   ├── Automação de API
│   ├── Testes de Unidade
│   ├── Testes de Performance
│   └── CI/CD e Qualidade Contínua
├── Desafios práticos
├── Boas práticas adotadas
└── Considerações finais
```

## Projetos

### 1. Automação de UI com Cypress

Projetos voltados à automação de fluxos de interface web com Cypress e Node.js.

- [teste-cy-base](https://github.com/Nickgdm/teste-cy-base) — aplicação utilizada como base para atividades de QA.
- [hub-de-leitura-teste-ui](https://github.com/Nickgdm/hub-de-leitura-teste-ui) — cenários de automação da interface.
- [Atividade-hub-de-leitura-teste-ui-task](https://github.com/Nickgdm/Atividade-hub-de-leitura-teste-ui-task) — atividade prática de testes de interface.

### 2. Testes Automatizados de API REST

Projetos para exercitar requisições HTTP, validação de endpoints e respostas de APIs.

- [hub-de-leitura-api-teste](https://github.com/Nickgdm/hub-de-leitura-api-teste) — automação de testes de API.
- [hub-de-leitura-api-teste-task](https://github.com/Nickgdm/hub-de-leitura-api-teste-task) — atividade prática de testes de API REST.
- [atividade-API-Ebac](https://github.com/Nickgdm/atividade-API-Ebac) — coleção de requisições para explorar e validar a API do catálogo de livros.

### 3. DevOps — CI/CD e Qualidade Contínua

Atividades que exploram pipelines e integração da execução de testes ao fluxo de desenvolvimento.

- [ci-cd-teste-jenkins](https://github.com/Nickgdm/ci-cd-teste-jenkins) — configuração de pipeline com Jenkins.
- [atividade-ci-cd-teste-exemplo](https://github.com/Nickgdm/atividade-ci-cd-teste-exemplo) — arquivos relacionados à integração e execução de testes.
- [Atividade-cucumber-cypress](https://github.com/Nickgdm/Atividade-cucumber-cypress) — projeto de BDD que também contém um Jenkinsfile.

### 4. Projeto com Docker

Projetos que utilizam containers para configurar aplicações e/ou executar testes em ambientes definidos.

- [atividade-docker](https://github.com/Nickgdm/atividade-docker) — ambiente com serviços de aplicação e testes Cypress.
- [atividade-docker-hub-de-leitura](https://github.com/Nickgdm/atividade-docker-hub-de-leitura) — configuração de ambiente para a aplicação e os testes de UI.

### 5. Automação de UI com Cypress — Avançado

Exercícios com recursos avançados do Cypress e/ou especificação de cenários com BDD.

- [Atividade-Intercept-AppActions-cypress](https://github.com/Nickgdm/Atividade-Intercept-AppActions-cypress) — prática com interceptação de chamadas e ações da aplicação.
- [Atividade-cucumber-cypress](https://github.com/Nickgdm/Atividade-cucumber-cypress) — cenários escritos com Gherkin e abordagem orientada a comportamento.

### 6. Testes de Performance

Projetos para praticar testes de carga e estresse e observar métricas de desempenho.

- [atividade-k6](https://github.com/Nickgdm/atividade-k6) — scripts de teste de performance.
- [atividade-jmeter-blazedemo](https://github.com/Nickgdm/atividade-jmeter-blazedemo) — plano e configuração de testes com JMeter.

### 7. Automação Mobile com Appium

- [atividade-appium-wdio](https://github.com/Nickgdm/atividade-appium-wdio) — projeto de automação mobile com cenários voltados a Android.

### 8. Testes de Unidade com JavaScript

- [atividade-exercicio-js](https://github.com/Nickgdm/atividade-exercicio-js) — exercícios de testes unitários e cobertura de código.

### 9. Testes com Inteligência Artificial

- [qa-prompt-assistant](https://github.com/Nickgdm/qa-prompt-assistant) — ferramenta de terminal em Python para apoiar a criação e revisão de prompts relacionados a cenários de teste, análise de requisitos, relatos de bugs, testes de API e automação. Explora provedores de IA por API e modelos locais via Ollama. As sugestões devem ser revisadas e validadas por uma pessoa; a ferramenta é um apoio, não substitui a análise de QA.

## Projetos complementares da formação

Os repositórios abaixo complementam os estudos, mas não substituem os projetos listados nas nove categorias principais.

- [Ebac](https://github.com/Nickgdm/Ebac) — arquivos `.feature` com cenários de cadastro, configuração e login. O repositório reúne especificações Gherkin; consulte seus arquivos para verificar o escopo implementado.
- [atividade-SQL](https://github.com/Nickgdm/atividade-SQL) — exercícios de consultas em banco de dados relacional.
- [atividade-NoSQL](https://github.com/Nickgdm/atividade-NoSQL) — consultas e dados de exemplo para praticar operações NoSQL.
- [aula-git-ebac](https://github.com/Nickgdm/aula-git-ebac) — atividade introdutória de versionamento.

## Tecnologias e ferramentas

De acordo com cada atividade, os repositórios incluem tecnologias e ferramentas como JavaScript, Node.js, Cypress, Jest, Postman, Appium, WebdriverIO, Cucumber/Gherkin, k6, Apache JMeter, SQL, MongoDB, Docker, Docker Compose e Jenkins. A descrição específica de cada projeto está no respectivo README.

## Como explorar e executar os projetos

1. Escolha uma categoria e abra o repositório correspondente.
2. Leia o README individual antes de executar o projeto.
3. Confira os pré-requisitos, as dependências e os comandos de instalação e execução.
4. Analise os testes, cenários, arquivos de configuração, coleções e evidências disponíveis.
5. Considere as limitações e dependências específicas de cada ambiente.

## Desafios práticos

As atividades da formação permitem praticar diferentes etapas do trabalho de QA, como interpretar requisitos, estruturar cenários, validar interfaces e APIs, configurar ambientes de execução, analisar resultados e documentar procedimentos. O escopo de cada desafio deve ser consultado no repositório correspondente.

## Boas práticas adotadas

- Organização dos projetos por categoria técnica.
- Links diretos para os repositórios de cada atividade.
- Documentação em Markdown para orientar a navegação e a execução.
- Uso de Git e GitHub para versionamento dos trabalhos.
- Descrições objetivas e alinhadas ao conteúdo disponível em cada repositório.
- Transparência sobre o escopo dos projetos, sem presumir resultados ou experiência que não estejam demonstrados nos arquivos.

## 📚 Aprendizados

A organização deste portfólio consolida os estudos em automação web e de API, testes unitários, performance, automação mobile, bancos de dados, containers, CI/CD e uso de inteligência artificial como apoio às atividades de QA. O processo também reforça a importância de estruturar projetos, documentar sua configuração e tornar os trabalhos fáceis de revisar e reproduzir.

## Considerações finais

Este repositório funciona como índice central dos projetos desenvolvidos durante a formação em QA. Os trabalhos estão distribuídos em repositórios independentes e podem ser consultados pelos links acima. A documentação e os projetos poderão ser aprimorados à medida que forem revisados e evoluírem.

---

## 🎓 Formação

Portfólio desenvolvido durante a formação profissionalizante em **Quality Assurance (QA) pela EBAC — Escola Britânica de Artes Criativas e Tecnologia**.
