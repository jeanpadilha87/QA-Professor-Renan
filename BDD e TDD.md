BDD - Cadastro de Usuário (CREATE)
Cenário: cadastrar novo usuário

Dado que estou na tela de cadastro de usuário e preencho os campos <nome>, <email> e <senha>
Quando clico no botão <Cadastrar>
Então o sistema deve registrar o usuário e redirecionar para a listagem de usuários

------------------------------------------------------------------------------------------------
BDD – Listagem de Usuários (READ)
Cenário: visualizar usuários cadastrados

Dado que estou na tela de listagem de usuários
Quando acesso a página de usuários
Então o sistema deve exibir todos os usuários cadastrados

-----------------------------------------------------------------------------------------------
BDD – Alterar Usuário (UPDATE)
Cenário: atualizar dados de um usuário

Dado que estou na tela de edição de usuário
e altero os campos <nome> e <email>
Quando clico no botão <Salvar>
Então o sistema deve atualizar os dados do usuário e retornar para a listagem

-----------------------------------------------------------------------------------------------
BDD – Deletar Usuário (DELETE)

Dado que estou na tela de listagem de usuários
e seleciono um usuário existente
Quando clico no botão <Excluir>
Então o sistema deve remover o usuário e atualizar a lista de usuários

-----------------------------------------------------------------------------------------------
BDD – Login
Cenário: autenticação no sistema

Dado que estou na tela de login
e informo <email> e <senha>
Quando clico no botão <Entrar>
Então o sistema deve autenticar o usuário e redirecionar para o painel principal

------------------------------------------------------------------------------------------------

Princípios de Teste

Os 7 princípios mostrados nos slides são:

O teste mostra a presença de defeitos
- testar mostra erros, mas não prova que o sistema é perfeito.

Testes exaustivos são impossíveis
- não dá para testar todas as combinações.

Testar cedo economiza tempo e dinheiro
- encontrar erros no início é mais barato.

Defeitos se agrupam
- poucos módulos costumam concentrar muitos erros.

Paradoxo do pesticida
- repetir sempre os mesmos testes deixa de encontrar novos bugs.

Testes dependem do contexto
- cada sistema exige estratégias diferentes.

Ausência de erros é uma ilusão
- mesmo sem bugs, o sistema pode não atender o usuário.


