# Caso de Uso: Gestão do Histórico de Serviços

## Nome do Caso de Uso:
Histórico de Serviços

## Ator Principal:
Funcionário

## Pré-condições:
O funcionário deve ter acesso à página de gestão do histórico de serviços, estando devidamente autenticado no sistema.

## Pós-condições:
O funcionário pode adicionar novos serviços ao histórico, garantindo que as informações sejam precisas e atualizadas.

## Fluxo Principal:
1. O funcionário acessa a página de gestão do histórico de serviços.
2. O sistema exibe uma lista completa dos serviços realizados, incluindo detalhes como data, descrição e valor do serviço.
3. O funcionário preenche os campos necessários para adicionar um novo serviço:
   - ID de Cliente: Identificação única do cliente associado ao serviço.
   - ID de Veículo: Identificação única do veículo relacionado ao serviço.
   - Data: Data em que o serviço foi realizado.
   - Descrição: Descrição detalhada do serviço realizado.
   - Valor: Valor do serviço.
   - Opções de Serviço: Dropdown com as opções de serviço fornecidas pela oficina.
4. O funcionário clica no botão "Adicionar Serviço".
5. O sistema valida os dados inseridos.
6. O sistema adiciona o novo serviço ao histórico de serviços.

## Fluxos Alternativos:
### A1: Campos Obrigatórios Não Preenchidos
- O funcionário deixa um ou mais campos obrigatórios em branco.
- O sistema exibe uma mensagem de erro indicando que todos os campos obrigatórios devem ser preenchidos.
- O fluxo retorna ao passo 3 do fluxo principal.
