# CRUD NO SQL

## 1. criando um novo banco de dados (create database)

## -- Um banco de dados é um lugar onde conde conseguimos guardar informações/dados dentro de tabelas.
## -- Para criar um banco de dados , usamos o seguinte comando:

######  CREATE DATABASE UNIVERSIDADE 
 

## -- CRIANDO UMA TABELA 'ALUNOS'

###### CREATE TABLE alunos(
###### ID_Aluno int,
###### Nome_Aluno varchar(100),
###### Email varchar(100)
###### );

## -- SELECIONANDO AS TABELAS CRIADAS

###### SELECT * FROM alunos;
###### SELECT * FROM cursos;
###### SELECT * FROM matriculas


## -- ADICIONANDO DADOS NA TABELA 'ALUNOS'
###### INSERT INTO alunos( ID_Aluno, Nome_Aluno, Email)
###### values
     (1, 'maria' , 'maria123@gmail.com'),
     (2, 'João ' , 'João123@gmail.com'),
     (3, 'Diego' , 'Diego123@gmail.com'),
     (4, 'carla' , 'Carla@gmail.com);
  
## --ATUALIZANDO O VALOR DO CURSO.   
    UPADATE cursos
    SET Preco_Curso = 700
    WHERE ID_CURSO = 1;

##Por fim vamos ver os comandos DROP TABLE e DROP DATABASE, que servem para excluir uma tabela ou um banco de dados.

