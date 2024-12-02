## Api

Projeto aluno online

* A API desenvolvida com Spring Boot utilizando o Spring Initializr, foi criada para organizar e gerenciar informações de um ambiente acadêmico e usada para controle dos dados de "aluno", "professore", "disciplina" e "matrículaAluno".

* O Endpoint implementado com Spring Boot foi composto por dependências como Spring web, Spring Data JPA, Swagger e Mysqldriver.

* Foi usado como anotações @RestController @RequestMapping @PostMapping @Autowired @ResponseStatus.

* As entidades criadas foram: Aluno, AlunoControlle, AlunoRepository, AlunoService, Professor, ProfessorController, ProfessorRepository, ProfessorService, Disciplina, DisciplinaController, DisciplinaRepository, DisciplinaService, MatriculaAluno, MatriculaAlunoController, MatriculaAlunoRepository, MatriculaAlunoService.

* Utilizando a ferramenta de desenvolvimento e teste Insomnia foram criadas as seguintes requisições:

- Na URL http://localhost:8080/alunos foram criadas as requisições do tipo POST, GET, PUT e DEL;

- Na URL http://localhost:8080/professores foram criadas as requisições tipo POST, PUT, GET, DELETE;

- Na URL http://localhost:8080/disciplinas foram criadas as requisições tipo POST, PUT, GET, DELETE;

- Na URL http://localhost:8080/matriculas-alunos foram criadas as requisições tipo POST, PUT, GET, DELETE e PTCH;

- Sendo usado o formato JSON no corpo de todas as requisição.

* Foi instalada a ferramenta Swagger para documentar a API.

* No Dbearver foi criado o banco de dados e as respectivas tabelas para armazenamento dos dados de aluno, professor, disciplina e matricula aluno. Sendo usado o insomnia para a realização dos testes garantindo o sucesso das implementações.



![readme insomnia](https://github.com/user-attachments/assets/1211fd04-8870-46ef-b769-a41934fb7790)






![readme dbeaver](https://github.com/user-attachments/assets/e57b158f-f82d-4aaa-915d-b79388a7d841)

