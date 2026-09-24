
Entrega 1 — Modelo Conceitual (DER)

Modelagem de um sistema de gestão de informações para a Coruja Surf

---

1. Caracterização da Organização

1.1 Nome e natureza da organização

A organização escolhida para o desenvolvimento deste projeto é a Coruja Surf, que atua no comércio de vestuário, realizando vendas presenciais e vendas online.

O levantamento de requisitos foi realizado por meio de entrevista com Antônio Gracia Ferreira Júnior.

Razão Social / Nome Fantasia: Coruja Surf
CNPJ: Não informado
Ramo de atuação: Comércio de vestuário, com vendas presenciais e online.
Entrevistado: Antônio Gracia Ferreira Júnior.

As informações acima foram obtidas durante o levantamento de requisitos realizado com a organização.

1.2 Contexto e porte

A Coruja Surf realiza a venda de roupas, com foco também nas vendas online.

Atualmente, a organização possui processos predominantemente manuais, com registros realizados em papel, e não utiliza um sistema integrado de gestão.

Está previsto que o sistema seja utilizado pelo proprietário e por aproximadamente quatro colaboradores.

A principal plataforma considerada para utilização do sistema são dispositivos móveis, principalmente celulares e smartphones.

1.3 Problemas e necessidades identificados

Durante o levantamento, foi identificado que a organização possui baixo nível de informatização.

Os principais processos ainda são realizados manualmente, sem um sistema integrado de gerenciamento e sem cadastros estruturados ou histórico organizado.

Os principais problemas e necessidades identificados foram:

- Registros realizados manualmente em papel;
- Ausência de um sistema integrado de gestão;
- Falta de cadastros estruturados;
- Falta de histórico organizado;
- Necessidade de melhorar a gestão das vendas;
- Grande demanda de trabalho manual nas operações online;
- Controle de estoque inexistente ou inadequado;
- Necessidade de registrar vendas e saídas de produtos;
- Necessidade de registrar pedidos e comprovantes de pagamento;
- Necessidade de consultar históricos de vendas, clientes e pedidos;
- Necessidade de notificações sobre estoque baixo;
- Necessidade de notificações sobre novos pedidos;
- Necessidade de notificações sobre status de pagamentos;
- Necessidade de controle de acesso às informações administrativas e financeiras.

1.4 Justificativa da escolha

A Coruja Surf foi escolhida por apresentar processos de negócio que podem ser representados por meio de uma modelagem de banco de dados, envolvendo clientes, produtos, estoque, vendas, pedidos, pagamentos e usuários.

A organização também apresenta oportunidades de melhoria por meio da informatização dos processos atualmente realizados de maneira manual.

O levantamento identificou como necessidades principais a gestão de estoque, o registro digital de vendas e pedidos, a consulta de históricos, a utilização de alertas e a criação de diferentes perfis de acesso em uma interface voltada para dispositivos móveis.

1.5 Evidências da organização

A existência e os processos da organização foram considerados a partir do levantamento de requisitos realizado por meio de entrevista com Antônio Gracia Ferreira Júnior.

Entrevistado: Antônio Gracia Ferreira Júnior
Organização: Coruja Surf
CNPJ: Não informado no levantamento.

Informações que ainda precisam ser anexadas, caso sejam exigidas pela instituição:

- Endereço completo da organização;
- Telefone ou outro contato;
- Site ou rede social;
- Link do Google Maps, se disponível;
- Fotografias da organização ou da visita;
- Outras evidências solicitadas pelo professor.

---

2. Processos de Negócio

2.1 Principais processos mapeados

Com base no levantamento realizado, foram identificados os seguintes processos principais:

2.1.1 Venda de produtos

A organização realiza vendas de roupas de forma presencial e online.

O registro de vendas e a saída dos produtos foram identificados como informações diárias essenciais para a operação.

2.1.2 Gestão de estoque

O controle de estoque foi identificado como uma das principais necessidades da organização.

Atualmente, o controle é inexistente ou inadequado, sendo considerada uma prioridade a criação de um processo estruturado para cadastro de produtos e registro de movimentações de entrada e saída.

2.1.3 Registro de pedidos

