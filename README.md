# Projeto de Laboratório de Banco de Dados

Este é um projeto de exemplo para o curso de Laboratório de Banco de Dados. O projeto implementa um sistema de gerenciamento de cursos usando Java e MySQL.

## Estrutura do Projeto

O projeto consiste nas seguintes partes principais:

1. **Configuração do Banco de Dados (MySQL Workbench):**
   - O script SQL `database_setup.sql` cria o banco de dados e as tabelas necessárias.
   - As tabelas incluem: `Gerente`, `Professor`, `Aluno`, `Curso`, `Inscricoes` e `Ministrada`.

2. **Aplicação Java:**
   - **DatabaseInitializer.java:** Inicializa o banco de dados e cria as tabelas.
   - **Main.java:** Interface interativa que permite criar registros no banco de dados.
   - **Classes de Modelo:**
     - `Usuario.java`: Classe abstrata base para `Gerente`, `Professor` e `Aluno`.
     - `Gerente.java`, `Professor.java`, `Aluno.java`: Classes que herdam de `Usuario`.
     - `Curso.java`: Classe que representa um curso.
