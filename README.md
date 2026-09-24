Entrega 1 — Modelo Conceitual (DER)

Coruja Surf

Sistema de gestão para uma loja de roupas com vendas presenciais e online.

1. Organização

Nome: Coruja Surf
Ramo: Comércio de vestuário
Entrevistado: Antônio Gracia Ferreira Júnior
CNPJ: Não informado

A empresa utiliza processos manuais, com registros em papel e sem sistema integrado. O sistema será utilizado pelo proprietário e aproximadamente quatro colaboradores, principalmente em celulares.

Problemas identificados

- Falta de sistema integrado;
- Registros manuais;
- Controle de estoque inadequado;
- Falta de cadastro de clientes, produtos e funcionários;
- Dificuldade para acompanhar vendas, pedidos e pagamentos;
- Necessidade de históricos e notificações;
- Necessidade de controle de acesso.

## 1.5 Evidências da organização

O levantamento de requisitos foi realizado por meio de entrevista com Antônio Gracia Ferreira Júnior, representante da Coruja Surf.

### Evidência da entrevista

![Evidência da entrevista](IMG-20260913-WA0112.jpg)

2. Processos de negócio

- Venda presencial e online;
- Cadastro e controle de produtos;
- Entrada e saída de estoque;
- Registro de pedidos;
- Controle de pagamentos e comprovantes;
- Consulta de históricos;
- Notificações sobre pedidos, pagamentos e estoque baixo;
- Controle de usuários e permissões.

3. Requisitos funcionais

Código| Requisito
RF01| Cadastrar e consultar clientes.
RF02| Consultar histórico de clientes e vendas.
RF03| Cadastrar e consultar produtos.
RF04| Registrar entradas e saídas de estoque.
RF05| Consultar quantidade disponível.
RF06| Registrar vendas e seus itens.
RF07| Registrar pedidos online e acompanhar status.
RF08| Registrar pagamentos e comprovantes.
RF09| Consultar históricos de vendas e pedidos.
RF10| Gerar notificações sobre pedidos, pagamentos e estoque baixo.
RF11| Cadastrar usuários e controlar permissões.
RF12| Diferenciar proprietário e funcionários.
RF13| Marcar notificações como lidas.

4. Requisitos não funcionais

- Interface responsiva para celulares;
- Autenticação de usuários;
- Controle de acesso por perfil;
- Armazenamento organizado e consistente;
- Consultas rápidas;
- Proteção das senhas;
- Possibilidade de expansão futura.

5. Regras de negócio

- As vendas podem ser presenciais ou online.
- Toda venda deve registrar os produtos vendidos.
- A saída de produtos deve atualizar o estoque.
- Pedidos online podem possuir comprovante de pagamento.
- O sistema deve acompanhar o status de pedidos e pagamentos.
- Deve haver alerta de estoque baixo.
- Informações administrativas e financeiras devem ser restritas ao proprietário.
- O sistema deve possuir perfis de proprietário e funcionário.
- A utilização deve priorizar dispositivos móveis.

6. Entidades principais

- Cliente;
- Produto;
- Estoque;
- Venda;
- Item_Venda;
- Pedido;
- Pagamento;
- Usuário;
- Notificação.

Principais atributos

Cliente: id, nome, telefone, e-mail, endereço e data de cadastro.
Produto: id, nome, descrição, categoria, tamanho, cor, preço e status.
Estoque: id, produto, quantidade atual, estoque mínimo e atualização.
Venda: id, cliente, usuário, data, valor total e status.
Item_Venda: id, venda, produto, quantidade, preço unitário e subtotal.
Pedido: id, cliente, data, valor total, status e observação.
Pagamento: id, venda/pedido, valor, forma, parcelas, status, comprovante e data.
Usuário: id, nome, e-mail, senha, perfil e status.
Notificação: id, usuário, tipo, mensagem, data e status de leitura.

7. Relacionamentos

- Cliente realiza pedidos e vendas;
- Produto possui estoque;
- Venda possui itens;
- Produto participa de itens de venda;
- Venda e pedido podem possuir pagamentos;
- Usuário registra vendas;
- Usuário recebe notificações.

8. Arquivos do DER

- "DER_Coruja_Surf.pdf" (./DER_Coruja_Surf.pdf)
- "DER_Coruja_Surf_Conceitual.xlsx" (./DER_Coruja_Surf_Conceitual.xlsx)

O DER representa entidades, atributos, relacionamentos e cardinalidades.

9. Justificativa técnica

A modelagem foi criada para organizar os processos atualmente manuais da Coruja Surf. As entidades representam clientes, produtos, estoque, vendas, pedidos, pagamentos, usuários e notificações.

A separação entre proprietário e funcionário atende à necessidade de restringir informações administrativas e financeiras. O modelo também considera vendas online, controle de estoque, históricos, notificações e uso em dispositivos móveis.

10. Uso de Inteligência Artificial

Foi utilizado o ChatGPT para:

- Organizar o README;
- Estruturar requisitos e regras de negócio;
- Organizar o dicionário de dados;
- Revisar o texto.

As informações foram baseadas no levantamento realizado com a organização. Dados não informados não foram inventados e deverão ser validados posteriormente.

11. Critérios atitudinais

- Participação;
- Comprometimento;
- Colaboração;
- Autonomia.

A participação também pode ser verificada pelo histórico de commits do GitHub.

12. Arquivos do projeto

Arquivo| Descrição
"README.md"| Documentação da entrega
"DER_Coruja_Surf.pdf"| Diagrama Entidade-Relacionamento
"DER_Coruja_Surf_Conceitual.xlsx"| Modelo conceitual
"Relatorio_Levantamento_Requisitos_Coruja_Surf.pdf"| Relatório de requisitos
"dicionario_de_dados_coruja_surf.pdf"| Dicionário de dados
"dicionario_de_dados_coruja_surf.md"| Dicionário em Markdown

13. Pendências

- CNPJ;
- Endereço e contato;
- Site ou rede social;
- Integrações;
- Funcionalidades essenciais;
- Critérios de sucesso;
- Regras detalhadas de pagamentos, estoque e permissões;
- Necessidade de relatórios.

Entrega final

A Entrega 1 é composta pelo "README.md" e pelo DER anexado ao GitHub. O projeto representa as principais necessidades da Coruja Surf e servirá de base para as próximas etapas.





<img width="1768" height="2948" alt="DER_Coruja_Surf_DIAGRAMA" src="https://github.com/user-attachments/assets/0ce6de63-ccaa-4ef1-81b5-ca6dad7768e2" />








