# Sistema de Gerenciamento de Academia 

## Objetivo

Desenvolver um sistema para gerenciar alunos, planos, professores e pagamentos, susbistituindo o controle manual atualmente realizado em papel e planilhas.

---
## Usuarios do sistema
- Administrador
- Recepcionista
- Professor
- Aluno

## Problemas Identificados

- Demora para localizar informações dos alunos.
- Controle manual de pagamentos.
- Dificuldade para acompanhar matrículas.
- Informações espalhadas em papel.
- Risco de perda de dados.

## Requisitos Funcionais

- RF01 - Cadastrar aluno.
- RF02 - Editar aluno.
- RF03 - Excluir aluno.
- RF04 - Cadastrar planos.
- RF05 - Registrar pagamentos.
- RF06 - Consultar alunos.
- RF07 - Gerenciar professores.
- RF08 - Emitir relatórios.

## Requisitos Não Funcionais

- RNF01 - O sistema deve possuir autenticação.
- RNF02 - O sistema deve funcionar em dispositivos móveis.
- RNF03 - O tempo de resposta deve ser inferior a 2 segundos.
- RNF04 - Os dados devem possuir backup periódico.
- RNF05 - Apenas usuários autorizados poderão acessar determinadas funcionalidades.

## Regras de Negócio
- RN01 - Cada aluno deve possuir um CPF único.
- RN02 - Um aluno só pode ter uma matrícula ativa.
- RN03 - O pagamento vencido bloqueia novos agendamentos.
- RN04 - Apenas administradores podem excluir alunos.
- RN05 - Professores podem visualizar alunos, mas não excluí-los.

## Dúvidas para o Cliente

- Existe integração com. maquininhas de pagamento?
- A academia possui mais de uma unidade?
- O aluno poderá acessar um portal próprio?
- Haverá emissão de recibos?