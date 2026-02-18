# Análise da Biotransferência de Calor no Tecido Tumoral

Este trabalho tem como objetivo analisar a **biotransferência de calor no tecido tumoral** e avaliar a eficiência do processo de necrose induzido pelo aumento da temperatura. A implementação foi realizada na linguagem **C++**, apresentando um desempenho aceitável mesmo em execução serial para alguns valores de **\( h_t = 0.1 \)**. No entanto, para valores menores, como **\( h_t = 0.001 \)**, a execução serial tornou-se mais demorada, evidenciando a necessidade de **paralelização** para otimização do tempo de execução.

## Resultados

- A **geração de calor metabólico (Qm)** representa a **região de temperatura**, auxiliando na **identificação do tumor**.  
- A aplicação de **calor externo (Qr)** por **hipertermia** foi essencial para atingir a temperatura necessária à necrose das células tumorais.  
- A **discretização dos modelos** teve um impacto significativo nos resultados, influenciando diretamente a precisão das previsões.  
- A solução demonstrou uma **convergência relativamente rápida** da temperatura, com uma taxa de variação reduzida após **1500s**, indicando estabilidade térmica.  
- Comparando os **resultados obtidos neste trabalho** com os **resultados do trabalho anterior**, verificou-se que os **valores de necrose do tumor foram próximos**, validando a abordagem utilizada.  

Os valores detalhados podem ser observados na **tabela a seguir**.
