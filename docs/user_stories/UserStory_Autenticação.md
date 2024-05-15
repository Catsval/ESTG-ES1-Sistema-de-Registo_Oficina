### Autenticação e Controle de Acesso para Funcionários

**Como** gerente de uma oficina mecânica,  
**Gostaria de** implementar um sistema de autenticação e controle de acesso para funcionários,  
**Para que** possamos garantir a segurança das informações e limitar o acesso apenas a usuários autorizados.

**Critérios de Aceitação**:
1. **Autenticação de Usuários**: Deve haver um sistema de login que exija que os funcionários insiram suas credenciais (nome de usuário e senha) para acessar o sistema.
2. **Registro de Tentativas de Acesso**: Deve haver um registro de todas as tentativas de login, incluindo informações como data, hora e resultado da tentativa (bem-sucedida ou falha).
3. **Recuperação de Senha Segura**: Deve haver um processo seguro para os funcionários recuperarem suas senhas no caso de esquecimento, garantindo que apenas o usuário legítimo possa redefinir a senha.
4. **Bloqueio de Conta por Tentativas Excedidas**: Se houver várias tentativas de login malsucedidas, a conta do usuário deve ser temporariamente bloqueada para proteger contra ataques de força bruta.
5. **Feedback de Erro de Login**: Se houver uma tentativa de login malsucedida, o usuário deve receber uma mensagem de erro clara e informativa para orientá-lo sobre como proceder.
