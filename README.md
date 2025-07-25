# MVP Análise de Dados e Boas Práticas

# Descrição do Problema
Este conjunto de dados contém dados sobre mortalidade por câncer de pulmão e é uma coleção abrangente de informações sobre pacientes, com foco específico em indivíduos diagnosticados com câncer. Este conjunto de dados contém informações abrangentes sobre 222.684 indivíduos relacionadas ao diagnóstico, tratamento e desfechos do câncer de pulmão. Com 17 colunas bem estruturadas, este conjunto de dados em larga escala foi projetado para auxiliar pesquisadores, cientistas de dados e profissionais de saúde no estudo de padrões, na construção de modelos preditivos e no aprimoramento de estratégias de detecção precoce e tratamento.

# Hipóteses do Problema
As hipóteses traçadas são as seguintes:

O índice de massa corporal do paciente, O nível de colesterol do paciente, a hipertensão arterial e a sobrevivência tem "correlação"?

Considerando idade (jovens, adultos, idosos), quais grupos demográficos são mais vulneráveis ao câncer de pulmão?

Taxa de sobrevida por tipo de tratamento com grupo etário (jovens, adultos, idosos)?

O projeto é composto por dois arquivos:<br>

   - cancer_pulmao.csv: Este arquivo contém o conjunto de dados.

   - MVP_boas_praticas.ipynb: Este é um arquivo de notebook Python, que  contém o código e a análise do projeto.

<a href="https://github.com/EdnilsonBastos/Analise_exploratoria/blob/main/MVP_boas_praticas.ipynb">Notebook do código do projeto</a>.<br><br>

# Conclusão
A análise e pré-processamento do dataset câncer de pulão demonstram a importância de entender a estrutura dos dados antes da modelagem. O dataset é limpo, normalizado, padronizado e algumas colunas sofrem o processo de ***One-hot encoding**. A análise exploratória revelou correlações importantes entre as características bmi e cholesterol_level a visualização do gráfico de hetmap demonstrou que há uma forte correlação positiva entre BMI e Cholesterol_level. O gráfico de barras reitera que a taxa de sobrevivência é mais elevada na faixa etária de "Meia idade" em comparação com os grupos "Jovem" e "Idoso". gráfico de barras empilhada é útil para entender como os diferentes tipos de tratamento se distribuem entre os grupos etários. A "Meia idade" se destaca por uma maior proporção de cirurgia, e há pequenas variações na radioterapia, enquanto a quimioterapia e o tratamento combinado são mais uniformes entre os grupos. As etapas de normalização, padronização e one-hot encoding são fundamentais para preparar os dados para diversos algoritmos de aprendizado de máquina, garantindo que o modelo possa aprender eficientemente com as relações presentes nos dados.

# As três hipóteses levantadas foram validadas:

O índice de massa corporal do paciente, O nível de colesterol do paciente, a hipertensão arterial e a sobrevivência têm correlação? Sim, entre as características bmi e cholesterol_level a visualização do gráfico com hetmap demonstrou que há uma forte correlação positiva entre BMI e Cholesterol_level, os demais atributos não demonstram correlação.

Considerando idade (jovens, adultos, idosos), quais grupos demográficos são mais vulneráveis ao câncer de pulmão? O gráfico de barras reitera que a taxa de sobrevivência é mais elevada na faixa etária de "Meia idade" em comparação com os grupos "Jovem" e "Idoso". Os grupos "Jovem" e "Idoso" têm taxas de sobrevivência muito próximas entre si e são as mais baixas.

Taxa de sobrevida por tipo de tratamento com grupo etário (jovens, adultos, idosos)? O gráfico de barras empilhadas foi útil para entender como os diferentes tipos de tratamento se distribuem entre os grupos etários. A "Meia idade" se destaca por uma maior proporção de cirurgia, e há pequenas variações na radioterapia, enquanto a quimioterapia e o tratamento combinado são mais uniformes entre os grupos.


