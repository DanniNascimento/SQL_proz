# Praticando SQL Curso Proz...

Lembre-se, cada desafio é uma chance de crescer. Não se desanime com os erros; eles são degraus no caminho do aprendizado. E acima de tudo, divirta-se! 
O aprendizado mais eficaz acontece quando nos engajamos e nos interessamos pelo que estamos fazendo.

#### Desafios - Respostas

```sql
-- Nosso banco de dados criado...
CREATE DATABASE ESCOLA;

-- Vamos selecionar o banco de dados ESCOLA para uso
USE ESCOLA;

-- Criar a tabela ALUNO
CREATE TABLE ALUNO (
    ID INT PRIMARY KEY AUTO_INCREMENT,
    nome VARCHAR(100),
    email VARCHAR(100),
    endereco VARCHAR(100)
);

```

#### Cada passo realizado detalhado

1-Criar o banco de dados ESCOLA:
```sql
CREATE DATABASE ESCOLA;
```

2-Selecionar o banco de dados ESCOLA para uso:
```sql
USE ESCOLA;
```

3-Criar a tabela ALUNO com os atributos especificados:
```sql
CREATE TABLE ALUNO (
    ID INT PRIMARY KEY AUTO_INCREMENT, -- Chave primária com auto incremento
    nome VARCHAR(100), -- Atributo nome do tipo varchar
    email VARCHAR(100), -- Atributo email do tipo varchar
    endereco VARCHAR(100) -- Atributo endereço do tipo varchar
);
```
