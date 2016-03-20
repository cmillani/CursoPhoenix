# Curso de Sistemas Embarcados e Micro Controladores
--------

Tópicos:
--------
* GPIO -                 kkk
* PullUp e PullDown -    kkk
* UART -                 kkkk
* PWM -                  kkkk
* ADC -                  kkkk
* Timer -                kkk
* Interrupções -         kk              
* Fuses  -               kk
* Sleep Mode -           kk
* Periféricos -          k
* Registradores -        k
* Memórias (RAM/Flash) - k
* Memory Mapped IO -     k
* Datasheet -            k
* Micro Programming -    kk
* PPM -                  kkkk

Competências:
-------------
----
* Ler e Buscar informações em Datasheets, para utilizar os recursos de um micro
* Intrepretar um Sinal PPM
* Gerar um sinal PWM
* Manipular uma GPIO para fins diversos
* Estabelescer uma comunicação serial
* Gravar microcontroladores AVR
* Compreender o funcionamento de um microcontrolador
* Projetar sistemas embarcados simples
* Melhorar eficiência energética de um sistema


Atividades:
-----------
-----------
* Criação de um programador AVRASP <- Adiar, causaria um overhead desnecessário para aprender AVR. O Arduino da conta :)
 - Soldar o circuito do AVRASP e gravar o programador no micro, para uso nas próximas aulas
 - Breve explicação de Interrupções, Memórias, Registradores e periféricos + Conclui com datasheet
* Criação de um Photogate
 - Aprender a Programar o micro
 - Uso de Interrupções , Sleep Mode e Fuses p/ timer
* Configuração de um pino como GPIO e leitura de Sensores com PullUp e PullDown, e uso do Timer
 - Explicação de Data Direction, Pin Mode, PullUp e PullDown e pq precisa, Timer
 - Possíveis materiais: push button e sensor IR
 - Aplicação: Controle Remoto Com Botões e Timer
* Comunicação Serial Bluetooth
 - Explicação UART, interrupções e PWM para controle de um Ventilador + ADC
 - Usar um módulo bluetooth para controlar o pwm de um cooler através de um outro micro com um potenciômetro
 - Substituição do BT por um receptor PPM para fins didáticos
