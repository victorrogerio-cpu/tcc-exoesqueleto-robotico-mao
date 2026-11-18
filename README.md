# Luva robótica para fisioterapia da mão

Repositório técnico do Trabalho de Conclusão de Curso em Engenharia de Controle e Automação da UFRPE.

## Escopo

O projeto desenvolve um protótipo mecatrônico para assistência controlada à flexão dos quatro dedos longos e ao movimento de pinça do polegar durante exercícios de fisioterapia. O trabalho compreende projeto, fabricação e verificação técnica em bancada. Não apresenta o protótipo como dispositivo médico validado nem como comprovação de eficácia clínica.

## Arquitetura mecânica em revisão

A revisão mecânica atual utiliza:

- chassi monobloco de antebraço, destinado à mão esquerda adulta de referência;
- servomotor DS3225 para os quatro dedos longos e MG996R para o polegar, instalados em berços laterais com fixação pelas abas originais;
- carretéis independentes acoplados por flange metálica 25T e polias-guia com rolamentos 608ZZ;
- transmissão por linha multifilamento de 0,50 mm conduzida em tubo PU 4 × 0,75 mm;
- retorno por molas de tração;
- tampa removível de proteção;
- baia eletrônica integrada ao chassi para ESP32-S3, com acesso de programação, retenção da placa e rotas separadas para potência e sinais.

Os modelos CAD e os arquivos de impressão somente são liberados após verificação de interfaces, folgas, fixações e rotas dos tendões. A aprovação geométrica digital não substitui o ensaio de bancada.

## Estado do desenvolvimento

- revisão teórica, requisitos e metodologia: em consolidação;
- arquitetura mecânica lateral e transmissão por cabos: revisão R14;
- baia do ESP32, retenção mecânica e rota de cabos: modeladas; aguardam ensaio físico de montagem;
- ensaios físicos, calibração dos sensores e firmware: pendentes.

## Estrutura do repositório

- `mechanical/`: modelos CAD, listas de materiais e instruções de montagem;
- `hardware/`: arquitetura eletrônica, alimentação, proteção e sensoriamento;
- `firmware/`: código embarcado e procedimentos de calibração;
- `docs/`: decisões de projeto, rastreabilidade e protocolos de ensaio.

## Autor

Victor Rogério Leite
