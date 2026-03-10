REQUISITOS FUCIONAIS
RF1: Pedir para o cliente fazer login e acessar a conta(se n tiver uma conta crio outra)
RF2: Criar um histórico de compras do cliente, com data, valor e os produtos
RF3: Ter uma barra de pesquisa para a pessoa poder ver produtos de seu interesse
REQUISITOS NÃO FUCIONAIS
RNF1: Limite no carrinho, para permitir até 50 compras de uma vez
RNF2: Pré-renderização das funções importante, já ter o carrinho pré-carregado para abrir mais rápido e outras funções de mesma
impotancia
REGRAS DE NEGÓCIO
RN: Sempre perguntar se ele confirma a ação(para aquelas ações que não pode ser desfeita)
RN: Sempre oferecer um disconto no frete para quando o cliente gastar mais de 500 reais e um maior para quando ele gastar mais de 1000 reais
CRITÉRIOS DE ACEITE PARA O RF1
AC1: Dado que o usuário está na tela de cadastro, quando ele preencher o e-mail, senha e nome, e clicar em "Enviar", então um novo
registro deve ser criado no banco de dados.
AC2: Dado que o usuário tenta se cadastrar com um e-mail já existente, quando ele clicar em "Enviar", então o sistema deve exibir uma
mensagem de erro "E-mail já cadastrado".
AC3: Dado que o usuário preenche a senha com menos de 6 caracteres, quando clicar em "Enviar", então o sistema deve impedir o envio e
exibir "Senha deve conter no mínimo 6 caracteres".