O processo de pedidos ocorre principalmente no ambiente online.

Atualmente, o cliente realiza o pedido e envia o comprovante de pagamento, sendo necessário substituir esse fluxo informal por um registro digital organizado.

2.1.4 Controle de pagamentos

Os pedidos podem envolver o envio de comprovantes de pagamento.

O sistema deverá permitir organizar essas informações e possibilitar o acompanhamento do status dos pagamentos.

2.1.5 Consulta de históricos

A consulta ao histórico foi identificada como importante para:

- Vendas;
- Clientes;
- Pedidos.

2.1.6 Sistema de notificações

Foi identificada a necessidade de avisos relacionados a:

- Estoque baixo;
- Novos pedidos;
- Status dos pagamentos.

Essas notificações deverão ser pensadas principalmente para utilização em dispositivos móveis.

2.1.7 Controle de acesso

Embora atualmente exista um único nível de acesso, o levantamento identificou a necessidade de restringir informações administrativas e financeiras ao proprietário.

Como proposta para o sistema, foram identificados os perfis:

- Administrador/Proprietário;
- Operador/Funcionário.

2.2 Fluxogramas

Os processos principais podem ser representados pelos seguintes fluxos:

Fluxo de venda

Cliente
   ↓
Escolha do produto
   ↓
Registro da venda/pedido
   ↓
Registro dos produtos
   ↓
Pagamento
   ↓
Confirmação do pagamento
   ↓
Atualização do estoque
   ↓
Conclusão da venda/pedido

Fluxo de pedido online

Cliente
   ↓
Realiza o pedido
   ↓
Envia comprovante de pagamento
   ↓
Verificação do pagamento
   ↓
Atualização do status
   ↓
Preparação do pedido
   ↓
Atualização do estoque
   ↓
Conclusão do pedido

Fluxo de estoque

Produto
   ↓
Entrada de produtos
   ↓
Atualização do estoque
   ↓
Venda/saída do produto
   ↓
Nova quantidade em estoque
   ↓
Verificação do estoque mínimo
   ↓
Alerta de estoque baixo

Fluxo de notificações

Evento do sistema
       ↓
Identificação do evento
       ↓
Novo pedido / pagamento / estoque baixo
       ↓
Geração da notificação
       ↓
Usuário recebe o aviso
       ↓
Notificação marcada como lida

«Os fluxogramas acima representam os processos identificados e deverão ser transformados em diagramas visuais caso a entrega exija os fluxogramas como imagens anexadas.»

---

3. Requisitos do Sistema

3.1 Requisitos Funcionais

Os requisitos funcionais foram elaborados a partir das necessidades identificadas no levantamento.

Código| Requisito
RF01| O sistema deve permitir cadastrar clientes.
RF02| O sistema deve permitir consultar clientes cadastrados.
RF03| O sistema deve permitir consultar o histórico de vendas dos clientes.
RF04| O sistema deve permitir cadastrar produtos.
RF05| O sistema deve permitir consultar produtos cadastrados.
RF06| O sistema deve permitir registrar entradas de produtos no estoque.
RF07| O sistema deve permitir registrar saídas de produtos do estoque.
RF08| O sistema deve permitir consultar a quantidade disponível de cada produto.
RF09| O sistema deve permitir registrar vendas.
RF10| O sistema deve permitir registrar os produtos pertencentes a cada venda.
RF11| O sistema deve permitir registrar pedidos online.
RF12| O sistema deve permitir acompanhar o status dos pedidos.
RF13| O sistema deve permitir registrar informações relacionadas aos pagamentos.
RF14| O sistema deve permitir registrar e consultar comprovantes de pagamento.
RF15| O sistema deve permitir consultar o histórico de vendas.
RF16| O sistema deve permitir consultar o histórico de pedidos.
RF17| O sistema deve permitir consultar informações históricas de clientes.
RF18| O sistema deve gerar notificações para novos pedidos.
RF19| O sistema deve gerar notificações relacionadas ao status dos pagamentos.
RF20| O sistema deve gerar notificações quando o estoque estiver baixo.
RF21| O sistema deve permitir cadastrar usuários.
RF22| O sistema deve permitir controlar permissões de acesso dos usuários.
RF23| O sistema deve permitir diferenciar o acesso do proprietário e dos funcionários.
RF24| O sistema deve permitir marcar notificações como lidas.

