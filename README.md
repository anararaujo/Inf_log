# Inf_log
Aprendizado - Informática ![image](https://github.com/user-attachments/assets/f4ecc483-ba91-40b9-9d87-cb306bae945e)



## Primeira atividade: Apresentação pessoal - Canva 
https://www.canva.com/design/DAGfsex8VIQ/8NZGxdBi9XK3lM1DvZFG5A/edit?utm_content=DAGfsex8VIQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
![image](https://github.com/user-attachments/assets/6a3ea5d9-8aec-45fb-b8c5-b95dc1fb409b)

## Segunda atividade: Fórmulas Básicas
Elaboração de gráficos no Excel.
![image](https://github.com/user-attachments/assets/1ab51ef2-d157-4d9b-bc9e-a2b8c966afec)
![image](https://github.com/user-attachments/assets/9f88b941-05ee-4315-9a2e-3686ea863062)

https://fatecspgov-my.sharepoint.com/:x:/r/personal/ana_tome2_fatec_sp_gov_br/Documents/Arquivos%20de%20Chat%20do%20Microsoft%20Teams/DADOS%20ABERTOS%20CA%C3%87APAVA%2008-047.xlsx?d=w40573e8bad0242118b722a9f105354c7&csf=1&web=1&e=H06GLY

## Terceira atividade: Trabalhando com Dados abertos 
Levantamento de dados abertos do GOV e composição de gráficos por meio do dashboard do Power BI
https://app.powerbi.com/groups/me/dashboards/547f13b5-37a4-432e-a7e0-a27466664edb?experience=power-bi

![image](https://github.com/user-attachments/assets/2a4ebcac-be1c-4665-badc-698508237550)

## Quarta Atividade: Fórmulas no Excel (SOMASE, CONTSE e SOMA)
Após orientações da professora Adriana, trabalhamos com o levantamento de dados abertos do Portal da Transferência da cidade de Caçapava e tratamento dos dados utilizando as fórmulas básicas do Excel.

https://fatecspgov-my.sharepoint.com/:x:/g/personal/ana_tome2_fatec_sp_gov_br/EYs-V0ACrRFCi3IqnxBTVMcBJF2EB5YytnlbeKABNPkGIA
![image](https://github.com/user-attachments/assets/a609d954-de5d-4d4d-ac60-47b76a0198aa)

## Quinta atividade: Dados abertos no Power BI
Após o levantamento dos dados, elaboramos um dashboard com um três gráficos sobre a quantidade de funcionários da Prefeitura de Caçapava por secretaria, funções e nível de escolaridade.
![image](https://github.com/user-attachments/assets/adb9400d-0810-48b5-9043-0407c1a592c0)

https://app.powerbi.com/groups/me/reports/b47d9a70-f558-4913-a06e-96317d8c7c74/c32ca6e1cd7028bb55d6?experience=power-bi

## Sexta atividade: (Faltei no dia)

## Sétima atividade: Previsão de Consumo de Cerveja com Regressão Linear

Nesta tarefa o objetivo era prever o consumo de cerveja em uma área universitária de São Paulo utilizando a técnica de **Regressão Linear Múltipla**, com base em variáveis climáticas e de calendário.

- Fonte de dados: [Kaggle - Beer Consumption São Paulo](https://www.kaggle.com/datasets/dongeorge/beer-consumption-sao-paulo)
- Número de registros: 365 dias
- Variável dependente: `Consumo de cerveja (litros)`
- Variáveis independentes:
  - `Temperatura Media (C)`
  - `Precipitacao (mm)`
  - `Final de Semana` (1 = sim, 0 = não)

---

## 🧪 Etapas do Projeto

1. **Importação e limpeza dos dados**
2. **Seleção de variáveis relevantes**
3. **Separação em conjunto de treino e teste**
4. **Treinamento do modelo com `LinearRegression()`**
5. **Avaliação do desempenho com R², MAE e MSE**
6. **Visualização dos resultados (gráfico Real vs Previsto)**

---

## 📌 Resultados

- **R² (coeficiente de determinação)**: `~0.76` *(pode variar)*
- **MAE (Erro médio absoluto)**: `~1500 litros` *(aproximadamente)*
- O modelo se mostrou eficaz para prever o consumo com base em temperatura, chuva e fim de semana.

## **RESPOSTAS**
1. Os dois modelos não são iguais, pois o Excel é bem mais simples, já o python permite uma visão mais completa, onde elaboramos testes e divisão treino/teste e mais métricas (MAE, MSE).
2. Depende do tipo de análise que eu estou buscando, se fosse uma análise mais simples usaria o Excel. Agora, se eu precisasse de algo mais completo, optaria pelo Python.
3. O modelo do artigo é mais profundo: testa a significância dos dados, analisa resíduos, e verifica se o modelo é estatisticamente válido. Já o modelo que fiz foca só na previsão.

![image](https://github.com/user-attachments/assets/6d0667d8-eea2-4a44-9f0e-c3df1fdacba8)

![image](https://github.com/user-attachments/assets/97caaf22-8a84-4fb0-9259-83ef95a1d60b)

# Previsão de Preços de Imóveis com Regressão Linear

## 🔗 Fonte dos Dados

Os dados foram obtidos do Kaggle:  
[https://www.kaggle.com/greenwing1985/housepricing](https://www.kaggle.com/greenwing1985/housepricing)

## 🔧 Ferramentas Utilizadas

- **Microsoft Excel**: Aplicada a função `PREVISÃO.LINEAR` para projeções simples de preços.
- **Python (Google Colab com AI Gemini)**:
  - Análise exploratória dos dados
  - Modelo de Regressão Linear Múltipla com `scikit-learn`
  - Visualizações com `matplotlib` e `seaborn`

## 📁 Estrutura dos Dados

As variáveis utilizadas são:

- `preços`: Preço do imóvel (variável dependente)
- `área`: Área construída do imóvel (m²)
- `garagem`: Número de vagas de garagem
- `banheiros`: Número de banheiros
- `lareira`: Número de lareiras
- `mármore`: Possui acabamento em mármore branco (1 = si

![image](https://github.com/user-attachments/assets/fbbd9fb8-d07c-4c58-86aa-acd50ffa468e)
![image](https://github.com/user-attachments/assets/62213570-a616-4996-89ee-d4aa58dd44ab)

## Oitava atividade: Projeção de vendas 

Nesta atividade, fiz a análise dos dados das empresas de panela de três empresas e baseando-se nestes para definir a projeção de vendas, receita e lucor, após isso foi feito o gráfico de dispersão que demonstra visualmente as análises obtidas.

*Empresa de Panela de Pressão*

![image](https://github.com/user-attachments/assets/0783afd6-5b57-4c07-a44e-da77540d95b5)

*Empresa confidencial*

![image](https://github.com/user-attachments/assets/77ca40c2-5c28-4377-95d7-92502c0e85d0)

*Empresa de Sorvetes* 

![image](https://github.com/user-attachments/assets/53846cb3-67e1-44da-8080-ce17e7c932ec)




