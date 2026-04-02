# RoboTrilha - Projeto IC

PT-BR | [English](#EN)

## PT-BR

### Visao geral
Este repositorio contem varias versoes de codigo para um carrinho robotico baseado em Arduino (Car8), com foco em:
- seguimento de linha usando sensor infravermelho;
- controle de motores por PWM;
- leitura de distancia com sensor ultrassonico;
- testes de logica para desvio de obstaculos.

Os arquivos representam iteracoes do projeto (testes, tentativas e versoes consideradas corretas/oficiais).

> **Versao final funcional:** `codigo da vitoria`.

### Tecnologias e plataforma
- Arduino (linguagem C/C++ para microcontrolador)
- Arduino IDE
- Funcoes tipicas usadas: `digitalWrite`, `analogWrite`, `pulseIn`, `attachInterrupt`

### Estrutura do repositorio
- `codigooficial`: versao principal com logica de movimento e desvio de obstaculo.
- `codigo da vitoria`: **versao final**, com ajuste de velocidade e leitura de distancia.
- `codigo CORRETO`: versao alternativa considerada estavel em alguns cenarios.
- `codigo teste`: variacao para experimentos.
- `Possivel solucao pra ele passar do obstaculo`: tentativa focada em contornar obstaculos.
- `talvez seja uma possibilidade`: prototipo curto para validacoes.
- `Teste_alteracao1`: arquivo de experimentacao adicional.

### Sensores e atuadores (resumo)
- Sensor infravermelho (`infra`) para detectar linha.
- Sensor ultrassonico (`ultraout`/`ultrain`) para medir distancia.
- Dois motores DC com pinos de direcao e velocidade (PWM).

### Como usar
1. Abra o Arduino IDE.
2. Crie ou abra um sketch.
3. Copie o conteudo do arquivo desejado deste repositorio para o sketch.
4. Ajuste pinos e constantes conforme seu hardware real.
5. Selecione a placa/porta correta.
6. Compile e envie para o Arduino.
7. Monitore o comportamento e ajuste delays/velocidades se necessario.

### Observacoes
- Alguns nomes de arquivo estao sem extensao. Se quiser, voce pode renomear para `.ino` para facilitar no Arduino IDE.
- Como ha varias versoes, compare os arquivos antes de definir uma base final.

---

## EN

### Overview
This repository contains multiple code versions for an Arduino-based robotic car (Car8), focused on:
- line following using an infrared sensor;
- motor control with PWM;
- distance measurement with an ultrasonic sensor;
- obstacle-avoidance logic experiments.

The files represent project iterations (tests, attempts, and versions considered correct/official).

> **Final working version:** `codigo da vitoria`.

### Tech stack and platform
- Arduino (C/C++ for microcontrollers)
- Arduino IDE
- Common functions used: `digitalWrite`, `analogWrite`, `pulseIn`, `attachInterrupt`

### Repository structure
- `codigooficial`: main version with movement and obstacle-avoidance logic.
- `codigo da vitoria`: **final version**, with speed tuning and distance reading.
- `codigo CORRETO`: alternative version considered stable in some scenarios.
- `codigo teste`: experimental variation.
- `Possivel solucao pra ele passar do obstaculo`: attempt focused on passing obstacles.
- `talvez seja uma possibilidade`: short prototype for quick validation.
- `Teste_alteracao1`: additional experimentation file.

### Sensors and actuators (summary)
- Infrared sensor (`infra`) for line detection.
- Ultrasonic sensor (`ultraout`/`ultrain`) for distance measurement.
- Two DC motors with direction and PWM speed pins.

### How to use
1. Open Arduino IDE.
2. Create or open a sketch.
3. Copy the contents of your chosen file from this repository into the sketch.
4. Adjust pin mapping and constants to match your hardware.
5. Select the correct board and serial port.
6. Compile and upload to Arduino.
7. Monitor behavior and tune delays/speeds as needed.

### Notes
- Some filenames have no extension. You may rename them to `.ino` for easier Arduino IDE usage.
- Since there are multiple versions, compare files before choosing your final baseline.
