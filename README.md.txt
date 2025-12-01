# Sistema de Gestão de Academia StrongFit — EP4

Este repositório contém os scripts SQL utilizados na Experiência Prática IV, incluindo povoamento do banco, consultas e manipulação de dados.

## 📌 Scripts incluídos

### 1. inserts.sql
Contém todos os comandos INSERT para popular:
- Planos
- Alunos
- Instrutores
- Treinos
- Exercícios
- Aulas coletivas
- Presenças
- Tabela N:N (Treino_Exercicio)

### 2. selects.sql
Consultas utilizando:
- JOIN
- WHERE
- ORDER BY
- LIMIT

### 3. updates.sql
Atualizações de:
- Plano do aluno
- Carga de exercícios
- Telefone de instrutor

### 4. deletes.sql
Exclusões seguras respeitando integridade referencial.

## 📌 Como executar

1. Abra o MySQL Workbench ou PGAdmin.
2. Crie o banco de dados:
   ```sql
   CREATE DATABASE strongfit;
   USE strongfit;
