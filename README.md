# Sistema de Irrigação Automática via MQTT

## Descrição
Este projeto apresenta um **Sistema de Irrigação Automática** controlado por um NodeMCU ESP8266, utilizando o protocolo MQTT para monitoramento do solo e controle da irrigação. Projetado para ser uma solução eficiente em gestão de recursos hídricos, o sistema automaticamente ajusta a irrigação com base na umidade do solo, promovendo um cuidado ideal para as plantas e reduzindo o desperdício de água.

## Funcionalidades
- **Monitoramento de Umidade**: Utiliza um sensor de umidade do solo para coletar dados em tempo real.
- **Controle Automático de Irrigação**: Ativa ou desativa o sistema de irrigação com base nos níveis de umidade detectados.
- **Comunicação MQTT**: Envio e recebimento de comandos e dados via MQTT, permitindo a integração com outros sistemas e controle remoto.

## Componentes
- NodeMCU ESP8266
- Sensor de Umidade do Solo
- Atuador (Bomba de Irrigação)
- LEDs para indicação de status
- Conexão Wi-Fi

## Configuração
Para reproduzir este sistema, siga os passos abaixo:

1. **Hardware**: Conecte o sensor de umidade, a bomba de irrigação e os LEDs aos pinos correspondentes no NodeMCU ESP8266.
2. **Software**: Carregue o script fornecido no NodeMCU. Certifique-se de modificar as configurações de Wi-Fi e MQTT para se adequar à sua rede e broker MQTT.
3. **Teste**: Após configurar o hardware e o software, teste o sistema para garantir que os componentes estejam funcionando corretamente.

## Uso
Após a configuração, o sistema operará automaticamente, ativando a bomba de irrigação quando o solo estiver seco e desligando-a quando a umidade adequada for alcançada. Os LEDs fornecem uma indicação visual do status atual do solo e da ação da bomba.


---
Criado por Renan de Andrade Joaquim para a disciplina de Objetos Inteligentes e Conectados da Universidade Presbiteriana Mackenzie.