«Os requisitos funcionais representam a proposta de solução derivada das necessidades identificadas no levantamento. As funcionalidades não informadas diretamente pelo entrevistado deverão ser validadas posteriormente.»

3.2 Requisitos Não Funcionais

Código| Requisito
RNF01| O sistema deve possuir interface adequada para dispositivos móveis.
RNF02| A interface deve ser responsiva e priorizar a utilização em celulares e smartphones.
RNF03| O sistema deve possuir controle de autenticação dos usuários.
RNF04| O sistema deve restringir informações administrativas e financeiras conforme o perfil do usuário.
RNF05| As informações devem ser armazenadas de forma organizada e consistente.
RNF06| O sistema deve possibilitar consultas rápidas aos históricos de vendas, clientes e pedidos.
RNF07| O sistema deve possibilitar futuras expansões de funcionalidades.
RNF08| As informações de autenticação devem ser protegidas de forma adequada.

A utilização em dispositivos móveis e o controle de permissões foram identificados como necessidades durante o levantamento.

---

4. Regras de Negócio

4.1 Regras operacionais

Com base no levantamento realizado, foram identificadas as seguintes regras e necessidades operacionais:

RN01. A organização realiza vendas de roupas.

RN02. As vendas podem ocorrer presencialmente ou online.

RN03. O registro das vendas e a saída dos produtos são informações importantes para a operação diária.

RN04. Os produtos precisam possuir controle de estoque.

RN05. A movimentação de entrada e saída dos produtos deve ser registrada.

RN06. O cliente pode realizar um pedido online.

RN07. No processo atual, o cliente envia o comprovante de pagamento após realizar o pedido.

RN08. O sistema deverá permitir o registro organizado dos pedidos e pagamentos.

RN09. O sistema deverá permitir consultar históricos de vendas, clientes e pedidos.

RN10. O sistema deverá emitir notificações relacionadas a novos pedidos.

RN11. O sistema deverá permitir notificações relacionadas ao status dos pagamentos.

RN12. O sistema deverá permitir notificações quando houver estoque baixo.

RN13. Informações administrativas e financeiras devem possuir acesso restrito ao proprietário.

RN14. O sistema deverá considerar diferentes perfis de usuário.

RN15. A utilização do sistema deverá priorizar dispositivos móveis.

4.2 Restrições organizacionais

O levantamento identificou algumas limitações e informações ainda não definidas.

Atualmente:

- Não existe cadastro formal de clientes;
- Não existe cadastro formal de funcionários;
- Não existe cadastro formal de produtos;
- O controle de estoque é inexistente ou inadequado;
- Os registros são predominantemente manuais;
- Não existe sistema integrado de gerenciamento;
- Atualmente existe apenas um nível de acesso;
- Não foram informadas integrações necessárias;
- Não foram definidas pelo entrevistado as funcionalidades consideradas essenciais;
- Não foi definido um critério de sucesso para o sistema;
- Não foi identificada necessidade imediata de emissão de relatórios.

Esses pontos deverão ser aprofundados nas próximas etapas do projeto.

---

5. Dicionário de Dados Conceitual (Preliminar)

O modelo conceitual considera as seguintes entidades principais:

- Cliente;
- Produto;
- Estoque;
- Venda;
- Item_Venda;
- Pedido;
- Pagamento;
- Usuário;
- Notificação.

5.1 Cliente

Atributo| Descrição| Regra de negócio associada
id_cliente| Identificador único do cliente| Chave primária
nome| Nome do cliente| Cadastro do cliente
telefone| Telefone do cliente| Informação de contato
email| E-mail do cliente| Informação de contato
endereco| Endereço do cliente| Informação de cadastro
data_cadastro| Data do cadastro| Controle do cadastro

5.2 Produto

