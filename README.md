# ProjetoPS2


Leonardo Depercia Romero -  TIA:31832091 
Vitor Henrique Vieira da Silva- TIA:31886574

CREATE TABLE carro(
id_carro INTEGER NOT NULL GENERATED ALWAYS AS IDENTITY (START WITH 1, INCREMENT BY 1),
modelo VARCHAR(50) NOT NULL,
marca VARCHAR(30) NOT NULL,
ano  INTEGER NOT NULL,
categoria VARCHAR(20) NOT NULL,
PRIMARY KEY(id_carro)
);

CREATE TABLE conta_bancaria(
id_conta INTEGER NOT NULL GENERATED ALWAYS AS IDENTITY (START WITH 1, INCREMENT BY 1),
nome_titular VARCHAR(255) NOT NULL,
saldo INTEGER NOT NULL,
agencia  INTEGER NOT NULL,
PRIMARY KEY(id_conta)
);
