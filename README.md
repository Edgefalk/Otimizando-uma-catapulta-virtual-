O objetivo deste projeto é utilizar os princípios de Design de Experimentos (DOE) para otimizar o desempenho de uma catapulta virtual, disponível em https://sigmazone.com/catapult/. O objetivo é encontrar as configurações ótimas da catapulta para atingir uma distância-alvo específica.
Etapas do Projeto:
A primeira etapa do projeto é entender como a catapulta funciona e quais variáveis podem ser controladas. Utilizando o simulador de catapulta para se familiarizar com as variáveis de controle e vendo como elas afetam a distância que a catapulta pode lançar.
depois de entender o problema, o próximo passo é projetar o experimento. Para isso, você precisará determinar quantos níveis você deseja para cada fator, quantas repetições você vai realizar e em que ordem você vai realizar os experimentos. Você pode começar com um fatorial completo, seguido por um fatorial fracionário, se necessário.
 Após o design, é realizado o experimento, mudando as variáveis de acordo com o design e registrando a distância alcançada para cada configuração.
 Depois de coletar os dados, os mesmom são analizadoss. Utilizando a biblioteca `pyDOE2` para realizar a análise de variância (ANOVA) e outras análises necessárias para identificar os fatores mais importantes.
 e por fim a otimização é feita.
