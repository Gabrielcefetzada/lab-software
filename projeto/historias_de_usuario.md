# Histórias de Usuário para o Sistema de Matrículas

## 1. Cadastro de Cursos
**Como** administrador da universidade  
**Quero** cadastrar um novo curso no sistema  
**Para que** eu possa incluir o curso na oferta curricular do semestre.

**Critérios de Aceitação:**
- O sistema deve permitir o preenchimento dos campos obrigatórios: nome do curso, número de créditos e disciplinas.
- O sistema deve confirmar a inclusão do curso com uma mensagem de sucesso.

## 2. Matricular em Disciplinas Obrigatórias
**Como** aluno  
**Quero** me matricular em até 4 disciplinas obrigatórias e até 2 disciplinas optativas para o semestre  
**Para que** eu possa cumprir com os requisitos do meu curso.

**Critérios de Aceitação:**
- O sistema deve listar as disciplinas obrigatórias e optativas disponíveis para matrícula.
- O sistema deve permitir a matrícula em no máximo 4 disciplinas obrigatórias e 2 optativas.
- O sistema deve verificar e informar se a disciplina atingiu o limite máximo de 60 alunos.
- O sistema deve atualizar o número de vagas disponíveis.

## 3. Verificar Disciplinas Ativas
**Como** aluno  
**Quero** ver as disciplinas ativas para o próximo semestre  
**Para que** eu possa me matricular nas disciplinas que estão realmente disponíveis.

**Critérios de Aceitação:**
- O sistema deve listar as disciplinas que têm pelo menos 3 alunos matriculados.
- O sistema deve indicar se a disciplina está cheia e se não aceita mais matrículas.

## 4. Consultar Alunos Matriculados
**Como** professor  
**Quero** consultar a lista de alunos matriculados em minhas disciplinas  
**Para que** eu possa preparar minhas aulas e acompanhar o progresso dos alunos.

**Critérios de Aceitação:**
- O sistema deve fornecer uma lista de alunos matriculados em cada disciplina que o professor leciona.

## 5. Receber Notificação de Matrícula
**Como** sistema de cobranças  
**Quero** ser notificado quando um aluno se matricular em disciplinas  
**Para que** eu possa gerar e enviar a cobrança correspondente.

**Critérios de Aceitação:**
- O sistema de matrículas deve enviar uma notificação ao sistema de cobranças com detalhes das disciplinas e valores a serem cobrados.

## 6. Acessar Disciplinas Disponíveis
**Como** aluno  
**Quero** acessar uma lista de todas as disciplinas disponíveis para matrícula  
**Para que** eu possa escolher as disciplinas que melhor se adequam ao meu plano de estudo.

**Critérios de Aceitação:**
- O sistema deve listar todas as disciplinas disponíveis para o semestre corrente.
- O sistema deve mostrar a quantidade de vagas restantes para cada disciplina.
