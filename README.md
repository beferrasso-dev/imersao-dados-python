Dashboard de Análise de Salários na Área de Dados

Este projeto é um dashboard interativo desenvolvido em Python para explorar e visualizar tendências salariais globais no mercado de dados. A aplicação permite filtrar informações por senioridade, tipo de contrato, ano e tamanho da empresa, fornecendo insights valiosos sobre a remuneração em diferentes cargos e regiões.

Tecnologias Utilizadas:

1. Python: Linguagem principal.
2. Streamlit: Framework para criação da interface web interativa.
3. Pandas: Manipulação e tratamento dos dados.
4. Plotly Express: Criação de gráficos dinâmicos e mapas.

📊 Funcionalidades e Análises
O dashboard está dividido em seções estratégicas para facilitar a interpretação dos dados:

1. Filtros Dinâmicos (Sidebar)
   
Localizados na barra lateral, permitem personalizar toda a visão do dashboard simultaneamente:
Ano: Filtre por períodos específicos.
Senioridade: Analise desde níveis Entry-level até Executive.
Tipo de Contrato: Freelance, Full-time, Part-time ou Contract.
Tamanho da Empresa: Pequena (S), Média (M) ou Grande (L).

2. Indicadores de Performance (KPIs)
   
Exibição direta de métricas fundamentais:
Salário Médio: Média aritmética anual em USD.
Salário Máximo: O maior teto encontrado nos dados filtrados.
Total de Registros: Volume de profissionais analisados.
Cargo Mais Frequente: Identificação do título profissional mais comum na amostra.

3. Visualizações Gráficas
   
Top 10 Cargos: Gráfico de barras horizontais mostrando as funções com as melhores médias salariais.
Distribuição Salarial: Histograma que revela a concentração de salários e identifica possíveis outliers.
Proporção de Trabalho: Gráfico de rosca (donut chart) para visualizar a divisão entre presencial, híbrido e remoto.
Mapa Global de Salários: Mapa coroplético focado no cargo de Data Scientist, mostrando a média salarial por país.
