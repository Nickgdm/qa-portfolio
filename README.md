# Portfólio de Quality Assurance (QA)

Portfólio de projetos práticos desenvolvidos durante a formação em **Quality Assurance (QA) na EBAC**. Os repositórios estão organizados pelas áreas técnicas do exercício final, com uma descrição objetiva do foco de cada atividade.

> **Nota sobre o escopo:** este portfólio reúne projetos de estudo e exercícios. A presença de uma tecnologia ou ferramenta indica que ela foi abordada no projeto; não significa, por si só, experiência profissional ou execução em produção. Consulte o README de cada repositório para pré-requisitos, instruções e limitações específicas.

## 1. Automação de UI com Cypress

Projetos de automação de interface web e prática inicial com Cypress e Node.js.

- [Hub de Leitura — projeto-base e aplicação de apoio](https://github.com/Nickgdm/teste-cy-base) — aplicação usada como base para atividades de QA.
- [Hub de Leitura — testes de UI com Cypress](https://github.com/Nickgdm/hub-de-leitura-teste-ui) — cenários de automação de interface.
- [Hub de Leitura — tarefa de testes de UI](https://github.com/Nickgdm/Atividade-hub-de-leitura-teste-ui-task) — exercício prático de testes de interface.

## 2. Testes Automatizados de API REST

Testes de endpoints e validação de respostas de APIs. A coleção do Postman também pode servir como referência para exploração manual.

- [Hub de Leitura — testes de API com Cypress](https://github.com/Nickgdm/hub-de-leitura-api-teste) — automação de testes da API.
- [Hub de Leitura — tarefa de testes de API](https://github.com/Nickgdm/hub-de-leitura-api-teste-task) — atividade prática de testes de API REST.
- [Catálogo de Livros — coleção Postman](https://github.com/Nickgdm/atividade-API-Ebac) — coleção de requisições para explorar e validar a API do catálogo de livros.

## 3. DevOps — pipelines e integração contínua

Projetos que exploram a execução de testes em pipelines e a automação de etapas de CI/CD.

- [Pipeline de testes com Jenkins](https://github.com/Nickgdm/ci-cd-teste-jenkins) — configuração de pipeline com Jenkins.
- [Exemplo de CI/CD com Cypress e Docker](https://github.com/Nickgdm/atividade-ci-cd-teste-exemplo) — arquivos de pipeline e execução de testes.
- [Cucumber com Cypress e Jenkins](https://github.com/Nickgdm/Atividade-cucumber-cypress) — projeto de BDD que também contém um Jenkinsfile.

## 4. Projeto com Docker

Projetos que usam containers para configurar aplicações e/ou executar testes em ambientes definidos.

- [Docker Compose — Golden Movie Studio](https://github.com/Nickgdm/atividade-docker) — aplicação com serviços de backend, frontend e testes Cypress.
- [Docker Compose — Hub de Leitura](https://github.com/Nickgdm/atividade-docker-hub-de-leitura) — ambiente integrado para a aplicação e os testes de UI.

## 5. Automação de UI com Cypress — avançado

Exercícios com recursos avançados do Cypress e/ou abordagem BDD.

- [Cypress — Intercept e App Actions](https://github.com/Nickgdm/Atividade-Intercept-AppActions-cypress) — prática com interceptação de chamadas e ações da aplicação.
- [Cypress com Cucumber — BDD](https://github.com/Nickgdm/Atividade-cucumber-cypress) — cenários descritos com Gherkin e abordagem orientada a comportamento.

## 6. Testes de Performance

Cenários e ferramentas para praticar testes de carga e análise de desempenho.

- [Performance com k6 — Hub de Leitura/API](https://github.com/Nickgdm/atividade-k6) — scripts de teste de carga e estresse.
- [Performance com Apache JMeter — BlazeDemo](https://github.com/Nickgdm/atividade-jmeter-blazedemo) — plano de teste JMeter e configuração de dados.

## 7. Automação Mobile com Appium

- [Automação mobile com Appium e WebdriverIO](https://github.com/Nickgdm/atividade-appium-wdio) — projeto de automação de testes mobile, com cenários para Android.

## 8. Testes de Unidade com JavaScript

- [Testes unitários com JavaScript e Jest](https://github.com/Nickgdm/atividade-exercicio-js) — exercícios de testes unitários e cobertura de código.

## 9. Inteligência Artificial aplicada a QA

- [QA Prompt Assistant](https://github.com/Nickgdm/qa-prompt-assistant) — ferramenta de terminal em Python para apoiar a criação e revisão de prompts relacionados a casos de teste, análise de requisitos, relatos de bugs, testes de API e automação. Explora provedores de IA por API e modelos locais via Ollama. A saída gerada deve ser revisada criticamente; a ferramenta apoia o trabalho de QA, mas não substitui a validação humana.

## Projetos complementares da formação

Os projetos abaixo complementam o portfólio, embora não correspondam diretamente a uma das nove categorias obrigatórias do exercício.

- [Exercícios BDD/Gherkin — EBAC](https://github.com/Nickgdm/Ebac) — arquivos `.feature` com cenários de cadastro, configuração e login. O repositório contém especificações Gherkin; não foi identificado nele um executor completo com definições de passos.
- [Consultas SQL](https://github.com/Nickgdm/atividade-SQL) — exercício de consultas em banco de dados relacional.
- [Consultas MongoDB/NoSQL](https://github.com/Nickgdm/atividade-NoSQL) — consultas e dados de exemplo para praticar operações NoSQL.
- [Fundamentos de Git e GitHub — EBAC](https://github.com/Nickgdm/aula-git-ebac) — atividade introdutória de versionamento.
- [qa-toolbox — portfólio principal](https://github.com/Nickgdm/qa-toolbox) — este repositório reúne os links e a organização dos projetos.

## Tecnologias e ferramentas

Conforme o projeto, o portfólio inclui JavaScript, Node.js, Jest, Cypress, Postman, Appium, WebdriverIO, Cucumber/Gherkin, k6, Apache JMeter, SQL, MongoDB, Docker, Docker Compose e Jenkins.

## Como explorar os projetos

1. Abra o repositório pelo link da categoria correspondente.
2. Leia o README individual para entender o objetivo, os pré-requisitos e os comandos de instalação e execução.
3. Consulte os arquivos de teste, configurações, coleções e evidências disponíveis.
4. Execute os projetos seguindo as instruções específicas e considerando as dependências do ambiente.

## Estrutura lógica do portfólio

Os projetos continuam armazenados em repositórios GitHub separados. A estrutura abaixo representa a organização por categoria usada neste README.

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

## Desafios práticos

As atividades permitem praticar diferentes tipos de teste, criar cenários, validar APIs, configurar ambientes, interpretar resultados e documentar procedimentos de execução. Os detalhes e eventuais limitações de cada desafio estão descritos no README do respectivo repositório.

## Boas práticas adotadas

- Organização dos projetos por área técnica.
- Links diretos para os repositórios individuais.
- Documentação de objetivo, ferramentas, pré-requisitos e instruções de execução, conforme o conteúdo de cada projeto.
- Uso de Git e GitHub para versionamento e apresentação do trabalho.
- Descrição transparente do escopo, sem afirmar resultados ou experiência que não estejam demonstrados nos artefatos.

## 📚 Aprendizados

A organização do portfólio consolida estudos de automação web e de API, testes unitários, performance, automação mobile, bancos de dados, containers e CI/CD. Também reforça a importância de estruturar cenários, compreender as ferramentas utilizadas e documentar como cada projeto pode ser configurado e executado.

## Considerações finais

Este portfólio reúne atividades práticas desenvolvidas ao longo da formação em QA. Ele será atualizado conforme os projetos forem revisados e as categorias pendentes forem completadas. Antes de considerar uma atividade concluída, consulte seus arquivos e siga as instruções de execução descritas no README individual.

---

## 🎓 Formação

Portfólio desenvolvido durante a formação profissionalizante em **Quality Assurance (QA) pela EBAC — Escola Britânica de Artes Criativas e Tecnologia**.
