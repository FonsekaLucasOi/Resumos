#   Testes e Automatização

- Os testes são uma garantia da qualidade na entrega do software, diminuindo a possibilidade de bugs no sistema;
- Alguns tipos de testes são essenciais para garantir toda a integridade do software, como por exemplo os testes de sistema, testes unitários e os testes integrados;

##  Testes de sistema

- São testes que abordam todo o ambiente de um sistema desenvolvido;
- Também é chamado por *end-to-end*, sendo descrito dessa forma por abordar desde a interface do usuário até o backend da aplicação;
- Ferramentas como o *Selenium* são utilizadas para realizar esse tipo de teste;
- Possui a desvantagem de serem testes lentos de serem executados;
- Manutenção desses testes bastante custosa baseada no prazo de entrega do desenvolvimento;

### Testes de serviços Web

- Para testar serviços *Web*, utiliza-se *API's* como *RestFul*, para que se economize tempo de desenvolvimento visando a produtividade;
- Percorrem toda a aplicação, trabalhando com *SOAP*, *REST* ou *POX*;

###  Testes de aceitação

- Testes para descrever o comportamento do sistema, sem precisar abordar toda a aplicação;
- Ferramentas como o *Cucumber* e o *JBehave* são conhecidas para a criação desse tipo de teste;

### Testes de limite do sistema

- Testes que envolvem performance, escalabilidade (teste de carga) visando o cenário de requisitos não-funcionais;
- Outros testes que envolvem execução humana são chamads de testes de exploração, visando casos particulares na aplicação;

## Teste de Unidade, TDD e design de código

- Testes unitários servem para garantir a execução de cada trecho específico com outras partes do sistema ou estado do objeto;
- Trabalha diretamente com o conceito de alta coesão e baixo acoplamento;
- Caso seja necessário utilizar alguma dependência dentro da classe, é criado um *fake object* para poder simular o comportamento do bloco específico, chamado de *Mock*;
- TDD (*Test Driven Development*): Conceito voltado para diminuir a chance de deixar o código incoeso e com alto acoplamento:
    - Primeiro se cria os cenários de testes para depois desenvolver a funcionalidade desejada;
    - Auxilia na alta cobertura de testes dentro de um código específico;