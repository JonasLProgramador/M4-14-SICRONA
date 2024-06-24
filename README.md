<!DOCTYPE html>
<html lang="pt-BR">
<body>
    <h1>📊 Projeto de Banco de Dados SQLite com Node.js</h1>
    <p>Este projeto foi desenvolvido durante a <strong>Aula 15 do Módulo 4</strong> do curso <strong>Programadores do Amanhã</strong>. O objetivo é aplicar os conceitos aprendidos em aula sobre a criação e manipulação de um banco de dados usando SQLite e Node.js.</p>
    <h2>🚀 Visão Geral</h2>
    <p>A aplicação cria um banco de dados SQLite chamado <code>animal.db</code> e gerencia três tabelas distintas:</p>
    <ul>
        <li><strong>animalsExtinct:</strong> Armazena informações sobre animais extintos.</li>
        <li><strong>Volunteer:</strong> Registra dados de voluntários.</li>
        <li><strong>AnimalsSaved:</strong> Contém informações sobre animais resgatados.</li>
    </ul>
    <h2>📋 Funcionalidades</h2>
    <ul>
        <li>📄 <strong>Criar Tabelas:</strong> Define e cria as tabelas <code>animalsExtinct</code>, <code>Volunteer</code> e <code>AnimalsSaved</code>.</li>
        <li>📝 <strong>Inserir Dados:</strong> Adiciona registros nas tabelas com funções específicas para cada uma.</li>
        <li>🔍 <strong>Consultar Dados:</strong> Realiza consultas em todas as tabelas para listar os registros inseridos.</li>
    </ul>
    <h2>🛠️ Tecnologias Utilizadas</h2>
    <ul>
        <li><a href="https://nodejs.org/">Node.js</a> - Ambiente de execução JavaScript no servidor.</li>
        <li><a href="https://www.npmjs.com/package/sqlite3">SQLite3</a> - Biblioteca SQLite para Node.js para gerenciar o banco de dados.</li>
    </ul>
    <h2>📂 Estrutura do Projeto</h2>
    <pre>
        project-root/
        │
        ├── src/
        │   ├── database/
        │   │   └── connection.js   # Código principal para configuração do banco de dados
        │
        ├── animal.db               # Banco de dados SQLite (arquivo invisível)
        └── package.json            # Dependências e scripts do projeto
    </pre>
    <h2>📦 Dependências</h2>
    <ul>
        <li><a href="https://www.npmjs.com/package/sqlite3">SQLite3</a> - Biblioteca para gerenciar bancos de dados SQLite.</li>
    </ul>
    <h2>🔧 Como Executar o Projeto</h2>
    <p>Siga os passos abaixo para clonar e executar o projeto em seu ambiente local:</p>
    <ol>
        <li>Clone o repositório:
            <pre><code>git clone https://github.com/JonasLProgramador/sqlite-node-project.git</code></pre>
        </li>
        <li>Navegue até a pasta do projeto:
            <pre><code>cd sqlite-node-project</code></pre>
        </li>
        <li>Instale as dependências:
            <pre><code>npm install</code></pre>
        </li>
        <li>Execute o arquivo <code>connection.js</code> para criar o banco de dados e tabelas, e inserir dados:
            <pre><code>node src/database/connection.js</code></pre>
        </li>
        <li>Verifique os logs no console para ver as consultas executadas.</li>
    </ol>
    <h2>📝 Licença</h2>
    <p>Este projeto está licenciado sob a Licença MIT. Para mais detalhes, consulte o arquivo <code>LICENSE</code>.</p>

</body>
</html>
