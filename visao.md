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

   A plataforma tem como objetivo disponibilizar um sistema completo de e-commerce especializado na comercialização de frutas, com foco em usabilidade, escalabilidade e segurança. O sistema será desenvolvido com uma arquitetura modular, visando performance e facilidade de manutenção, e contará com funcionalidades voltadas à gestão de produtos, pedidos, usuários e logística de entrega.

   **Recursos Principais:**

      -Catálogo de Produtos
Implementação de um módulo de catálogo dinâmico com suporte a CRUD completo para produtos. Cada item exibirá nome, descrição, imagem, preço unitário, categoria e status de disponibilidade. O sistema deverá permitir fácil integração com um backend para atualização em tempo real.

   -Gestão de Pedidos e Carrinho de Compras
Funcionalidade de carrinho persistente com suporte a múltiplas operações: adicionar, remover, editar quantidades e calcular totais parciais. Integração com o módulo de pedidos para submissão, armazenamento e rastreamento do status em tempo real.

   -Checkout e Integração com Gateways de Pagamento
Implementação de processo de checkout com validação de dados, cálculo de frete (se aplicável) e integração com provedores de pagamento (ex: Stripe, PayPal, Pix) utilizando APIs seguras (HTTPS, tokens e autenticação).

   -Gerenciamento de Contas de Usuário
Sistema de autenticação (login/cadastro) com criptografia de senhas (ex: bcrypt). Área de perfil para gerenciamento de dados pessoais, endereços, preferências e visualização do histórico de pedidos.

   -Pesquisa Avançada e Filtros Dinâmicos
Ferramentas de busca com suporte a autocomplete, pesquisa por palavras-chave e filtros combináveis (categoria, faixa de preço, disponibilidade, etc.). Implementação otimizada para performance com indexação via banco de dados ou mecanismo de busca dedicado (ex: Elasticsearch).

   -Agendamento de Entrega
Sistema de agendamento de entregas baseado em calendário e faixas de horário configuráveis, com verificação de disponibilidade por região e controle de capacidade logística.

   -Sistema de Notificações
Módulo de notificações assíncronas para envio automático de atualizações de pedido, promoções e lembretes via múltiplos canais (e-mail, SMS, Telegram). Integração com serviços externos via APIs (ex: Twilio, SendGrid, Telegram Bot API).

   -Central de Suporte ao Cliente
Implementação de uma interface para suporte ao usuário com formulário de contato, sistema de tickets ou chatbot. Possibilidade de integração com plataformas de atendimento (ex: Zendesk, Freshdesk).
  
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
