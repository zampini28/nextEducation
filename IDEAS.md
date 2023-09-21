# TODO
1 - Criação das Entidades - (Mínimo 5 entidades com um total de 20 atributos entre elas)
2 - Criação das Controladoras - (CRUD para cada uma das 5 entidades separadas por pasta)
3 - Criação das Services - (CRUD para cada uma das 5 entidades separadas por pasta)
4 - Criação do Repositório
5 - Criação das Migrations
6 - Execução das Migrations
7 - Apresentação no Lab com o Thunder pronto

# IDEAS
Criação das Entidades
- Usuario
	- id
	- nome
	- rg
	- cpf
	- n_telefone
	- email
	- usuario
	- nascimento
	- criacao
	- ult_atualizacao
	- bloqueado
	- senha
- Administrador
	- id
	- usuario_id
	- Professor
	- id
	- disciplina_id
	- usuario_id
- Responsavel
	- id
	- cadastrador_id
	- usuario_id
- Aluno
	- id
	- matricula
	- cadastrador_id
	- usuario_id