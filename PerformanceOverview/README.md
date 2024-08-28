# Northwind Dashboard em Power BI

Este repositório contém o projeto de um dashboard desenvolvido em Power BI utilizando a base de dados Northwind. O objetivo deste dashboard é fornecer insights valiosos sobre o gerenciamento de estoque, receitas, despesas, e o desempenho geral dos funcionários.

## Visão Geral do Projeto
<p align="center">
  <img src="https://github.com/user-attachments/assets/85061f31-302b-41b3-8da4-71d60a06ee5f" alt="Dashboard Página 1" width="45%">
  <img src="https://github.com/user-attachments/assets/94094ade-7d30-49ca-b529-6457372287dd" alt="Dashboard Página 2" width="45%">
</p>



O dashboard permite analisar:
- **Receita e Despesa**: Visualização das receitas e despesas totais.
- **Estoque x Pedidos**: Comparação entre o nível de estoque e os pedidos ao longo dos meses.
- **Faturamento por Funcionários**: Avaliação do desempenho dos funcionários em termos de faturamento.
- **Receita por Categoria**: Receita gerada por diferentes categorias de produtos.
- **Tempo de Envio**: Monitoramento do tempo médio de envio dos pedidos ao longo do ano.

## Base de Dados Utilizada

A base de dados Northwind, um clássico exemplo de banco de dados de vendas, foi utilizada para alimentar este dashboard. As seguintes tabelas foram incluídas:

- **Customers**: Informações sobre os clientes.
- **Orders**: Detalhes dos pedidos realizados.
- **Order_Details**: Informações específicas sobre cada produto dentro dos pedidos.
- **Products**: Detalhes dos produtos, como preços e estoque.
- **Categories**: Categorias a que os produtos pertencem.
- **Suppliers**: Informações sobre os fornecedores.
- **Employees**: Dados sobre os funcionários.
- **Shippers**: Detalhes das empresas responsáveis pelo envio dos produtos.
- **Regions, Territories, Employee_Territories**: Informações sobre regiões e territórios atendidos pelos funcionários.

### Associações Criadas
Foram criadas associações entre todas as tabelas relevantes para garantir a integridade dos dados e permitir análises abrangentes:

- **Orders** foi associado com **Customers**, **Employees**, **Shippers**, e **Order_Details**.
- **Order_Details** foi associado com **Products**.
- **Products** foi associado com **Suppliers** e **Categories**.
- **Employees** foi associado com **Employee_Territories**, **Territories** e **Regions**.

## Insights e Conclusões

Este dashboard revela que alguns produtos estão sofrendo com a falta de gerenciamento de estoque, resultando em problemas que podem impactar diretamente as vendas e a satisfação do cliente. A análise dos dados destaca a necessidade de uma estratégia mais eficaz de controle de estoque para evitar a perda de vendas devido à indisponibilidade de produtos.
