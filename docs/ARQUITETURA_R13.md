# Arquitetura mecânica R13

## Finalidade

A revisão R13 organiza a unidade de acionamento no antebraço para reduzir o volume sobre a mão e concentrar os elementos de maior massa. A arquitetura é destinada a uma luva para mão esquerda e mantém acionamentos independentes para os quatro dedos longos e para o polegar.

## Cadeia de transmissão

Cada rota de tração segue a sequência:

1. eixo estriado 25T do servomotor;
2. flange metálica circular 25T;
3. carretel impresso;
4. polia-guia sobre dois rolamentos 608ZZ;
5. tubo PU 4 × 0,75 mm;
6. módulo do dedo.

O carretel não utiliza estriado impresso como elemento transmissor de torque. A flange metálica é fixada ao eixo pelo parafuso central do servomotor; o carretel é aparafusado à flange.

## Fixação e rigidez

Os servomotores são recebidos por berços laterais integrados ao chassi. A retenção é realizada pelas abas originais dos servos, com parafusos inseridos de cima para baixo e porcas travadas no chassi. O chassi monobloco concentra berços, pedestais das polias, guias de saída e a futura baia eletrônica, reduzindo interfaces estruturais removíveis.

## Integração eletrônica

A baia do ESP32-S3 deve permanecer separada de carretéis, polias e cursos dos atuadores. O modelo deve prever:

- envelope mínimo de 60 mm × 27 mm × 12 mm para a placa e conectores;
- apoio plano, guias laterais e retenção removível;
- acesso ao USB-C sem remoção dos atuadores;
- alívio de tração para os cabos;
- rota de potência distinta da rota de sinais;
- ventilação protegida e sem comunicação com as rotas dos tendões.

## Limites da revisão

A validação geométrica verifica interferências entre sólidos e acessibilidade de montagem. A liberação para uso depende de ensaios de bancada com curso reduzido, sem a mão, para verificar giro livre, enrolamento dos cabos, retorno por molas, aquecimento, retenção da eletrônica e atuação das proteções.
