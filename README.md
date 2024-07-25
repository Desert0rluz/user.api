A API Users.Api foi criada para gerenciar informações de usuários. Ela fornece endpoints para realizar operações básicas de CRUD (Create, Read, Update, Delete) sobre os dados dos usuários armazenados em um banco de dados MS SQL Server.
Como a API Funciona

A API utiliza o Entity Framework para interagir com o banco de dados e expõe os seguintes endpoints conforme a especificação do Swagger:

    GET /api/Users: Retorna a lista de todos os usuários.
    GET /api/Users/{id}: Retorna os detalhes de um usuário específico pelo ID.
    POST /api/Users: Cria um novo usuário.
    PUT /api/Users/{id}: Atualiza as informações de um usuário existente pelo ID.
    DELETE /api/Users/{id}: Deleta um usuário específico pelo ID.
    GET /api/Users/hello: Retorna a string "Hello World!" para verificar se a API está funcionando.