Atributo| Descrição| Regra de negócio associada
id_produto| Identificador do produto| Chave primária
nome| Nome do produto| Identificação
descricao| Descrição do produto| Caracterização
categoria| Categoria do produto| Classificação
tamanho| Tamanho da roupa| Característica
cor| Cor do produto| Característica
preco| Preço de venda| Informação comercial
ativo| Indica se o produto está ativo| Controle de disponibilidade

5.3 Estoque

Atributo| Descrição| Regra de negócio associada
id_estoque| Identificador do estoque| Chave primária
id_produto| Produto relacionado| Chave estrangeira
quantidade_atual| Quantidade disponível| Deve ser atualizada conforme movimentações
estoque_minimo| Quantidade mínima considerada| Relacionada ao alerta de estoque baixo
data_atualizacao| Data da última atualização| Controle da movimentação

5.4 Venda

Atributo| Descrição| Regra de negócio associada
id_venda| Identificador da venda| Chave primária
id_cliente| Cliente relacionado| Chave estrangeira
id_usuario| Usuário responsável| Chave estrangeira
data_venda| Data da venda| Registro da operação
valor_total| Valor total da venda| Informação financeira
status| Situação da venda| Controle da operação

5.5 Item_Venda

Atributo| Descrição| Regra de negócio associada
id_item_venda| Identificador do item| Chave primária
id_venda| Venda relacionada| Chave estrangeira
id_produto| Produto vendido| Chave estrangeira
quantidade| Quantidade vendida| Deve representar a saída do estoque
preco_unitario| Preço unitário| Valor do produto no momento da venda
subtotal| Valor total do item| Quantidade × preço unitário

5.6 Pedido

Atributo| Descrição| Regra de negócio associada
id_pedido| Identificador do pedido| Chave primária
id_cliente| Cliente que realizou o pedido| Chave estrangeira
data_pedido| Data do pedido| Registro da operação
valor_total| Valor total do pedido| Informação comercial
status| Status do pedido| Deve permitir acompanhar a situação
observacao| Informações adicionais| Campo opcional

5.7 Pagamento

Atributo| Descrição| Regra de negócio associada
id_pagamento| Identificador do pagamento| Chave primária
id_venda| Venda relacionada| Chave estrangeira
id_pedido| Pedido relacionado| Chave estrangeira
valor| Valor do pagamento| Informação financeira
forma_pagamento| Forma de pagamento| Deve ser registrada
parcelas| Quantidade de parcelas| Relacionada ao pagamento parcelado
status| Status do pagamento| Permite acompanhamento
comprovante| Comprovante enviado pelo cliente| Relacionado ao processo atual
data_pagamento| Data do pagamento| Registro financeiro

5.8 Usuário

Atributo| Descrição| Regra de negócio associada
id_usuario| Identificador do usuário| Chave primária
nome| Nome do usuário| Cadastro
email| E-mail do usuário| Acesso ao sistema
senha| Senha do usuário| Deve ser protegida
perfil| Perfil de acesso| Proprietário ou funcionário
ativo| Indica se o usuário está ativo| Controle de acesso

Os perfis considerados no levantamento são:

- Administrador/Proprietário;
- Operador/Funcionário.

5.9 Notificação

Atributo| Descrição| Regra de negócio associada
id_notificacao| Identificador da notificação| Chave primária
id_usuario| Usuário destinatário| Chave estrangeira
tipo| Tipo de notificação| Novo pedido, pagamento ou estoque baixo
mensagem| Conteúdo do aviso| Informação apresentada ao usuário
data_envio| Data do envio| Registro da notificação
lida| Indica se foi visualizada| Controle de leitura

Privacidade

Nenhum dado pessoal real de clientes, funcionários ou outras pessoas deve ser utilizado como exemplo no trabalho.

---

6. Modelagem Conceitual

6.1 Entidades reconhecidas

As entidades foram definidas a partir dos processos e necessidades identificados:

Cliente

Representa os clientes que realizam compras ou pedidos.

Produto

Representa as roupas comercializadas pela Coruja Surf.

Estoque

Representa o controle da quantidade disponível dos produtos.

Venda

Representa uma operação de venda realizada pela organização.

Item_Venda

Representa cada produto pertencente a uma venda.

Pedido

