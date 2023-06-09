# Experimento Neptune
Case proposto para testar as habilidades de análises de dados no ramo de adquirência.

## [Contexto](https://github.com/mathara/Adquirencia_SUP/blob/d55682ce68845bfa4d9983ed38aa8c3d7eaaf27c/in/Experiment%20Case%20-%20Setup.pdf)

A marca SUP lançou o experimento na cidade de Neptune, no dia 17/05/21.
O experimneto aplica uma nova proposta de valor e devemos avaliar os impactos nos principais KPIs.

O experimento consiste em dar uma alta taxa de desconto se o **comerciante**(nosso cliente, dono da maquininha de cartão) tiver um 
**TPV(Volume Total Pago) mensal acima de R$12,000**.

### Hipóteses

- Aumento de vendas devido aos descontos
- Aumento da média do TPV devido aos novos comerciantes em Neptune ( i.e. se darmos um alto desconto para clientes com um TPV grande, 
nós iremos atrair mais deles e o nosso TPV médio em Neptune, será maior).

<!--
### Observações

*TPV:* é o volume total de vendas(em R$) no qual o comerciante usa a maquinhinha SUP.

*Sale Date:* é a data no qual o comerciante compra a maquinhinha SUP. 

*Nível de TPV:* os comerciantes tem diferentes níveis de TPV ao longo da vida, sendo as primeiras 
semanas após a data de compra( i.e. sale date), normalmente, as que apresentam os menores níveis de
TPV.
-->

**Desafio:** Os comerciantes que já possuem um relacionamento conosco não será afetado pelas novas taxas.
Como você irá separar o TPV dos comercianes antigos daqueles afeados pelo experimento?

## Perguntas levantadas

- A campanha foi efetia?
  - As vendas aumentaram?
  - Aumentamos o TPV Médio?
  - Aumentamos os números de comerciantes?
    - Atraímos os clientes público-alvo da campanha?
  - Aumentamos o TPV total em Neptune?
- Como foi a performance de Neptune?
  - Antes e depois do exerimento?
  - Em vista das outras cidades no mesmo período de tempo? 


## Dados Analisados

Os dados recebidos para esse estudo e as intruções se encontram na pasta [in](/in/), caso você tennha interesse em realizar esse estudo.

### Estrutura de dados no PowerBI
![Estrutura Relacionamento das Tabelas](bau/Estrutura.PNG)


Aprofudando um pouco na estrutura, podemos ver algumas separações:
- Tabelas Principais
  - *Merchant:* compra de máquina por cliente
  - *TPV:* transacional de pagamento
- Tabela Auxiliar
  - *Merchant_Cad:* Cadastro único do Comerciante
- Medidas

### Dashboard
![Painel de Campanha](bau/SUP_video.gif)
Acesse aqui o [Dashboard](https://bit.ly/MMA_CampanhaNeptune).

## Ferramentas Utilizadas

- Excel
- Power BI
- Power Point
- Think-cell [lincense 60 trial](https://www.think-cell.com/en/product/firmlearning?utm_campaign=firmlearning-22-1483-1&utm_source=firmlearning&utm_medium=youtube&utm_content=&utm_id=firmlearning-22-1483)

## Resultados
![Painel de Campanha](bau/SUP_CE_video.gif)

A campanha em Neptune foi um sucesso, devido:
- Crescimento médio de clientes ativos e transacionando de 670% e 563%,
respectivamente, após a campanha. Objetivo: Diminuir a
diferença entre clientes ativos e transacionando
- Crescimento de vendas de máquinas e novos clientes de 280% e 222%,
respectivamente, em relação a média das demais cidades, sem o foco da
campanha
- O público alvo desta campanha chegou a representar 55,3% do TPV Total na
semana. Devemos acompanhar a recorrência e o churn semanalmente
- O público alvo aumentou, em média, 46% do TPV médio geral. À medida que
perdemos esse público, a média geral tende a se aproximar daquela fora da
campanha


Material de consulta [Apresentação Executiva Final](out_resultado/Case_Neptune.pdf).
