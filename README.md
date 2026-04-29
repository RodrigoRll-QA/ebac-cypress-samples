# 🚀 EBAC Cypress Automation Project

![Cypress](https://img.shields.io/badge/-cypress-%23058a5e?style=for-the-badge&logo=cypress&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-blue?style=for-the-badge&logo=github-actions)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Reports](https://img.shields.io/badge/Reports-Allure-yellow?style=for-the-badge)
![EBAC](https://img.shields.io/badge/EBAC-QE-%23E30613?style=for-the-badge)

## 📝 Descrição Técnica
Este repositório contém uma suíte de automação E2E robusta desenvolvida com **Cypress**. O projeto foi estruturado com foco em cenários reais de Qualidade de Software, integrando fluxos de **CI/CD** e relatórios dinâmicos para garantir visibilidade e estabilidade nas entregas.

## 🛠️ Diferenciais do Projeto

### 🔄 Automação e CI/CD
O projeto utiliza **GitHub Actions** para implementar integração contínua (CI): 
* Execução automática de testes a cada push ou Pull Request.
* Feedback imediato sobre a saúde da aplicação.

### 📊 Relatórios Detalhados (Allure Reports)
Integração com **Allure Framework** para análise visual dos resultados:
* **Dashboards:** Gráficos de sucesso e falha.
* **Evidências:** Screenshots e logs automáticos anexados em caso de erro.
* **Histórico:** Acompanhamento da performance da suíte de testes.

---

## ⚙️ Configuração e Execução

### Instalação

```bash
git clone https://github.com/EBAC-QE/ebac-cypress-samples.git
```

### 2. Entrar na pasta do projeto

```bash
cd ebac-cypress-samples
```

### 3. Instalar as dependências

```bash
npm install
```

### 4. Rodar o Cypress (modo interativo)

```bash
npx cypress open
```

### 5. Rodar os testes (modo headless)

```bash
npx cypress run
```

📂 Estrutura do Projeto
.github/workflows: Pipelines de automação (CI).

cypress/e2e: Scripts de automação.

cypress/fixtures: Massas de dados para testes.

cypress.config.js: Configurações e plugins.

---
👤 Autor
Rodrigo Lins - QA Automation Engineer.
----
Focado em entregar software com confiança através de automação inteligente.
