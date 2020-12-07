# Projeto Crud Rest
Repositório criado para a matéria de ADID6.

# Banco de Dados
Para realizar a atividade usei o microsoft sql server management studio 18. 
Código necessário para criar o bd:

```
CREATE DATABASE WEB_API
USE WEB_API

CREATE TABLE Usuarios(
	  UsuarioId int primary key,
    Nome varchar(30),
    Email varchar(30),
	  Senha varchar(30)
)

INSERT INTO Usuarios(UsuarioId,Nome,Email,Senha) VALUES(1,'Esther','estherleao@gmail.com','123456')
INSERT INTO Usuarios(UsuarioId,Nome,Email,Senha) VALUES(2,'Sueli','suelileao@gmail.com','121212')
INSERT INTO Usuarios(UsuarioId,Nome,Email,Senha) VALUES(3,'Erick','erickleao@gmail.com','101010')
```

# Postman
Para fazer requisições é necessário usar o Postman

