![image](https://github.com/PabloNeri66/Distribui-oDePossion/assets/89610356/bbb16b69-5d12-451f-b4ef-88e71420c749)
#_Análise de Gols na Premier League 2022/23 com Distribuição de Poisson_#


Descrição do Projeto
Este projeto realiza uma análise estatística do número de gols por partida na Premier League 2022/23, utilizando a Distribuição de Poisson para modelar e prever a frequência de gols. A análise é feita com base em dados históricos e busca identificar padrões que podem ser úteis para previsões e apostas.

Motivação
O uso da Distribuição de Poisson em análises de gols por partida é comum, pois essa distribuição é eficaz para modelar eventos que ocorrem com uma média conhecida em um intervalo de tempo fixo (neste caso, gols em uma partida). Este projeto fornece insights sobre a probabilidade de diferentes contagens de gols para o time mandante e o visitante, facilitando o entendimento das médias observadas e ajudando em previsões.

Tecnologias Utilizadas
O projeto foi desenvolvido com as seguintes bibliotecas do Python:

Pandas: Manipulação e análise de dados.
Matplotlib: Criação de gráficos e visualizações.
Seaborn: Visualização de dados estatísticos.
NumPy: Cálculos matemáticos, especialmente para distribuições.
Resultados e Análise
O gráfico abaixo (gerado no projeto) compara a porcentagem de gols por partida entre times mandantes e visitantes com as linhas da Distribuição de Poisson para cada caso.


Legenda:
Vermelho: Gols do time mandante.
Verde: Gols do time visitante.
Linhas pontilhadas: Distribuição de Poisson para cada caso.
Interpretação
A linha de Poisson ajuda a visualizar como a distribuição se ajusta aos dados de gols reais. Observa-se, por exemplo, que existe aproximadamente 31% de chance de uma partida terminar com 1 gol para o time mandante (conforme a linha de Poisson). Esse valor corresponde aos padrões observados no campeonato.

Contribuição
Contribuições são bem-vindas! Se você quiser melhorar a análise ou adicionar novas funcionalidades, fique à vontade para abrir uma issue ou enviar um pull request.

Licença
Este projeto é distribuído sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

