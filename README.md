# projeto_LDR_ArduinoProjeto: Controle de LED com Sensor LDR

Este projeto tem como objetivo criar um sistema de controle automático de LED utilizando um Arduino Uno e um sensor LDR. 
O sensor identifica a quantidade de luz no ambiente e o Arduino controla o LED de acordo com essa leitura. 
Quando estiver escuro, o LED acende, e quando estiver claro, o LED apaga 

## Materiais
## Materiais

| Quantidade | Material |
|------------|----------|
| 1 | Arduino Uno |
| 1 | Sensor LDR |
| 1 | LED |
| 1 | Resistor |
| 1 | Protoboard |
| 4 | Jumpers |
### Sensore → OUTPUT

```cpp
int sensor = A0;
int led = 9;

void setup() {
  pinMode(led, OUTPUT);
}
