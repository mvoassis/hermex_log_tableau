# Hermex log - Data Analysis - BI

> Alura's 3rd BI Challenge 

## 
A empresa Hermex necessita analisar dados sobre a logística das entregas do seu negócio.

Foram disponibilizados os dados contidos no banco de dados quanto às informações das entregas, bem como a identidade visual da empresa.

Os resultados podem ser acessados em: [Tableau Dashboard](https://public.tableau.com/app/profile/marcos.assis6468/viz/ChallengeBISem2/Hermexlog-Dashboard?publish=yes)

## Ferramentas

- Python - Limpeza dos dados.
- Tableau - Análise de dados.

## Objetivos

Criar um ou mais dashboards que avaliem:

* Entregas feitas no prazo.
* Entregas atrasadas
* Número de veículos disponíveis.
* Ship to Door (S2D) em dias.
* Entregas por estado.
* Nível médio de Estoque por ano.

## Dashboards

Foram implementados 3 dashboards, relativos a:

1. Visão geral.
2. Produtos
3. Pedidos em Trânsito. 

### Visão geral:

Neste dashboard, são avaliados todas as informações requeridas nos objetivos do projeto (destacados acima).

Nessa view, o campo "Delivery Status" pode ser utilizado como filtro. Com isso, é possível identificar que o S2D médio é de 10 dias para entregas no prazo e 20 dias para entregas atrasadas. 

Além disso, pode-se observar que a quantidade média de produtos em estoque tem crescido ano a ano. 

Por fim, o mapa do Brasil ilustra a quantidade de pedidos por estado. Pode-se observar que os estados de São Paulo e Rio de Janeiro concentram a maior quantidade de pedidos da empresa. Além disso, este mapa também funciona como filtro, podendo-se avaliar por estado as entregas on time, atrasadas e S2D médio.

### Produtos

Esse dashboard traz informações adicionais relativas a produtos.

Foram identificados 147,924 produtos descategorizados, bem como 10 diferentes categorias não presentes no banco de dados da empresa. Pode representar uma base de dados desatualizada, ou registros de pedidos com referência errada a produtos. 

Além disso, essa view destaca as categorias dos produtos mais vendidos, e as categorias de produtos mais lucrativas.

Finalmente, no mapa do Brasil é possível identificar a categoria de produtos mais popular por Estado, bem como a quantidade de pedidos da mesma. 

### Pedidos em Trânsito

Esse dashboard traz informações adicionais relativas a pedidos em trânsito.

Foram identificados 3,757 produtos em trânsito. Além disso, mesmo havendo 3 tipos de veículos disponíveis para entregas na empresa (Caminhonete, Carro e Moto), 100% dos pedidos em trânsito estão atribuídos a motos.

O mapa do Brasil funciona como filtro, e destaca a quantidade de pedidos em trânsito por estado. Novamente, São Paulo e Rio de Janeiro são os estados com maior quantidade de produtos em trânsito. 

Por último, o gráfico mais a baixo ilustra a quantidade de entregas esperadas por dia nos meses avaliados (Março e Maio de 2021). Pode-se observar que a quantidade de entregas em abril é superior a maio no país. Ao se selecionar um estado específico no mapa, é possível identificar a expectativa de entregas por dia para cada estado separadamente. 

