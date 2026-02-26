# Dados_Python-Alura
📊 Dashboard de Salários na Área de Dados Este projeto consiste em um dashboard interativo desenvolvido em Python para análise de análise na área de dados (Data Science, Data Engineering, Data Analysis, etc.). O projeto foi desenvolvido no contexto da Imersão Dados com Python da Alura.

# 🎯 Objetivo
O objetivo principal é explorar e visualizar dados salariais históricos, permitindo identificar tendências específicas em:

- Nível de senioridade (Júnior, Pleno, Sênior, Executivo).
- Tipo de contrato (Integral, Freelancer, etc.).
- Tamanho da empresa.
- Localização geográfica.

# 🛠 Tecnologias Utilizadas
- Python 3 : Linguagem principal.
- Pandas : Para manipulação, limpeza e análise de dados.
- Streamlit : Framework para criação do dashboard web interativo.
- Plotly Express : Para criação de gráficos interativos (barras, histogramas, mapas, pizza).
- Seaborn/Matplotlib : Utilizados na etapa de análise exploratória ( dados_python.py).
# 📂 Estrutura do Projeto
- Dashboard.py/app.py : Código fonte da aplicação Streamlit. Contém lógica de interface, filtros laterais e renderização de gráficos.
- dados_python.py: Roteiro contendo a Análise Exploratória de Dados (EDA) e pré-processamento. Este arquivo reflete o conteúdo das aulas (limpeza de dados, renomeação de colunas, tratamento de valores nulos e primeiros gráficos).
- dados-imersao-final.csv: Fonte de dados utilizada pelo dashboard (carregada via URL no código).

# 🚀 Como Executar
1. Pré-requisitos
Certifique-se de ter o Python instalado. Em seguida, instale as bibliotecas possíveis:

    *pip install pandas streamlit plotly seaborn matplotlib*

3. Executando o Dashboard
Navegue até a pasta do projeto no seu terminal e execute o comando do Streamlit apontando para o arquivo principal:

     *streamlit run app.py*

    O painel será aberto automaticamente no seu navegador padrão https://dados-python-j2026.streamlit.app/

# 📈 Funcionalidades do Dashboard

1.Filtros Laterais : Permite filtrar os dados por Ano, Antiguidade, Tipo de Contrato e Tamanho da Empresa.

2.KPIs (Métricas) : Exibe Salário Médio, Salário Máximo, Total de Registros e Carga mais frequentes.

3.Gráficos :
  - Top 10 cargas por salário médio.
  - Distribuição de anual anual (Histograma).
  - Proporção de tipos de trabalho (Remoto, Híbrido, Presencial).
  - Mapa coroplético com salário médio por país.
    
4.Tabela de Dados : Visualização detalhada dos dados filtrados.

Desenvolvido durante a Imersão de Dados com Python - Alura.


