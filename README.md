# Luva robótica para fisioterapia

Repositório do Trabalho de Conclusão de Curso em Engenharia de Controle e Automação da UFRPE.

O projeto desenvolve um exoesqueleto de mão de baixo custo para apoio a exercícios de fisioterapia. A revisão mecânica atual é a **R6B**, destinada à mão direita adulta tamanho L e organizada para fabricação por impressão 3D.

## Estado atual

- arquitetura mecânica definida para flexão ativa e abertura passiva;
- servo principal DS3225-270, de 25 kgf·cm, posicionado na região volar do antebraço;
- quatro tendões independentes para indicador, médio, anelar e mínimo;
- polegar previsto com servo auxiliar para oposição e movimento de pinça;
- retorno dos dedos por molas de extensão;
- cinco sensores FSR402 previstos para leitura de contato/força;
- modelos de fabricação disponíveis em STL, STEP e 3MF na entrega técnica R6B;
- ensaio físico, calibração dos sensores e desenvolvimento do firmware ainda pendentes.

## Estrutura

- `mechanical/`: decisões mecânicas, conjuntos CAD e fabricação;
- `hardware/`: arquitetura eletrônica, alimentação e sensoriamento;
- `firmware/`: código de controle a ser desenvolvido após a montagem de bancada;
- `docs/`: documentação técnica e registros das revisões.

## Autor

Victor Rogério Leite
