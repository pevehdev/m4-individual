# SISTEMA DE ACOMPANHAMENTO

## Objetivo do trabalho

<p> Criar um banco de dados com as modelagens para armazenar seus cursos, turmas e alunos. </p>

Questões importantes que devem ser respondidads:

### Existem outras entidades além dessas três?
<p> Sim, poderia ter a entidade Professor, a propria Sala poderia ser uma entidade já que Turma poderia mudar de uma sala para outra.</p>

### Quais são os principais campos e tipos?
<p> Os principais campos e tipos são os ids, cpf ou matrícula do tipo int (inteiro) pois é por eles que são feito as chaves primárias. Entre outros campos como nome, capacidade, turno, endereco, telefone e etc. Estes ultimos podem ser considerados como varchar.</p>

### Como essas entidades estão relacionadas?
<p>A entidade "Turma" possui no mínimo "1" e no máximo "N" "Cursos". "Cursos" pode estar em "0" ou "N" "Turmas".</p>
<p>Uma "Turma" pode ter "0" ou no máximo "N" "Aluno"."Aluno" pode estar no minimo "1" e máximo "N" Turmas </p>
<p>Um "Aluno" pode estar em "0" ou "N" "Cursos" e Cursos pode ter "0" ou "N" "Alunos"</p>
