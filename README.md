# CPU RISC-V de 32 Bits: Design e Implementação com Pipeline de 5 Estágios

O trabalho "CPU RISC-V de 32 Bits: Design e Implementação com Pipeline de 5 Estágios" aborda o desenvolvimento de uma CPU baseada na arquitetura RISC-V RV32I, conhecida por sua simplicidade e escalabilidade. A CPU implementa um pipeline de 5 estágios: Busca, Decodificação, Execução, Memória e Escrita de Resultados, com o objetivo de aumentar a eficiência do processamento.

Cada estágio é detalhado em termos de componentes e funcionalidades, desde a busca de instruções na memória ROM até a escrita de resultados nos registradores. Técnicas de controle de riscos de dados, como o forwarding e a detecção de hazards, são implementadas para garantir o correto funcionamento do pipeline.

O projeto é desenvolvido em VHDL, com a criação de diversos componentes como ALU, unidades de controle e registradores de pipeline. Além disso, são apresentados os códigos e os diagramas correspondentes aos componentes da CPU. Para operações SIMD, modificações específicas são realizadas, adicionando novos vetores de controle.
