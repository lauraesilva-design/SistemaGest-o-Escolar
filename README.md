# Sistema de Gestão Escolar

## Sistema para gerenciar funcionários, alunos, cursos e matrículas

1.Que utilizará o sistema(usúarios)?
funcionários.

2.Quais os tipos de usúarios e o que cada tipo consegue fazer?
Colaboradores:cadastrar alunos, cadastrar cursos,editar dados dos alunos, editar dados dos cursos, excluir alunos, excluir cursos,
listar alunos, listar cursos, matricular alunos nos cursos e desmatricular alunos dos cursos e atualizar os proprios dados.

ADM:Todas sa fuções acima, mais: cadastrar outros fucionários, listar outros fucionarios, editar dados dos outros funcionários e excluir outros funcionários.

3.Quais informações iremos armazenar?
Funcionários:nome, email, cargo, data de nascimento, CPF, senha, telefone, endereço.

Alunos:nome, email, matricula, telefone, CPF, data de nascimento,endereco.

Cursos:descrição, carga horaria, nome.

Matriculas:quais alunos estão cadastrados em quais cursos.

4.Quais regras ou restrições são necessárias?

-Apenas funcionários ADM podem criar/deletar outros fucionários.

-Funcionários colaboradores não podem editar dados de outros 
funcionários.

-CPF não pode repetir, email não pode repetir.

-Nome, email, cargo, CPF, senha, carga horaria, matrícula são dados obrigatorios.

-Um aluno não pode ser matriculado duas ou mais vezes no mesmo curso.

-O sistema deve validar sa informações.

## PROBLEMA:
-Esses sistema é direcionado a funcionarios da escolas.
-Permite cadastrar, editar, listar e deletar alunos, cursos, matrículas e funcionários.

## Modelo de Negócio:
![Business Model Canvas](images/ModelodeNegocio.png)

## Requisitos:
1. Requisitos Funcionais:
-Cadastrar Alunos
-Cadastrar Funcionários
-Cadastrar Cursos
-Listar Alunos
-Listar Cursos
-Mostrar dados dos Alunos
-Mostrar dados dos Funcionários
-Mostrar dados do Curso
-Realizar Matrículas
-Editar os dados do Aluno
-Editar os dados do Funcionário
-Excluir os Alunos
-Excluir os Funcionários
-Excluir os Cursos
-Excluir as Matrículas

2. Requisitos Não Funcionais:
-Autenticação
-Interface com Navegação Padronizada a Consistente entre as Telas
-Interface responsiva e adaptativa e diversas resoluções de telas e dispositivos diferentes, como computador, celular e tablet
-Interface deve ser compatível com os principais navegadores Web
-Criptografar as senhas antes de salvá-las no banco de dados
-Quando o sistema notificar qualquer erro, tem que ser corrigido rapidamente.
-Atender o usuario com dificultade de acessar
-usuário só pode ter acesso somente às funções permitidas
-Notificar erros internos do sistema
-Notificar erros externos do sistema
-Ser facíl de acessar o sistema
-Facilidade no carregamento da página
-Os dados importantes devem possuir cópias de segurança
-Teve ter armazenamento suficiente para todos dados armazenados
-O sistema deve suportar muitos usúarios utilizando ao mesmo tempo 
-Ter proteção a dados pessoais dos alunos como nome completo, cpf, idade e etc
-Ter proteção a dados pessoais dos Fucionarios que ficam no sistema como nome completo, cpf, telefone e etc
-O sistema deve permitir recuperação dos dados em caso de falha
-Sistema deve registrar alterações importantes realizadas pelos funcionários
-Quando utilizado deve evitar travamentos e erros frequentes
-O sistema deve carregar rapidamente as informações
-Deve ficar disponível durante o horário de trabalho e tanbém de estudo
-O sistema deve continuar funcionando adequadamente mesmo com o aumento do número de funcionários
-Ter uma lista para quem esta a espera de uma vaga
-O funcionário poderá configurar o sistema de acordo com suas preferências de trabalho
-
-
-
-
-
-
-
-
-
-
-