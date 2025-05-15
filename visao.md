**Documento de Visão**

**Histórico da Revisão**


|**Data**|**Versão**|**Descrição**|**Autor(es)**|
| :-: | :-: | :-: | :-: |
|04/09/2023|1\.0|Versão inicial do documento de visão |Elder Fernandes, Fabio Ricardo, Thavinson Brendo, Victor Olympio|
|20/09/2023|1\.1|Adição de novos detalhes sobre o sistema e contexto |Elder Fernandes, Fabio Ricardo, Thavinson Brendo, Victor Olympio|
|20/07/2024|1\.2|Adição de novos detalhes sobre o sistema e contexto |Elder Fernandes, Dassaev Lima, Matheus Lagos, Victor Olympio|

1. **Projeto**: **PotiFruti**
   1. **Objetivo**:

Esse projeto pretende desenvolver um e-commerce voltado para venda de frutas e verduras sob demanda, fazendo com que os Usuários façam o pedido diretamente pelo site, tornando as compras mais intuitivas, dando mais agilidade, e automatizando um dos trabalhos mais demorados que o funcionário precisa fazer , criando a possibilidade de atender ainda mais clientes.

2. **Descrição do problema:**

|**O problema de** |*Falta de eficiência e organização, no processo de geração de lista para cotação, dos pedidos de compras dos clientes, incluindo a geração de listas de compras antes do faturamento.*|
| :- | :- |
|**afeta**| *O cliente que não possui uma forma sistemática de realizar pedidos de frutas e verduras, e a empresa, devido à dificuldade de gerenciar os pedidos dos clientes.*
|**cujo impacto é** | Um trabalho desnecessário na cotação dos produtos solicitados pelos clientes, e lentidão no atendimento, acarretando possíveis perdas nas vendas.*|
|**uma boa solução seria**|*Um aplicativo que permita que seus usuários realizem pedidos de frutas, verduras, entre outros, tornando as compras eficazes, permitindo que a empresa acompanhe de forma eficiente os pedidos, cotações e entregas aos clientes, além de garantir uma usabilidade fácil e intuitiva para todos os usuários.*|

3. **Descrição dos usuários:**

|**Nome**|**Descrição**|**Responsabilidade**|
| - | - | - |
|*Funcionário*|*Usuário que Gerencia os produtos e pedidos, cadastrando as cotações feitas.*|*- Consultar pedidos de compra dos clientes;* *- Gerar lista para cotação de preço no fornecedor;* *- Realiza cotação de preço de produtos;* *- Cadastrar a cotação dos produtos; - Após pedido confirmado, autorizar a compra e a entrega dos pedidos.*|
|*Cliente*|*Usuário que acessa o sistema para realizar pedidos de frutas e verduras*|*- Envia pedido de compras para o hortifruti;* *- Confirma a compra mediante aprovação na cotação de preços no fornecedor;* *- Confirma recebimento dos produtos.*|
|*Administrador*|*Usuário que acessa o sistema para gerenciar os funcionários da empresa*|*- Mantém o cadastro dos funcionários.*|


4. **Descrição do ambiente dos usuários:**
- Os clientes mandam o pedido para o hortifruti via aplicativo de mensagens instantâneas, que recebe esses pedidos e cria uma lista, com essa lista um outro funcionário vai até o ceasa fazer a cotação dos itens disponíveis, compram os pedidos que já é certo, voltam para a unidade, separam os pedidos, e colocam no caminhão para ir entregar.
- O número de pessoas envolvidas na execução da tarefa são 4 (Financeiro, que anota os pedidos e cuida dos pagamentos, a pessoa que compra os itens no Ceasa, a pessoa que arruma os pedidos, e o entregador).
- Geralmente o Usuário precisa transcrever todos os pedidos recebidos, gastando em média 1h~2h por dia só para digitar, com o sistema pronto, isso será automatizado, e pronto para ser impresso ou para ser checado direto no aplicativo.
- É utilizado o WhatsApp para receber os pedidos de compras dos usuários e um sistema proprietário para processar as listas e enviar ao fornecedor.

5. **Principais necessidades dos usuários:**

   *A principal necessidade do usuário é, que tenha uma empresa que faça o translado entre os produtos ofertados pela central de abastecimento (CEASA) e o cliente final, com uma listagem online, e o'que ele não encontrar listado, tenha como acrescentar ao pedido, e que tenha uma entrega rápida e segura.*


