# Caso de Uso: Registo de Clientes

## Nome do Caso de Uso:
Registo de Clientes

## Ator Principal:
Funcionário

## Pré-condições:
O funcionário deve ter acesso à página de registo de clientes.

## Pós-condições:
O cliente aparece na lista de clientes registados na interface do usuário.

## Fluxo Principal:
1. O funcionário navega para a página de registo de clientes.
2. O funcionário preenche o campo "Nome" com o nome do cliente.
3. O funcionário preenche o campo "Veículos" com a descrição dos veículos do cliente.
4. O funcionário clica no botão "Adicionar Cliente".
5. O sistema valida os dados inseridos.
6. O sistema adiciona os dados do cliente na tabela exibida na página.

## Fluxos Alternativos:
### A1: Campos Obrigatórios Não Preenchidos
- O funcionário deixa um ou mais campos obrigatórios em branco.
- O sistema exibe uma mensagem de erro indicando que todos os campos obrigatórios devem ser preenchidos.
- O fluxo retorna ao passo 2 do fluxo principal.
