# Análise probabilística da chuva em Santa Helena - PR
Este projeto apresenta os códigos e dataset utilizados para análise dos dados para construção do artigo intitulado **"Modelagem probabilística da precipitação pluvial em diferentes escalas temporais para Santa Helena, Paraná"**.
As análises foram realizados no Google Colab.
# Como citar?
Oliveira, F. C.; Sobucki, L.; Thomaz, D. V.; Giovanella, T. H.; Rocha, A. S. Modelagem probabilística da precipitação pluvial em diferentes escalas temporais para Santa Helena, Paraná. **Revista Brasileira de Geografia Física** v.18, n.02, 2025. [https://doi.org/10.26848/rbgf.v18.2.p1527-1542](https://doi.org/10.26848/rbgf.v18.2.p1527-1542)
# Resumo do artigo
A precipitação é um fenômeno que varia espacial e temporalmente. Visando contribuir com tomadas de decisões mais assertivas e sustentáveis no gerenciamento dos recursos hídricos, torna-se necessário identificar a função de densidade de probabilidade que melhor caracterize os eventos de precipitação, considerando diferentes escalas de tempo. Assim, o objetivo deste trabalho foi determinar a precipitação provável em Santa Helena, Paraná, utilizando modelagem probabilística em escalas anual, mensal e decendial, com diferentes probabilidades de ocorrência de valores extremos, e identificar a Função de Distribuição de Probabilidade (FDP) que melhor se ajusta aos dados objetivo deste trabalho foi determinar a precipitação provável em escala anual, mensal e decendial com várias probabilidades de ocorrência de valores extremos, selecionando a melhor função de densidade de probabilidade para Santa Helena, Paraná. Foram utilizados dados diários de precipitação de um período de 48 anos. As análises foram realizadas em três escalas de tempo: anual, mensal e decendial. Foram analisados os seguintes modelos de distribuição de probabilidade: Normal, Exponencial, Gama e Log-Normal. A avaliação do melhor modelo ajustado foi realizada utilizando o teste de Kolmogorov-Smirnov e determinação do p-valor. A análise probabilística identificou que a função de distribuição de probabilidade que melhor se ajustou foi a Log-Normal para as escalas anual e mensal, e a Exponencial para a escala decendial. O ajuste das funções de probabilidade possibilitou a determinação das chuvas prováveis para as escalas anuais, mensais e decendiais, contribuindo para o monitoramento climático e o planejamento das atividades antrópicas dependentes da precipitação pluvial.
# Conteúdos do repositório
`analises_anual_chuva.ipynb`: contém os códigos para abrir e carregar dados; analisar a tendência anual da chuva; encontrar as funções FDP e FDA; e, determinar a precipitação provável para sete níveis de probabilidade de ocorrência;

`analises_mensal_chuva.ipynb`: contém os códigos para abrir e carregar dados; analisar a tendência mensal da chuva; encontrar as funções FDP e FDA; e, determinar a precipitação provável para sete níveis de probabilidade de ocorrência;

`analises_decendial_chuva.ipynb`: contém os códigos para abrir e carregar dados; encontrar as funções FDP e FDA; e, determinar a precipitação provável para sete níveis de probabilidade de ocorrência;

`dataset_chuva_sh.csv`: contém a série de dados diários chuva de 1976 a 2023, organizados nas seguindas colunas:

| **Coluna**      | **Descrição**                                                                 |
|------------------|-------------------------------------------------------------------------------|
| **Dia**          | Dia de cada ano                                                             |
| **Mês**          | Mês de cada ano                                                            |
| **Ano**          | Ano dos dados                                                              |
| **Chuva (mm)**   | Precipitação pluvial em milímetros                                          |
| **Lat**          | Latitude em graus                                                          |
| **Lon**          | Longitude em graus                                                         |
| **Alt**          | Altitude em metros                                                         |
| **Data**         | Data correspondente a cada dado                                            |

OBS.: Os dados da estação meteorológica são de responsabilidade da Secretaria do Meio Ambiente e Recursos Hídricos do Paraná, representados pelo AGUASPARANÁ por meio do Instituto das Águas do Paraná (IAT) (http://www.sih-web.aguasparana.pr.gov.br/sih-web/gerarRelatorioAlturasDiariasPrecipitacao.do?action=carregarInterfaceInicial)
