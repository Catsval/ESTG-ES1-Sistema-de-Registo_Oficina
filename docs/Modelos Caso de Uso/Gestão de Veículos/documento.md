# Caso de Uso: Registo de Veículos

## Nome do Caso de Uso:
Registo de Veículos

## Ator Principal:
Funcionário

## Pré-condições:
O funcionário deve ter acesso à página de registo de veículos, estando devidamente autenticado no sistema, se aplicável.

## Pós-condições:
O novo veículo aparece na lista de veículos registrados na interface do usuário, visível imediatamente após a inserção dos dados.

## Fluxo Principal:
1. O funcionário navega para a página de registo de veículos.
2. O funcionário preenche o campo "Marca" com a marca do veículo.
3. O funcionário preenche o campo "Modelo" com o modelo do veículo.
4. O funcionário preenche o campo "Ano" com o ano de fabricação do veículo.
5. O funcionário preenche o campo "Matrícula" com a matrícula do veículo.
6. O funcionário clica no botão "Adicionar Veículo".
7. O sistema valida os dados inseridos.
8. O sistema adiciona os dados do veículo na tabela exibida na página.

## Fluxos Alternativos:
### A1: Campos Obrigatórios Não Preenchidos
- O funcionário deixa um ou mais campos obrigatórios em branco.
- O sistema exibe uma mensagem de erro indicando que todos os campos obrigatórios devem ser preenchidos.
- O fluxo retorna ao passo 2 do fluxo principal.
