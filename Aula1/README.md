# Aula 1 : Photogate
###### sim, aquele mesmo do lab de física...

## Lógica Binária:
  
  Conceitos de:
  * Operadores lógicos (and, or, ...)
  * Bit Masks

## GPIO:

  Generic Purpose Input and Output.
  
  Primeiramente, explicar rapidamente os conceitos:
  * Porta: Array de pinos (byte de pinos)
  * Pino: O pino onde conectamos os fios
  * Modo de opereção (Input or Output): O pino pode estar configurado como entrada ou saída (mudança na impedância)
  
  Com os conceitos explicados, pedir para acender o led do pino 13 (já existente na placa do Arduino)
  
```c
void setup()
{
  DDRB |= (1 << PB5); // Configura modo do pino como saida
  PORTB |= (1 << PB5); // "Liga" o pino. Ja configurado como saida, ele pode estar "ligado" ou "desligado"
}

void loop()
{
  
}
```

  Com a entrada funcionando, vamos agora trabalhar com uma entrada para interagir com esse led.
  Para usar um botão precisamos entender o que é um pullUp ou um pullDOwn:
  
  ![alt tag](./PDCircuit.gif)