# Objetivos

-Estudar retificadores de meia onda, onda completa em ponte e onda completa com
derivação central, medindo as principais grandezas nos circuitos montados;

-Verificar o funcionamento dos retificadores;

-Implementar filtros capacitivos nos retificadores e verificar seu funcionamento com a
presença destes elementos.

# Parte 01_a Circuito Retificador de Meia Onda

## Simulando o circuito sem capacitor:

![circuito sem capacitor](https://i.imgur.com/tCWH4qA.jpg)

### Onda gerada para a tensão (Vf) no enrolamento primário

![Circuito sem capacitor](https://i.imgur.com/k130ItG.jpg)

### Onda gerada para as tensões (Vin) e (Vo) no enrolamento secundário

![Circuito sem capacitor](https://i.imgur.com/LSTQOWg.jpg)
Analisando as duas ondas, pode ser notado que Vo tem uma amplitude menor que Vin por causa da queda de tensão sobre o diodo, e nos ciclos negativos de Vin o valor do sinal em Vo se torna 0 devido a polarização inversa do diodo.

### Tensão média e eficaz para os pontos (Vin) e (Vo)

![Circuito sem capacitor](https://i.imgur.com/LGmw0Gx.jpg)

![Circuito sem capacitor](https://i.imgur.com/xeNq0SA.jpg)

### Preenchendo Tabela com os valores medidos sem capacitor

![Circuito sem capacitor](https://i.imgur.com/2XCefNQ.jpg)


### Onda gerada sobre o diodo

![Circuito sem capacitor](https://i.imgur.com/8l6U26L.jpg)

O valor maximo da corrente foi de **41,64mA**, com um valor médio de **12,81mA** e valor eficaz de **20,84mA**.



## Simulando o circuito com um capacitor de 330uF:

![circuito capacitor 330](https://i.imgur.com/EolIVNx.jpg)
 
### Onda gerada para as tensões (Vin) e (Vo) no enrolamento secundário

![circuito capacitor 330](https://i.imgur.com/DIGYflf.jpg)

### Tensão média e eficaz para Vo

![circuito capacitor 330](https://i.imgur.com/IcDpRdl.jpg)

Adicionando o capacitor no circuito fez com que a taxa de variação de Vo seja diminuída, no ciclo positivo de Vin o capacitor é carregado, e descarrega no ciclo negativo. A tensão de ripple é a diferença entre a tensão máxima de Vo e a sua tensão quando o capacitor está carregando.

### Preenchendo Tabela com os valores medidos capacitor de 330uF

![circuito capacitor 330](https://i.imgur.com/A1Kd0Dl.jpg)

### Onda gerada sobre o diodo

![circuito capacitor 330](https://i.imgur.com/Eku99v3.jpg)

O valor maximo da corrente foi de **1,48A**, com um valor médio de **102,5mA** e valor eficaz de **317,69mA**.

## Simulando o circuito com um capacitor de 2200uF:

![circuito capacitor 2200](https://i.imgur.com/cfcw5OL.jpg)

### Onda gerada para as tensões (Vin) e (Vo) no enrolamento secundário

![circuito capacitor 2200](https://i.imgur.com/hrg0ZYf.jpg)

### Tensão média e eficaz para Vo

![circuito capacitor 2200](https://i.imgur.com/bcgES7i.jpg)

Com o valor da capacitância do capacitor aumentada consequentemente o valor da tensão de ripple diminuiu.

### Preenchendo Tabela com os valores medidos capacitor de 2200uF

![circuito capacitor 2200](https://i.imgur.com/5wv4ezy.jpg)

### Onda gerada sobre o diodo

![circuito capacitor 2200](https://i.imgur.com/jmP5QY1.jpg)

O valor maximo da corrente foi de **9,89A**, com um valor médio de **522,51mA** e valor eficaz de **1,94A**.







# Parte 01_b

O Resistor shunt é um resistor com um valor de resistência muito baixo, devido sua baixa resistência e a possibilidade de determinar o seu valor, o resistor shunt pode ser usado para determinar a corrente que circular por ele.

Para determinar o valor do resistor ele deve ser colocado em série com a carga, e os valores podem ser determinado pela queda de tensão, usando a formula de lei de Ohmn onde V=RxI ou R=V/I.

