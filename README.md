📄 Sistema de Controle de Impressões (Singleton)

📌 Descrição

Este projeto consiste em um sistema simples de controle de impressões desenvolvido em Java, com persistência de dados em SQLite.

O principal objetivo é demonstrar a aplicação do padrão de projeto Singleton, garantindo que exista apenas uma instância responsável pela conexão com o banco de dados.

🎯 Objetivo

Controlar o cadastro de documentos para impressão
Armazenar dados em banco de dados local
Aplicar o padrão Singleton na prática

🧠 Padrão de Projeto Utilizado
🔹 Singleton

O padrão Singleton foi aplicado na classe ConexaoBD, com o objetivo de:

Garantir uma única instância de conexão com o banco
Evitar múltiplas conexões simultâneas
Centralizar o acesso aos dados

⚙️ Tecnologias Utilizadas

Java
SQLite
JDBC

📊 Funcionalidades
📥 Cadastrar documento
📄 Listar documentos
❌ Remover documento
