📊 Análise do Consumo de Energia Elétrica no Brasil

Este projeto realiza uma Análise Exploratória de Dados (EDA) do consumo de energia elétrica no Brasil, com foco na identificação e comparação dos períodos de retração do consumo observados nos anos de 2008–2009, 2014–2016 e 2019–2020.
O objetivo é entender como diferentes tipos de consumo contribuíram para cada uma dessas crises, utilizando dados oficiais do setor elétrico brasileiro.

🎯 Objetivo do Projeto

Analisar a evolução do consumo de energia elétrica ao longo dos anos
Identificar períodos de queda no consumo agregado
Avaliar a contribuição de cada tipo de consumo (Residencial, Comercial, Industrial e Outros) nas diferentes crises
Comparar padrões entre crises de naturezas distintas (financeira, econômica doméstica e pandêmica)


🗂️ Fonte dos Dados

Origem: Ministério de Minas e Energia (MME) / ANEEL
Base: Dados oficiais do consumo de energia elétrica por UF e tipo de consumo
Frequência: Mensal
Unidade: MWh

Os dados foram tratados para garantir consistência analítica, sendo excluídas categorias agregadas com valores ausentes de número de consumidores (como Total e Cativo).

🧠 Metodologia
As principais etapas da análise foram:


Tratamento e verificação dos dados

Identificação e análise de valores ausentes
Seleção dos tipos de consumo com dados consistentes



Análise da evolução temporal

Agregação do consumo anual
Identificação visual dos períodos de retração



Análise das crises

Comparação entre anos pré-crise e anos de contração
Cálculo da variação absoluta do consumo
Decomposição da variação total por tipo de consumo



Visualização dos resultados

Gráficos de linha para evolução temporal
Gráficos de barras com eixo zero para análise de contribuição setorial




📈 Principais Resultados
🔻 Crise de 2008–2009 (Crise Financeira Global)

A queda foi predominantemente puxada pelo setor industrial
O consumo residencial apresentou comportamento contracíclico, amortecendo parcialmente a retração
O choque teve forte impacto sobre a atividade produtiva

🔻 Crise de 2014–2016 (Crise Econômica Doméstica)

Novamente, o setor industrial foi o principal responsável pela queda
O setor comercial também contribuiu para a retração
O consumo residencial mostrou resiliência, mas sem papel contracíclico relevante

🔻 Crise de 2019–2020 (Pandemia de Covid‑19)

A retração foi puxada principalmente pelo setor comercial
O setor industrial teve impacto secundário
O consumo residencial apresentou forte comportamento contracíclico, evidenciando a realocação do consumo para os domicílios


✅ Conclusão
A análise evidencia que o consumo de energia elétrica reflete de forma sensível a natureza das crises econômicas.
Enquanto as crises de 2008–2009 e 2014–2016 estiveram associadas a choques produtivos e à queda da atividade industrial, a crise de 2019–2020 apresentou um padrão distinto, fortemente ligado à interrupção de atividades presenciais e à mudança no comportamento da sociedade.
A decomposição da variação do consumo por tipo mostrou-se uma ferramenta eficaz para compreender essas diferenças, oferecendo insights relevantes para análise econômica, planejamento energético e gestão de risco.

🛠️ Tecnologias Utilizadas

Python
pandas
matplotlib
seaborn
Jupyter Notebook


📁 Estrutura do Repositório
analise-consumo-energia-brasil/
├── README.md
├── dados_brutos/
│   └── br_mme_consumo_energia_eletrica_uf.csv.gz
├── notebooks/
│   └── analise_consumo_energia.ipynb
├── imagens/
│   ├── grafico_2008_2009.png
│   ├── grafico_2014_2016.png
│   └── grafico_2019_2020.png


👤 Autor
Anderson Ferreira de Paula
🎓 Estudante de Ciência de Dados – UNIVESP
📍 Belo Horizonte – MG
