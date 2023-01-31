# SQL_PROJECT

⇨ Existem outras entidades além dessas três?
As entidades criadas alem das três apresentadas são equipe e secretaria
⇨ Quais são os principais campos e tipos?
No modelo nostemos: 
cursos: id(int), nome(varchar), carga_horaria(int), categoria(varchar).
alunos: id(int), nome(varchar), cpf(int), data_de_nascimento(int).
equipe:id(int), professor(varchar), monitor(varchar), coordernador(varchar).
secretaria: id(int), nome(varchar).
turma: id(int), nome(varchar), horario(int)
⇨ Como essas entidades estão relacionadas?
cursos contém turma e secretaria, turma possui alunos e equipe.
