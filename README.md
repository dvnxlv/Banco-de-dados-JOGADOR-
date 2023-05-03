# Banco-de-dados-JOGADOR-


create table Jogadores (codigo integer not null auto_increment, 
username varchar (20) not null unique, email varchar (100) not null unique, senha varchar (20) not null, primary key (codigo));
