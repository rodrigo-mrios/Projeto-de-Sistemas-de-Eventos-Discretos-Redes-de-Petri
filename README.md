# Projeto de Sistemas de Eventos Discretos Redes de Petri
## Descrição Geral
O projeto propõe a modelagem de um cenário usando Redes de Petri. O cenário em questão trata-se de um aeroporto constituído por três gates, dois segmento de taxiamento e uma pista, desde as etapas de solo até as de vôo no aeroporto, considerando as etapas de saída e chegada nos gates, taxiamento e decolagem e pouso nas pistas.
## Objetivos
O objetivo do projeto é desenvolver um modelo que represente um sistema de controle de tráfego aeroportuário de um aeroporto utilizando Redes de Petris com o software CPN Tools, procurando:
- Desenvolver um modelo com todas as etapas do sistema;
- Buscar cumprir todas as regras operacionais, evitando estados indesejados e/ou proibidos;
- Simular e verificar a funcionalidade do sistema.
## Funcionamento do sistema
### Principais componentes
- 3 gates;
- 2 pistas de taxiamento;
- 1 pistas de decolagem e pouso.
### Regras dos operacionais
- Rota dos aviões
  - Fluxo de saída: Saída de um dos gates →  Pista de taxiamento de saída → Pista de decolagem;
  - Fluxo de chegada: Pouso na pista → Pista de taxiamento de entrada → chegada ao gate;

- Prioridade de acesso
  - Apenas um avião pode entrar ou sair dos gates por vez;
  - Aviões não podem pousar/decolar caso a pista esteja ocupada ou todos os gates estejam ocupados.
##
## Modelo do Aeroporto
O modelo implementado difere da imagem apenas no número de gates no estacionamento.
<p align="center"><img src=https://help.eadaviacaocivil.com/wp-content/uploads/2024/01/Screenshot_114.png>
  
<p align="center">Fonte: https://help.eadaviacaocivil.com/aeronaves-e-aerodromos/
