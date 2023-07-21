
<p align="center"> 
:construction: <b> PROJETO EM CONSTRUÇÃO... </b> :construction: 
<p>

<div align="center">

![Capturar](https://user-images.githubusercontent.com/92175791/236311942-9745ab4e-9ced-4259-9dba-fa9d078b2e4b.PNG)

</div> 

<div align="center">

:camera: <b> IMAGEM 01: Tabela dos valores, sendo aplicada a opção de Regressão Linear (baseada no notebook anexo) </b> :camera: 

 </div> 


  
## Previsão de Faturamento :chart_with_upwards_trend:

Este é um projeto de previsão de faturamento que utiliza técnicas de Machine Learning para predizer o valor de faturamento para o próximo mês, com base em uma base histórica de dados. O software possui uma interface gráfica desenvolvida em Qt for Python (PyQt5) para facilitar a interação do usuário e permitir a escolha da metodologia de previsão desejada. :computer:

### Funcionamento do Projeto :gear:

O projeto recebe como entrada uma base de dados no formato CSV contendo três colunas: "ano", "mes" e "faturamento". A partir desses dados históricos, o modelo é treinado e capaz de realizar previsões para o próximo mês.

O front end desenvolvido em Qt for Python permite que o usuário escolha a metodologia que deseja utilizar para a previsão. As opções disponíveis são:

1. :bar_chart: **Média:** O modelo utilizará a média dos valores históricos como a previsão para o próximo mês.
2. :chart_with_upwards_trend: **Desvio Padrão:** O modelo utilizará a média mais o desvio padrão dos valores históricos como a previsão para o próximo mês.
3. :bar_chart: **Média Ponderada:** O modelo utilizará uma média ponderada dos valores históricos, onde pesos podem ser atribuídos a diferentes períodos.
4. :chart_with_downwards_trend: **Segunda Derivada dos Dados:** O modelo utilizará uma abordagem de segunda derivada para estimar a tendência do faturamento.
5. :chart_with_upwards_trend: **Regressão Linear:** O modelo realizará uma regressão linear com base nos dados históricos para prever o faturamento futuro.
6. :watch: **Séries Temporais:** O modelo utilizará técnicas de séries temporais para realizar a previsão.

### Como Utilizar :point_down:

1. :package: Instale as dependências necessárias, como PyQt5 e outras bibliotecas Python relevantes.
2. :file_folder: Abra o executável "sistema.py" localizado na pasta "QT_faturamento" para iniciar a interface gráfica.
3. :file_folder: Selecione a base de dados CSV contendo as colunas "ano", "mes" e "faturamento".
4. :bulb: Escolha a metodologia de previsão desejada através dos botões disponíveis.
5. :arrow_forward: Pressione o botão de previsão para obter o resultado.

### Observações :memo:

- :notebook: O projeto possui um notebook anexo, utilizado como base para o desenvolvimento das fórmulas de previsão.
- :warning: O código em python do arquivo "sistema.py" utiliza trechos de fórmulas retirados do notebook, onde são coletadas apenas as equações ou chamadas dos recursos das bibliotecas utilizadas.
- :warning: Este é um protótipo inicial e o projeto pode ser expandido para incluir outras metodologias de previsão e melhorias na interface gráfica.
