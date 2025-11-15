## Introdução
&emsp; O presente projeto trata-se do desenvolvimento de um semáforo inteligente, que se utiliza principalmente de dois microcontroladores ESP32, um sensor LDR e um sensor ultrassônico. Os conhecimentos aqui aplicados fazem referencia aos assuntos conceituados durantes as aulas de programação do módulo 4 das semana 1 à semana 5. 

## Parte 1: Montagem Física do Semáforo com LDR e Modo Noturno

&emsp; Para a realização da montagem física deste semáforo, nós utilizamos os seguintes componentes: 

</n>

|Quantidade | Componente | Finalidade|
|------------|---------------|----------|
| 2 |Microcontroladores ESP32| Conectividade Wi-Fi, responsável pela conexão do circuito |
| 1 | Sensor ultrassônico | Detectar quando um carro está próximo e ajustar o semáforo para facilitar o trânsito |
| 1 | Sensor LDR | Detectar se está dia ou noite e mudar o comportamento do semáforo com base nesses dados |
| 7 | Peças MDF | Para conectar os componetes do circuito, simulando a simulação do semáforo |
| 13 | Jumper (Macho-fêmea e Fêmea-fêmea) | Conectar os componentes do cuircuito |
| 7 | Resistor (10kOhms, 310Ohms e 330hms) | Transformar energia térmica e evitar a sobrecarga elétrica dos componentes |
| 2 | Cabo USB | Para alimentar os microcontroladores |
| 2| Protoboard | Para comportar os jumpers e resistores |

</n>

&emsp; O funcionamento do sensor LDR se faz por meio da alternância de resistência do circuito por meio da quantidade de luz emitida sobre ele. Dentro do projeto semáforo inteligente, o ele detecta essa quantidade de incidência de luz e ajusta o semáforo para comportar um fluxo de transito maior. 

&emsp; Mais detalhes sobre o funcionamento do semáforo inteligente podem ser encontradas por meio do seguinte código:

``` .cpp

CÓDIGO DO SEMÁFORO

```


## Parte 2: Configuração da Interface Online

&emsp; Para a configuração da interface online nós utilizamos o software online Ubidots. Logo abaixo, podem ser encontrados mais detalhes da interface. 

(ADICIONAR IMAGENS DA INTERFACE)

</n> 

&emsp; Para melhor visualização dos dados obtidos, podem ser encontradas mais imagens abaixo, bem como o vídeo demonstrativo: 

</n>

Link do vídeo: (ADICIONAR LINK DO VÍDEO)

(ADICIONAR IMAGENS DOS GRÁFICOS DO SENSOR)

