# Spring Batch

## Conceito de Sistema de Processamento em Lote

- Tipo de sistema voltado para ambiente de grandes volumes de dados;
- Combinação de registros para deixar as informações mais completas dentro da aplicação;
- Registrar as operações realizadas na vida útil do sistema;
- Utilizam fontes de dados comuns para escrita e leitura de dados, como arquivos XML e CSV, arquivos de texto, dente muitos outros;
- Utilização de vários frameworks para combiná-los com o propósito de alcançar a alta produtividade da aplicação em um curto período de tempo;
- Spring Batch é uma solução voltada para a construção de sistemas de processamento em lotes;

## O que é o Spring Batch?

- Biblioteca voltada para o gerenciamento de transações, acompanhamento e registro das execuções realizadas dentro do sistema, reinicialização e cancelamento de tarefas, entre outras funções;
- Integração entre outras bibliotecas mais simples de serem realizadas;

## Componentes

- Job: Principal componente do Spring Batch. É o que será executado pelo sistema;
    - Separação de conceitos: definição dos processos a serem realizados pelo Job.
    - Existem dois componentes dentro de um Job, que são o Job (escopo do que será realizado) e o JobInstance (representação de um evento particular dentro do Job);