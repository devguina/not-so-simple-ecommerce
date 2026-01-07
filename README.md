# Not So Simple Ecommerce
Aplicação composta por um Frontend React e Backend .NET composto por 6 microserviços e um Banco relacional Postgresql
Essa aplicação foi fornecida pelo Kenerry em seu curso DevOps na Nuvem, abordando as melhores práticas. Acompanhe comigo a minha evolução e quem sabe a sua? Farei várias anotações em arquivos MD explicando conceitos e etc. Futuro leitor, lhe desejo uma boa leitura, hehe!

## Stack de todo o projeto
Primeiramente, execute o build da stack de infraestrutura, pois ela é a base para tudo.

### Stack de Infra
- LocalStack:  Usado para replicar vários serviços da AWS.
- Terraform: Infrastructure as Code (IaC) usado para criar a infraestrutura local na AWS, que neste projeto será no LocalStack.
- Nginx: Poderoso Servidor HTTP/Loadbalance/Proxy Reverso: Usado neste projeto como Proxy reverso e eventualmente um gateway, onde os microserviços estaram por trás.