6. **Alternativas concorrentes:**
   
     *Existem várias alternativas disponíveis, incluindo plataformas E-commerce como Amazon, Mercado Livre, Aliexpress e Nordestão.*
  
   **Amazon:**

      - *Pontos Fortes: Ampla variedade de produtos, entrega rápida, sistema de revisão de produtos, excelente atendimento ao cliente.*
      - *Pontos Fracos: Não oferece venda de frutas frescas.*
  
   **Nordestão**

      - *Pontos Fortes: Venda de produtos frescos, incluindo frutas*
      - *Pontos Fracos: Depende do estoque existente, e não tem todos os produtos que tem no ceasa, e sim só os mais vendidos.*

   **Mercado Livre:**

      - Pontos Fortes: Diversidade de produtos, ampla base de vendedores, sistema de classificação de vendedores.
      - Pontos Fracos: Não se concentra na venda de frutas sob demanda, sem garantia de frescor

   **Aliexpress:**

      - Pontos Fortes: Produtos a preços competitivos, grande variedade de produtos de vendedores internacionais.
      - Pontos Fracos: Não especializado em venda de frutas, prazos de entrega mais longos.

   No entanto, em comparação com essas alternativas, o Potifruti se destaca pelo seu foco específico na venda de frutas sob demanda. Enquanto os concorrentes tradicionais mantêm estoques e oferecem uma variedade de         produtos, o Potifruti se concentra em atender às necessidades específicas dos clientes, permitindo que eles solicitem frutas frescas de acordo com suas preferências e horários de entrega desejados. Isso diferencia o    Potifruti de seus concorrentes, proporcionando uma experiência única e conveniente aos usuários finais.



7. **Visão geral do produto:**

   **Recursos Principais:**

      - Catálogo de Produtos: O site deve apresentar um catálogo completo de frutas disponíveis para compra, com descrições, imagens e preços.
      - Pedido de Compras: Os usuários devem ser capazes de adicionar produtos ao pedido de compras, ajustar as quantidades e finalizar suas compras de forma conveniente.
      - Checkout e Pagamento: Integração com métodos de pagamento seguros para facilitar a conclusão das transações.
      - Gerenciamento de Conta: Os usuários devem poder criar e gerenciar suas contas, incluindo informações de perfil e histórico de pedidos.
      - Pesquisa e Filtros: Funcionalidades de pesquisa avançada e filtros para facilitar a localização de produtos desejados.
      - Entrega Programada: Opção de agendamento de entrega, permitindo que os clientes escolham a data e o horário de entrega.
      - Notificações por E-mail/SMS/Telegram: Comunicação automatizada para atualizar os clientes sobre o status dos pedidos e promoções.
      - Suporte ao Cliente: Mecanismo para lidar com perguntas, reclamações e feedback dos clientes.
  
   **Interfaces com Outros Aplicativos:**
      - Integração com Plataformas de Pagamento: Conexão com serviços de pagamento online Pagseguro.
      - Integração com Redes Sociais: Compartilhamento de Mensagens via Telegram.




8. **Requisitos FUNCIONAIS**

|***Código***|***Nome***|***Descrição***|
| :- | :- | :- |
|*F01*|Criar conta de cliente|*O usuário se cadastra no sistema como cliente*|
|*F02*|Criar conta de funcionário|*O administrador cadastra os funcionários da empresa*|
|*F03*|Entrar no sistema|*O usuário acessa o sistema como cliente, funcionário ou administrador*|
|*F04*|Sair do sistema|*O usuário finaliza o acesso ao sistema*|
|*F05*|Montar pedido de compra|*O cliente seleciona os produtos desejados e insere no pedido de compra*|
|*F06*|Confirmar pedido de compra|*O cliente confirma o pedido de compra e aguarda a cotação dos produtos*|
|*F07*|Cadastrar categoria|*O funcionário mantém o cadastro de categorias de produtos*|
|*F08*|Cadastrar produto|*O funcionário mantém o cadastro de produtos*|
|*F09*|Consultar pedidos de compra|*O funcionário lista os pedidos de compras dos clientes*|
|*F10*|Gerar lista para cotação de produtos|*O funcionário gera lista de produtos para cotação de preços em diferentes fornecedores*|
|*F11*|Cadastrar cotações de preços|*O funcionário cadastra preços cotados nos fornecedores*|
|*F12*|Enviar cotação de preços|*O funcionário envia preços cotados para os clientes aprovarem a compra*|
|*F13*|Aprovar pedido de compra|*O cliente visualiza e aprova o pedido de compra*|
|*F14*|Confirmação de envio|*O funcionário informa o envio do pedido*|


9. **Requisitos NÃO-FUNCIONAIS**

|**Código**|**Nome**|**Descrição**|**Categoria**|**Classificação**|
| :- | :- | :- | :-: | :-: |
|*NF01*|Controle de acesso Usuário|*Só usuários autenticados podem ter acesso aos Pedidos.*|Segurança|*Obrigatório*|
|*NF02*|Tempo de resposta|*A comunicação entre o servidor e o cliente não pode ultrapassar o tempo limite.*|Performance|*Desejável*|
