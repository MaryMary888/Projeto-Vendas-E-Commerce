## Objetivo do Projeto:
<p>Realizar a junção (JOIN) de duas tabelas utilizando SQL para consolidar as informações. Exportar os dados resultantes para um arquivo CSV. Desenvolver um dashboard interativo e informativo para visualização das principais métricas e insights do e-commerce.</p>

---

## Tabelas Disponibilizadas:
- **Tabela de Transações:** Contém os registros de transações realizadas pelos clientes, incluindo detalhes como ID da transação, valor e outros.
- **Tabela de Dados Pessoais:** Contém as informações pessoais dos clientes, como ID do cliente, nome, genero, cidade, etc.
- **Chave de Ligação:** As tabelas se relacionam através da coluna ID_CLIENT, que é a chave identificadora dos clientes.
---

### Decisão para qual tipo de Join utilizar:
<p>O Inner Join será utilizado para a construção do dashboard, pois o foco principal do mesmo é observar as transações válidas, ou seja, os registros completos das transações dos clientes baseados nas demais métricas, como gênero e estado. Caso Left, Right ou Full Join fossem utilizados, as colunas com valores vazios teriam certo impacto nos resultados do dashboard como o valor médio gasto pelos clientes por estado.</p>

---

## Dasboard: 
Link para Visualizar resultado no [Looker Studio](https://lookerstudio.google.com/reporting/57037706-0678-4636-9033-2f2ecc8713ee).
