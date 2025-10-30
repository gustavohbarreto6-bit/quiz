📝 README.md — Capitais dos Países
# 🌎 Capitais dos Países

Este projeto exibe uma lista de **países e suas respectivas capitais**, com o objetivo de servir como material educativo e de apoio para estudos de **geografia, programação e banco de dados**.

---

## 🧠 Objetivo

Demonstrar como é possível organizar e exibir informações de **países e suas capitais** utilizando **PHP e HTML**, de forma simples, clara e visualmente agradável.

O projeto também ajuda a praticar:
- Estruturação de arrays em PHP
- Exibição de dados em tabelas HTML
- Estilização básica com CSS
- Organização de código em múltiplos arquivos

---

## 📂 Estrutura do Projeto



📁 capitais/
├── index.php # Página principal (interface e exibição da tabela)
├── paises.php # Lista de países e suas capitais (array PHP)
└── README.md # Este arquivo de documentação


---

## 🧩 Exemplo de Dados

O arquivo `paises.php` contém um array associativo com países e suas capitais, como no exemplo abaixo:

<?php
return [
    ['pais' => 'Brasil', 'capital' => 'Brasília'],
    ['pais' => 'Argentina', 'capital' => 'Buenos Aires'],
    ['pais' => 'França', 'capital' => 'Paris'],
    ['pais' => 'Japão', 'capital' => 'Tóquio'],
    ['pais' => 'Estados Unidos', 'capital' => 'Washington, D.C.'],
    ['pais' => 'Canadá', 'capital' => 'Ottawa'],
    ['pais' => 'Alemanha', 'capital' => 'Berlim'],
    ['pais' => 'Itália', 'capital' => 'Roma'],
    ['pais' => 'Portugal', 'capital' => 'Lisboa'],
    ['pais' => 'México', 'capital' => 'Cidade do México'],
    ['pais' => 'Espanha', 'capital' => 'Madri'],
    ['pais' => 'Austrália', 'capital' => 'Camberra'],
    ['pais' => 'China', 'capital' => 'Pequim'],
    ['pais' => 'Índia', 'capital' => 'Nova Délhi'],
    ['pais' => 'Rússia', 'capital' => 'Moscou'],
];

🖥️ Exemplo de Interface

A página index.php exibe os dados em formato de tabela, com o nome do país e sua capital, por exemplo:

País	Capital
Brasil	Brasília
França	Paris
Japão	Tóquio
Alemanha	Berlim
Canadá	Ottawa
🎨 Estilo e Design

A interface utiliza um design limpo, inspirado em tons de azul e branco, com:

Cabeçalho moderno

Tabela centralizada e responsiva

Efeitos de hover nas linhas

Exemplo de CSS embutido no index.php:

table {
    width: 80%;
    margin: 40px auto;
    border-collapse: collapse;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}
th {
    background-color: #1565c0;
    color: white;
    padding: 15px;
}
td {
    padding: 15px;
    background-color: #f9f9f9;
}
tr:hover {
    background-color: #e3f2fd;
}

⚙️ Como Executar

Instale o XAMPP ou WampServer (para rodar PHP localmente).

Coloque a pasta do projeto dentro de:

C:\xampp\htdocs\capitais


Inicie o servidor Apache pelo painel do XAMPP.

No navegador, acesse:

http://localhost/capitais/index.php

🧭 Possíveis Extensões

Adicionar bandeiras dos países (usando imagens ou emojis)

Criar campo de busca para filtrar países

Adicionar população e continente

Criar uma API JSON com as informações

👨‍💻 Autor

Desenvolvido por Gustavo Barreto
📧 gbrtsports@gmail.com

🌐 Projeto educacional em PHP, HTML e CSS — 2025


---

Quer que eu te gere também o **`index.php`** e o **`paises.php`** correspondentes a esse README (com tabela e design igual ao dos jogadores)?  
Assim você teria o projeto completo de “Capitais dos Países” pronto para usar.
