
**Fan-in**: Dependências que chegam. Essa métrica identifica o número de classes fora desse componente que dependem das classes contidas dele.
**Fan-out**: Dependências que saem. Essa métrica identifica o número de classes contidas nesse componente que dependem de classes fora dele.
**I (Instabilidade)**: I = Fan-out / (Fan-in + Fan-out)

A métrica *I* de um componente deve ser maior do que a métrica I dos componente dos quais ele depende. Ou seja, as métricas *I* devem diminuir na direção da dependência.
