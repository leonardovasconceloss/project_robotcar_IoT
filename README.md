# Projeto de IoT: Carrinho Robô para Competição(V1 Beta)

## Objetivo do Projeto

O objetivo deste projeto é aplicar os conhecimentos adquiridos na matéria de lógica com IoT para desenvolver um carrinho robô. Este carrinho foi  utilizado em uma competição onde o objetivo é movimentar o carrinho para estourar a bexiga do adversário.

## Componentes Utilizados

### Hardware

- **ESP32:** Microcontrolador principal responsável pelo controle do carrinho.
- **Chassi 2WD:** Com duas rodas motorizadas e uma roda boba na frente.
- **Motores DC:** Dois motores integrados no chassi para movimentação.
- **Ponte H L298N:** Utilizada para controlar os motores DC.
- **Pilhas AA (x4):** Fonte de alimentação do carrinho.
- **Protoboard de 170 Pinos:** Para montagem dos circuitos.
- **Resistor:** Utilizado no circuito de feedback.
- **LED:** Para feedback de conexão.
- **Jumpers:** Cabos de conexão para interligar os componentes.

### Software

- **Blynk IoT:** Aplicativo utilizado para controlar o microcontrolador ESP32 via Wi-Fi.

## Descrição do Sistema

O sistema consiste em um carrinho robô controlado remotamente através de um dispositivo móvel utilizando o aplicativo Blynk IoT. O ESP32 recebe comandos via Wi-Fi, que são traduzidos em movimentos dos motores DC, permitindo ao carrinho se movimentar de forma estratégica para estourar a bexiga do adversário.

### Conexões

1. **ESP32:**
   - Alimentação: 3.3V e GND.
   - Pinos de controle: Pinos digitais para controle da Ponte H.

2. **Ponte H L298N:**
   - Conexão com os motores DC.
   - Alimentação dos motores com as pilhas AA.

3. **Motores DC:**
   - Conectados à Ponte H para controle de rotação e direção.

4. **LED de Feedback:**
   - Conectado ao ESP32 para indicar a conexão Wi-Fi.

### Fluxo de desenvolvimento 
![image](https://github.com/leonardovasconceloss/project_robotcar_IoT/assets/118570524/0e4a6ba6-10a1-49a0-a916-cafa26f7bd9b)

## Funcionamento do Projeto

1. **Configuração Inicial:**
   - Montagem dos componentes no chassi e conexão dos circuitos conforme o diagrama.
   - Programação do ESP32 para receber comandos via Blynk.

2. **Controle Remoto:**
   - Utilização do aplicativo Blynk para enviar comandos de movimento ao ESP32.
   - Controle da velocidade e direção dos motores para movimentar o carrinho.

3. **Competição:**
   - Estratégia de movimentação para estourar a bexiga do adversário.
   - Feedback em tempo real através do LED indicando a conexão e recepção dos comandos.

## Desafios e Soluções

### Desafios Encontrados

- **Estabilidade da Conexão Wi-Fi:** Garantir uma conexão estável durante a competição.
- **Sincronização dos Motores:** Manter os motores sincronizados para movimentos precisos.
- **Alimentação de energia dos motores:** Conseguir alimentar em potência máxima os dois motores para melhor eficiência e potência. 

### Soluções Implementadas

- **Ajustes no Código:** Implementação de códigos de reconexão e calibração dos motores.
- **Testes Extensivos:** Realização de testes para assegurar o desempenho adequado durante a competição.

## Resultados Obtidos

- **Taxa de Sucesso:** Moderado índice de sucesso na execução das tarefas planejadas.
- **Feedback Positivo:** Através do LED de conexão e controle eficiente via Blynk.

## Conclusão

Este projeto demonstrou a aplicabilidade de conceitos de IoT e lógica em um ambiente competitivo e prático. O carrinho robô desenvolvido mostrou-se fiel em atingir os objetivos propostos, destacando a importância de uma integração bem-feita entre hardware e software.

## Futuras Melhorias

- **Melhorar a Autonomia:** Otimização do consumo de energia.
- **Aprimorar o Controle:** Implementação de sensores adicionais para navegação autônoma.
- **Novos métodos de conexão:** Adicionar novas formas de conexão, focando na baixa latência e consistência do sinal.
- **Software:** Otimizar o código e adicionar novas funcionalidades para feedback. 

## Agradecimentos

Agradecemos a todos os colegas e professores que contribuíram para a realização deste projeto. 

**Professor orientador:** Leonardo Bontemp

**Equipe participante:**

Gustavo Gazi
Leonardo V Santana
Eder Malaquias
Amauri
Vander Silva
Arthur


## Book de imagens dos momentos de desenvolvimento. 
![Imagem do WhatsApp de 2024-05-04 à(s) 13 24 30_4736b140](https://github.com/leonardovasconceloss/project_robotcar_IoT/assets/118570524/8227d296-240e-4b4c-8067-75af14c05300)
![Imagem do WhatsApp de 2024-05-04 à(s) 14 40 59_02682241](https://github.com/leonardovasconceloss/project_robotcar_IoT/assets/118570524/1ccadff1-9778-4360-a6ab-7dbe2510573e)
![Imagem do WhatsApp de 2024-05-04 à(s) 13 25 03_2945e48f](https://github.com/leonardovasconceloss/project_robotcar_IoT/assets/118570524/f0bd65cc-23fe-43ab-b60b-1299d94ac9f3)
![Imagem do WhatsApp de 2024-05-10 à(s) 11 02 51_4cffb638](https://github.com/leonardovasconceloss/project_robotcar_IoT/assets/118570524/94eca611-3c09-42e8-97c8-a42e2fd63a66)
![Imagem do WhatsApp de 2024-05-10 à(s) 11 03 56_e4165d49](https://github.com/leonardovasconceloss/project_robotcar_IoT/assets/118570524/67da57ca-0232-4093-ae99-baaf734edaed)
![Imagem do WhatsApp de 2024-05-17 à(s) 10 15 33_1e3c6a97](https://github.com/leonardovasconceloss/project_robotcar_IoT/assets/118570524/f9cf1350-6252-4472-944d-2c85c89c6327)
![Imagem do WhatsApp de 2024-05-24 à(s) 10 56 23_60164537](https://github.com/leonardovasconceloss/project_robotcar_IoT/assets/118570524/e0b0b5b4-6107-47e0-8a2e-a099b487b788)




---

