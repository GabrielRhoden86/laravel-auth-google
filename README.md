## TUTORIAL: https://www.itsolutionstuff.com/post/laravel-10-socialite-login-with-google-account-exampleexample.html#google_vignette

## Fluxo de Autenticação:
# 1 - Usuário faz login com Google: O Google autentica o usuário e retorna um token.
# 2 - Verificação no Banco de Dados: O sistema verifica se o usuário já existe no banco de dados.
# 3 - Criação/Atualização do Usuário: Se o usuário não existir, ele é criado com os dados fornecidos pelo Google.
# 4 - Login Automático: O usuário é autenticado automaticamente no sistema Laravel.

____________________________________________________________________________________________________________________________________
Incluir URL da aplicação no console goole developers:

# 1 -  acesse:
https://console.cloud.google.com/apis/dashboard?project=sinuous-country-309104

# 2 - credenciais 
Em URIs de redirecionamento autorizados insira:
http://localhost:8000/auth/google/callback
