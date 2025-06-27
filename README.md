# 📘 Plano de Aula – Projeto Pedagógico: Mural de Comunicados

## 🧑‍🏫 Professor: Cristian Ramos  
**Projeto:** Aplicação fullstack simples com Node.js e Express  
**Objetivo:** Ensinar a integração entre front-end e back-end usando Node.js e Express, com rotas, middleware e consumo via fetch API.  
**Público-alvo:** Estudantes de cursos técnicos ou de graduação em informática ou desenvolvimento web  
**Carga Horária:** 3 aulas de 1h30 (total: 4h30)

---

## 🎯 Objetivos da Aula

### Objetivo Geral:
Capacitar os alunos a desenvolverem uma aplicação web básica com Node.js e Express, entendendo a estrutura de rotas, uso de middleware, e integração com o front-end por meio de requisições HTTP.

### Objetivos Específicos:
- Compreender a arquitetura cliente-servidor.
- Criar rotas e respostas HTTP com Express.
- Utilizar middleware para tratamento de dados e requisições.
- Consumir rotas da API usando `fetch()` no front-end.
- Criar um layout simples com HTML, CSS e Bootstrap.
- Exibir, adicionar e remover comunicados dinamicamente.

---

## 🛠️ Tecnologias e Ferramentas

- **Front-end:** HTML, CSS, Bootstrap, JavaScript (fetch API)
- **Back-end:** Node.js, Express
- **Ambiente:** VS Code, navegador, terminal
- **Extras (opcional):** Nodemon, Postman, Git

---

## 🧠 Competências Desenvolvidas

- Manipulação de rotas e middlewares no Node.js
- Comunicação entre front-end e back-end
- Uso prático do método fetch e requisições HTTP (GET, POST, DELETE)
- Organização de código em camadas simples
- Trabalho com array ou estrutura simulada como "banco de dados"

---

## 📚 Conteúdo Programático

### 🟩 Aula 1 – Introdução à API com Node.js e Express

- Conceito de servidor HTTP
- Criação do projeto Node com `npm init`
- Instalação e configuração do Express
- Criação das primeiras rotas (`GET /comunicados`, `POST /comunicados`)
- Uso de middleware `express.json()`
- Testes com Postman

> **Atividade prática:** Criar array local de comunicados e testar envio e leitura via Postman.

---

### 🟨 Aula 2 – Integração com o Front-End

- Criação da estrutura front-end: `index.html`, `style.css`, `script.js`
- Layout com Bootstrap (tabela ou cards)
- Uso de `fetch()` para consumir `GET` e `POST`
- Inserção dinâmica de comunicados no DOM
- Introdução ao método `DELETE` para remover comunicados

> **Atividade prática:** Criar formulário e exibir comunicados em tela, com botão de exclusão.

---

### 🟥 Aula 3 – Boas Práticas e Refino

- Separação do código (rotas, lógica, arquivos estáticos)
- Middleware customizado (ex: log de requisições, validação de dados)
- Implementação de feedback visual (alertas, carregamento)
- Discussão: como adicionar persistência (banco de dados, arquivos JSON)

> **Atividade prática:** Melhorar UX e organizar o projeto em pastas (`routes`, `public`, etc.)

---

## 🗂️ Estrutura Sugerida de Pastas

```

mural-comunicados/
├── public/
│   ├── index.html
│   ├── script.js
│   └── style.css
├── routes/
│   └── comunicados.js
├── app.js
├── package.json

```

---

## ✅ Avaliação

- Participação nas práticas em aula
- Funcionamento do sistema (rotas, inserção e exibição)
- Organização do código
- Apresentação do projeto em dupla ou individual

---


## 💡 Recursos Didáticos

- Slides explicativos sobre rotas e middleware
- Quadro branco digital ou físico para desenhar o fluxo de requisições
- Código inicial ou repositório modelo
- Exemplos de requisições com Postman

---

> Projeto criado com fins didáticos para ensinar integração fullstack utilizando Node.js, Express e JavaScript moderno no front-end.
