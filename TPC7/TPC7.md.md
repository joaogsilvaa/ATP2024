### TPC7

O exercício consiste em desenvolver uma aplicação Python para analisar e manipular dados meteorológicos. Os dados incluem informações diárias sobre temperatura 
mínima, temperatura máxima e precipitação, armazenadas numa tabela. O objetivo principal é implementar um menu interativo que permita realizar diversas operações,
como cálculos, visualizações gráficas e manipulação de ficheiros, com base nos dados fornecidos.

O programa implementado apresenta um menu com várias funcionalidades. Através deste, o utilizador pode calcular a temperatura média diária, guardar os dados 
meteorológicos num ficheiro, carregar dados a partir de um ficheiro, identificar a temperatura mínima mais baixa registada, calcular a amplitude térmica diária,
determinar o dia com a maior precipitação, listar dias com precipitação acima de um determinado valor, encontrar a maior sequência de dias com precipitação
a baixo de um valor especificado e gerar gráficos que representem as temperaturas mínima e máxima, bem como os níveis de precipitação.

A solução foi implementada utilizando funções específicas para cada funcionalidade. Por exemplo, a função Medias calcula as temperaturas médias diárias, 
enquanto a função amplTerm determina a amplitude térmica. Para guardar e carregar os dados meteorológicos, as funções guardaTabMeteo e carregaTabMeteo foram 
implementadas, respetivamente, utilizando o formato de texto para armazenamento. Para analisar padrões de precipitação, as funções diasPrecSup e maxSemChuva 
identificam dias com precipitação superior a um limite e a maior sequência de dias com precipitação inferior a um valor, respetivamente.

Para visualização, a função grafTabMeteo gera gráficos de linha para as temperaturas mínima e máxima e gráficos de barras para os níveis de precipitação, 
utilizando a biblioteca matplotlib.O menu foi implementado de forma iterativa, garantindo que o utilizador pode realizar múltiplas operações antes de sair do 
programa. Cada opção do menu está associada a uma funcionalidade específica, e o programa assegura uma interação intuitiva e eficiente.