# Caso de Uso: Registo de Funcionários

## Nome do Caso de Uso:
Registo de Funcionários

## Ator Principal:
Funcionário

## Pré-condições:
O funcionário deve ter acesso à página de registo de funcionários, estando devidamente autenticado no sistema, se aplicável.

## Pós-condições:
O novo funcionário aparece na lista de funcionários registrados na interface do usuário, visível imediatamente após a inserção dos dados.

## Fluxo Principal:
1. O funcionário navega para a página de registo de funcionários.
2. O funcionário preenche o campo "Nome" com o nome completo do funcionário.
3. O funcionário preenche o campo "Cargo" com o cargo do funcionário.
4. O funcionário preenche o campo "Contacto" com o número de telefone.
5. O funcionário preenche o campo "Email" com o e-mail do funcionário.
6. O funcionário clica no botão "Adicionar Funcionário".
7. O sistema valida os dados inseridos.
8. O sistema gera um ID único para o funcionário.
9. O sistema adiciona os dados do funcionário, incluindo o ID gerado, na tabela exibida na página.

## Fluxos Alternativos:
### A1: Campos Obrigatórios Não Preenchidos
- O funcionário deixa um ou mais campos obrigatórios em branco.
- O sistema exibe uma mensagem de erro indicando que todos os campos obrigatórios devem ser preenchidos.
- O fluxo retorna ao passo 2 do fluxo principal.
