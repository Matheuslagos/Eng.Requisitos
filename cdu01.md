# CDU001. Gerenciar Produto

- **Ator principal**: Funcionário
- **Resumo**: Este caso de uso descreve como o funcionário pode gerenciar produtos em um sistema, adicionar, editar e excluir.
- **Pré-condição**: O funcionário deve estar previamente cadastrado.
- **Pós-Condição**: As alterações no produto, como adicionar, editar e excluir, são refletidas no sistema e no banco de dados.

## Fluxo Principal - Adicionar
| Ações do ator | Ações do sistema |
| :-----------------: | :-----------------: | 
| 1 - [IN] O funcionário seleciona a opção "Gerenciar Produtos" no menu principal;| | 
| | 2 - [OUT] O sistema exibe uma lista de produtos existentes, com opções para adicionar, editar ou excluir produtos. Nessa lista sera renderizado ultimo preço dos produtos, nome, id | 
| 3 - [IN] O funcionário seleciona "Adicionar Produto"; | |  
| | 4 - [OUT] O sistema exibe um formulário de entrada de informações do produto; | 
| 5 - [IN] O funcionário preenche os campos necessários, descrição, preço, categoria e aciona a funcionalidade “Adicionar Produto”; | | 
| | 6 - [OUT] O sistema registra o novo produto no banco de dados; | 
| 7 - [IN] [IN] O funcionário visualiza a adição do novo produto. | | 

## Fluxo Principal - Editar
| Ações do ator | Ações do sistema |
| :-----------------: |:-----------------: | 
| 1 - [IN] No passo 3 do "Fluxo Principal - Adicionar", o funcionário selecionar "Editar Produto"; | | 
| | 2 - [OUT] O sistema permite que o funcionário selecione um produto da lista; | 
| 3 - [IN] O funcionário seleciona o produto e então edita as informações desse produto e confirmar as alterações; | | 
| | 4 - [OUT] O sistema registra as alterações do produto no banco de dados; | 
| 5 - [IN] O funcionário visualiza as alterações do produto. | | 

## Fluxo Principal - Excluir
| Ações do ator | Ações do sistema |
| :-----------------: |:-----------------: | 
| 1 - [IN] No passo 3 do "Fluxo Principal - Adicionar", o funcionário selecionar "Excluir Produto"; | | 
| | 2 - [OUT] O sistema permite que o funcionário selecione um produto da lista; | 
| 3 - [IN] O funcionário seleciona e confirma a exclusão do produto; | | 
| | 4 - [OUT] O sistema apresenta uma mensagem de confirmação de exclusão; | 
| 5 - [IN] O funcionário confirma a exclusão do produto; | | 
| | 6 - [OUT] O sistema remove o produto do banco de dados; | 
| 7 - [IN] O funcionário visualiza a exclusão do produto. | | 

## Fluxo Alternativo III - Cancelar a Adição
| Ações do ator | Ações do sistema |
| :-----------------: |:-----------------: | 
| 1 - [IN] A partir do passo 3 do "Fluxo Principal", o funcionário cancelar a adição do produto; | | 
| | 2 - [OUT] Sistema retorna ao menu principal de gerenciamento de produtos. | 

## Fluxo Alternativo IV - Cancelar a Edição
| Ações do ator | Ações do sistema |
| :-----------------: |:-----------------: | 
| 1 - [IN] A partir do passo 1 do "Fluxo alternativo I - Editar Produto", o funcionário cancela a edição do produto; | | 
| | 2 - [OUT] Sistema retorna ao menu principal de gerenciamento de produtos. | 

## Fluxo Alternativo V - Cancelar Exclusão
| Ações do ator | Ações do sistema |
| :-----------------: |:-----------------: | 
| 1 - [IN] A partir do passo 1 do "Fluxo alternativo II - Excluir Produto", o funcionário cancela a exclusão do produto; | | 
| | 2 - [OUT] Sistema retorna ao menu principal de gerenciamento de produtos. | 

## Fluxo de exceção I - Validação
| Ações do ator | Ações do sistema |
| :-----------------: |:-----------------: | 
| 1 - [IN] O funcionário durante a adição ou edição de um produto, tentar inserir informações inválidas, como deixar campos obrigatórios em branco ou inserir dados em um formato incorreto; | | 
| | 2 - [OUT] Sistema deve exibir uma mensagem de erro indicando o problema e permitir que o funcionário corrija as informações. | 

## Fluxo de exceção II - Conflito
| Ações do ator | Ações do sistema |
| :-----------------: | :-----------------: | 
| 1 - [IN] O funcionário durante a edição de um produto, tentar salvar alterações, mas essas alterações entrarem em conflito com os dados existentes (por exemplo, tentando definir um ID de produto que já existe); | |  
| | 2 - [OUT] Sistema deve notificar o funcionário sobre o conflito e solicitar que ele resolva o problema. |  

## Fluxo de exceção III - Conflito de Dependências
| Ações do ator | Ações do sistema |
| :-----------------: | :-----------------: | 
| 1 - [IN] O funcionário tentar excluir um produto que tenha dependências em outras partes do sistema (por exemplo, se o produto estiver associado a pedidos existentes); | |  
| | 2 - [OUT] Sistema deve exibir uma mensagem de aviso indicando que o produto não pode ser excluído devido a dependências e solicitar ao funcionário para confirmar a exclusão ou cancelar a ação. |  

## Fluxo de exceção IV - Erros Técnicos
| Ações do ator | Ações do sistema |
| :-----------------: | :-----------------: | 
| 1 - [IN] O funcionário adicionou, editou ou excluiu produtos e ocorreram erros técnicos, como problemas no banco de dados ou falhas no sistema; | |  
| | 2 - [OUT] Sistema deve fornecer uma mensagem de erro genérica e a opção de tentar novamente ou entrar em contato com o suporte técnico. |  

## Fluxo de exceção V - Não Autenticado
| Ações do ator | Ações do sistema |
| :-----------------: | :-----------------: | 
| 1 - [IN] O funcionário não está autenticado ao tentar acessar o caso de uso "Gerenciar Produto"; | |  
| | 2 - [OUT] Sistema deve redirecionar para a página de login e, após a autenticação bem-sucedida, retornar ao ponto em que o funcionário tentou acessar originalmente. |
