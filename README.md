# CPU RISC-V de 32 Bits: Design e Implementação com Pipeline de 5 Estágios

![Diagrama dos blocos da CPU com pipeline de 5 estágio. Controle da ALU e o MUX ALUScr
foi omitido para fins de simplificação.](Diagrama.png)

O trabalho "CPU RISC-V de 32 Bits: Design e Implementação com Pipeline de 5 Estágios" aborda o desenvolvimento de uma CPU baseada na arquitetura RISC-V RV32I, conhecida por sua simplicidade e escalabilidade. A CPU implementa um pipeline de 5 estágios: Busca, Decodificação, Execução, Memória e Escrita de Resultados, com o objetivo de aumentar a eficiência do processamento.

Cada estágio é detalhado em termos de componentes e funcionalidades, desde a busca de instruções na memória ROM até a escrita de resultados nos registradores. Técnicas de controle de riscos de dados, como o forwarding e a detecção de hazards, são implementadas para garantir o correto funcionamento do pipeline.

Para desenvolver o trabalho foi utilizado o simulador LogiSIM-Evolution e implementado com blocos feitos em Linguagem de Descrição de Hardware VHSIC (VHDL), no qual VHSIC significa Circuito Integrado de Altíssima Velocidade. Esta linguagem permite modelar sistemas eletrônicos digitais através da definição, simulações e testagens das estruturas e comportamentos de circuitos digitais.
