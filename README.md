O objetivo de um sistema de controle de uma suspensão ativa automotiva é manter o movimento
relativo entre as rodas e o chassi (ou monobloco) do veículo dentro de parâmetros estabelecidos.
Isto permite que o sistema de suspensão forneça melhores características de conforto ou de
aderência em relação a um sistema passivo comum, utilizando sensores, central eletrônica e
atuadores. 

Para este projeto, um modelo matemático simplificado foi obtido considerando apenas a dinâmica 
vertical de um modelo físico de dois graus de liberdade com excitação por movimento da base. 
O projeto do controlador para esse sistema foi feito seguindo os itens listados abaixo.

- Obtenção de um modelo matemático linear para um veículo que inclua dois graus de liberdade, um
relacionado ao movimento da massa não suspensa, e outro relacionado ao movimento da massa suspensa,
descrevendo-o a partir de equações diferenciais, função de transferência, equações de estado e
diagrama de blocos.

- Aplicação de valores nominais para todos os parâmetros do modelo, a partir de dados públicos
disponíveis para o veículo escolhido, para mostrar a resposta desse sistema para entrada do tipo
degrau unitário e analisar o regime transiente e o regime permanente, identificando aspectos dessa
resposta que podem ser melhorados e definindo os critérios de desempenho para o sistema.

- Projeto do controlador por meio do Controle por Lugar das Raízes, Controle por Resposta em
Frequência, Controle PID e Controle em Espaço de Estados.

- Análise da resposta do sistema controlado com cada uma das formas anteriores.

- Análise da robustez desse sistema de controle em relação a pelo menos 2 parâmetros do sistema
original, e também a um distúrbio do tipo degrau, estimando uma distribuição.
