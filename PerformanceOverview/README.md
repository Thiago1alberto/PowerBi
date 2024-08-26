# Northwind Dashboard em Power BI

Este repositório contém o projeto de um dashboard desenvolvido em Power BI utilizando a base de dados Northwind. O objetivo deste dashboard é fornecer insights valiosos sobre o gerenciamento de estoque, receitas, despesas, e o desempenho geral dos funcionários.

## Visão Geral do Projeto

![image](https://github.com/user-attachments/assets/6e83a64e-1ae7-4203-8394-1dc7ffa19c08)

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
![Captura de tela 2024-08-25 142501](https://github.com/user-attachments/assets/ac1e6eba-750a-4270-b41d-6cc25c5d7ccb)
Foram criadas associações entre todas as tabelas relevantes para garantir a integridade dos dados e permitir análises abrangentes:

- **Orders** foi associado com **Customers**, **Employees**, **Shippers**, e **Order_Details**.
- **Order_Details** foi associado com **Products**.
- **Products** foi associado com **Suppliers** e **Categories**.
- **Employees** foi associado com **Employee_Territories**, **Territories** e **Regions**.

## Insights e Conclusões

Este dashboard revela que alguns produtos estão sofrendo com a falta de gerenciamento de estoque, resultando em problemas que podem impactar diretamente as vendas e a satisfação do cliente. A análise dos dados destaca a necessidade de uma estratégia mais eficaz de controle de estoque para evitar a perda de vendas devido à indisponibilidade de produtos.
