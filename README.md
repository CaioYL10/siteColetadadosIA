# Sistema Web de Coleta e Análise de Dados sobre Inteligência Artificial 🤖🧠

#### Projeto desenvolvido para coleta, armazenamento, análise e apresentação de informações relacionadas ao tema Inteligência Artificial. ####
##### ✏️🗒️ Contendo Backend, Frontend, Banco de Dados SQLite e geração de relatório em PDF 🗒️✏️ #####

---

<details closed>
  <summary><h2>Informações do projeto 📌</h2></summary>

  ---

  ° Sistema desenvolvido com Node.js e Express.js no backend: ✅📃

  ---

  ° Interface gráfica construída com HTML, CSS e JavaScript: ✅🎨

  ---

  ° Coleta automática de dados utilizando Axios e Cheerio: ✅🌐

  ---

  ° Banco de dados SQLite para armazenamento das informações: ✅🗄️

  ---

  ° Dashboard com exibição dos dados coletados em tempo real: ✅📊

  ---

</details>

---

<details closed>
  <summary><h2>Tecnologias utilizadas 🛠️</h2></summary>

  ---

  - Node.js — Ambiente de execução JavaScript
  - Express.js — Servidor e rotas da aplicação
  - Axios — Requisições HTTP
  - Cheerio — Extração de dados de páginas HTML
  - SQLite3 — Banco de dados local
  - Regex — Validação e tratamento de dados
  - HTML5 / CSS3 / JavaScript — Interface e manipulação do DOM
  - PDFKit — Geração de relatórios em PDF
  - CORS — Comunicação entre frontend e backend

  ---

</details>

---

<details closed>
  <summary><h2>Funcionalidades do sistema ⚙️</h2></summary>

  ---

  ### 🌐 Cadastro de Sites
  Permite cadastrar sites relacionados ao tema Inteligência Artificial para realizar as coletas.

  ---

  ### 📥 Coleta Automática de Dados
  Utiliza Axios para acessar páginas externas e Cheerio para extrair:
  - títulos
  - links
  - imagens
  - palavras-chave
  - descrições

  ---

  ### 🗄️ Armazenamento no Banco
  Os dados coletados são salvos em tabelas relacionadas no banco SQLite.

  ---

  ### 🔎 Consulta com INNER JOIN
  O sistema realiza consultas relacionando os dados das tabelas utilizando INNER JOIN.

  ---

  ### 📊 Dashboard
  Exibição visual das informações coletadas através de cards, listas e resumos.

  ---

  ### 📄 Relatório PDF
  Geração automática de relatório em PDF com os dados coletados.

  ---

</details>

---

<details closed>
  <summary><h2>Rotas principais 🔗</h2></summary>

  ---

  | Método | Rota | Descrição |
  |--------|------|-----------|
  | GET | /dados | Lista os dados coletados |
  | POST | /sites | Cadastra um novo site |
  | POST | /coletar | Inicia a coleta de dados |
  | GET | /dashboard | Retorna dados do dashboard |
  | GET | /relatorio | Gera o relatório PDF |

  ---

</details>

---

<details closed>
  <summary><h2>Como executar ▶️</h2></summary>

  ---

  ### Pré-requisitos
  - Node.js instalado
  - npm disponível no terminal

  ---

  ### Instalação

  ```bash
  npm install