Representa os pedidos realizados, especialmente no processo online.

Pagamento

Representa as informações relacionadas ao pagamento dos pedidos ou vendas.

Usuário

Representa as pessoas autorizadas a utilizar o sistema.

Notificação

Representa os avisos enviados aos usuários.

6.2 Atributos e classificações

Os atributos foram definidos para representar as principais informações necessárias às operações identificadas.

Os identificadores das entidades funcionam como chaves primárias.

Os atributos que estabelecem ligação entre entidades funcionam como chaves estrangeiras.

6.3 Relacionamentos pertinentes

Relacionamento| Descrição
Cliente — Pedido| Um cliente pode realizar pedidos.
Cliente — Venda| Um cliente pode realizar vendas.
Produto — Estoque| O estoque controla a quantidade dos produtos.
Venda — Item_Venda| Uma venda pode possuir vários itens.
Produto — Item_Venda| Um produto pode aparecer em diferentes itens de venda.
Venda — Pagamento| O pagamento pode estar relacionado à venda.
Pedido — Pagamento| O pagamento pode estar relacionado ao pedido.
Usuário — Venda| Um usuário pode registrar vendas.
Usuário — Notificação| Um usuário pode receber notificações.

6.4 Restrições e políticas organizacionais

O modelo considera:

- Controle de produtos;
- Controle de estoque;
- Registro de entradas e saídas;
- Registro de vendas;
- Registro de pedidos;
- Registro de pagamentos;
- Consulta de históricos;
- Notificações;
- Controle de usuários;
- Restrição de informações administrativas e financeiras ao proprietário.

A necessidade de restrição das informações administrativas e financeiras foi identificada diretamente durante o levantamento.

---

7. Diagrama Entidade-Relacionamento (DER)

O Diagrama Entidade-Relacionamento representa a estrutura conceitual proposta para o sistema da Coruja Surf.

Arquivos do DER

DER em PDF:

"DER_Coruja_Surf.pdf" (./DER_Coruja_Surf.pdf)

Modelo conceitual em planilha:

"DER_Coruja_Surf_Conceitual.xlsx" (./DER_Coruja_Surf_Conceitual.xlsx)

O DER contempla as principais entidades identificadas no levantamento:

- Cliente;
- Produto;
- Estoque;
- Venda;
- Item_Venda;
- Pedido;
- Pagamento;
- Usuário;
- Notificação.

O diagrama deve representar:

- Entidades;
- Atributos;
- Relacionamentos;
- Cardinalidades.

O modelo foi estruturado considerando a possibilidade de expansão nas próximas etapas do projeto.

---

8. Justificativa Técnica

A modelagem foi desenvolvida considerando os problemas e necessidades identificados durante o levantamento de requisitos.

A entidade Cliente foi criada para permitir a organização das informações dos clientes, já que atualmente não existe cadastro formal e a consulta ao histórico de clientes foi considerada importante.

A entidade Produto representa as roupas comercializadas pela organização.

A entidade Estoque foi separada para representar o controle das quantidades dos produtos, pois o levantamento identificou o controle de estoque como uma necessidade prioritária.

A entidade Venda representa as operações comerciais realizadas pela organização.

A entidade Item_Venda permite representar os produtos que fazem parte de cada venda, evitando concentrar vários produtos em um único registro.

A entidade Pedido foi incluída devido à importância das vendas online para a organização e ao processo atualmente utilizado, no qual o cliente realiza o pedido e envia o comprovante de pagamento.

A entidade Pagamento foi criada para organizar as informações financeiras relacionadas aos pedidos e vendas.

A entidade Usuário representa as pessoas que utilizarão o sistema. O levantamento prevê o proprietário e aproximadamente quatro colaboradores como usuários.

A divisão entre Administrador/Proprietário e Operador/Funcionário foi considerada devido à necessidade de restringir informações administrativas e financeiras ao proprietário.

A entidade Notificação foi incluída para r













<img width="1768" height="2948" alt="DER_Coruja_Surf_DIAGRAMA" src="https://github.com/user-attachments/assets/0ce6de63-ccaa-4ef1-81b5-ca6dad7768e2" />








