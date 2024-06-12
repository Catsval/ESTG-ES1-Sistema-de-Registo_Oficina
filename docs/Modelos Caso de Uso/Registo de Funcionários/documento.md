# Caso de Uso: Registo de Funcionários

1. **Nome do Caso de Uso:**
   Registo de Funcionários

2. **Ator Principal:**
   Funcionário

3. **Pré-condições:**
   O funcionário deve ter acesso à página de registo de funcionários, estando devidamente autenticado no sistema, se aplicável.

4. **Pós-condições:**
   O novo funcionário aparece na lista de funcionários registrados na interface do usuário, visível imediatamente após a inserção dos dados.

5. **Fluxo Principal:**
   1. O funcionário navega para a página de registo de funcionários; essa página é especificamente projetada para adicionar novos funcionários ao sistema.
   2. O funcionário preenche o campo "Nome" com o nome completo do novo funcionário, garantindo que não haja erros de digitação.
   3. O funcionário preenche o campo "Cargo" com a posição ocupada pelo novo funcionário dentro da organização, fornecendo uma descrição precisa e clara.
   4. O funcionário clica no botão "Adicionar Funcionário", iniciando assim o processo de inserção de dados no sistema.
   5. O sistema valida os dados inseridos, verificando a completude e a correção das informações fornecidas; qualquer erro deve ser identificado nesta etapa.
   6. O sistema adiciona os dados do novo funcionário na tabela exibida na página, atualizando a interface do usuário para refletir a nova entrada.

6. **Fluxos Alternativos:**
   ### A1: Campos Obrigatórios Não Preenchidos
   - O funcionário deixa um ou mais campos obrigatórios em branco, uma situação que deve ser prontamente identificada pelo sistema.
   - O sistema exibe uma mensagem de erro, indicando que todos os campos obrigatórios devem ser preenchidos; o funcionário é então direcionado para corrigir a omissão.
   - O fluxo retorna ao passo 2 do fluxo principal, onde o funcionário pode retomar o processo de inserção de dados.
