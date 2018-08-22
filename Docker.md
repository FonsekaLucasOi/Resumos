# Docker

## O que é o Docker?

- Ferramenta que cria *containers* de aplicações e serviços de forma isolada do Sistema Operacional;
- Baseado em **LXC** (*Linux Containers*);
- Reduz drasticamente custos e facilita a integração de diferentes ambientes a serem criados;
- Possui os seguintes recursos:
    - ***Cgroups***: Recurso que gerencia a utilização de hardware dos containers (como CPU, memória, disco, rede), os isolando e limitando o seu uso;
        - Agrupa os recursos necessários para a utilização de alguma requisição de forma que seja possível definir limites e restrições desse uso visando manter o desempenho do ambiente;
    - ***Namespaces***: isolam grupos de processos, de forma que os mesmos não enxerguem processos de outros grupos, criando assim uma camada de isolamento;
        - *pid* (isolamento de processos), *net* (controle de interface de rede), *icp* (controle de recursos do ICP), *mnt* (gestão dos pontos de montagem) e *uts* (isolamento de recursos do kernel) são as nomenclaturas dessas camadas;
    - *UnionFS*: Sistemas de arquivos por meio da criação de camada, sendo esses arquivos leves e rápidos de se utilizar.
