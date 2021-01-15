# Projeto e Implementa��o de Banco de Dados
Reposit�rio para atividades da disciplina Projeto e Implementa��o de Banco de Dados (ENPE/2020)

## Trabalho 2 - Grupo 04
### Participantes da Etapa 04:
* Daniel Farah (417513)
* Felipe Francisco Berreta (422649)
* Marco Antonio B. Grivol (758619)
* Pedro Henrique Grespan Carneiro (761029)

### Instru��es
1. Verifique se est� na vers�o mais recente do reposit�rio atrav�s do comando "git pull".
2. Crie um novo banco de dados no pgAdmin4 chamado "pibd".
3. Execute em sequ�ncia:
    1. 1create.sql
    2. 2triggerANDprocedure.sql
    3. 3popula.sql
    4. 4requisitos.sql
4. Abra o projeto em uma IDE (Eclipse preferencialmente).
5. Se necess�rio, altere as informa��es de login no arquivo Tela.java (este projeto utiliza postgres como usuario e senha padr�es).
6. Execute o arquivo Tela.java.

### Exemplos
1. Consulta:
	1. carro
	2. pessoa
	3. possui
	4. telefone
	5. temAmizade
2. Inser��o:
	1. carro: placa, modelo, ano, cor
	2. pessoa: nome, sobrenome, data de nascimento (aaaa-dd-mm), email, homepage, cep, n�mero da rua, nome da rua
	3. possui: c�digo da pessoa, placa
	4. telefone: c�digo da pessoa, ddd, prefixo, n�mero
	5. temAmizade: c�digo da pessoa, c�digo da amiga, data da amizade (aaaa-dd-mm)