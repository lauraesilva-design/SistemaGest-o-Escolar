#Sistema de Gestão Escolar

##Sistema para gerenciar funcionários, alunos, cursos e matrículas

1.Que utilizará o sistema(usúarios)?
funcionarios.

2.Quais os tipos de usúarios e o que cada tipo consegue fazer?
Colaboradores:cadastrar alunos, cadastrar cursos,editar dados dos alunos, editar dados dos cursos, excluir alunos, excluir cursos,
listar alunos, listar cursos, matricular alunos nos cursos e desmatricular alunos dos cursos e atualizar os proprios dados.

ADM:Todas sa fuções acima, mais: cadastrar outros fucionarios, listar outros fucionarios, editar dados dos outros funcionarios e excluir outros funcionarios.

3.Quais informações iremos armazenar?
Funcionarios:nome, email, cargo, data de nascimento, CPF, senha, telefone, endereço.

Alunos:nome, email, matricula, telefone, CPF, data de nascimento,endereco.

Cursos:descrição, carga horaria, nome.

Matriculas:quais alunos estão cadastrados em quais cursos.

4.Quais regras ou restrições são necessárias?

-Apenas funcionarios ADM podem criar/deletar outros fucionarios.

-Funcionarios colaboradores não podem editar dados de outros 
funcionarios.

-CPF não pode repetir, email não pode repetir.

-Nome, email, cargo, CPF, senha, carga horaria, matricula são dados obrigatorios.

-Um aluno não pode ser matriculado duas ou mais vezes no mesmo curso.

-O sistema deve validar sa infomações.

##PROBLEMA:
-Esses sistema é direcionado a funcionarios da escolas.
-Permite cadastrar, edita, listar e deletar alunos,cursos, matriculas e funcionarios.
