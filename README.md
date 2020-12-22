# skinet

#geral
Esta solução trata-se do backend de um e-commerce, qual será desenvolvido em .NET Core.

#arquitetura
A arquitetura ficou da seguinte maneira:

1 - Um projeto WebApi chamado API, onde estarão os Controllers e os endpoits implementados;
2 - Um projetpo lib chamado Core, onde estarão todas as entidades utilizadas pela API;
3 - Um projeto lib chamado Infrastructure, onde estarão tudo relacionado a Data, Migrations, Storage.

#db
A base do projeto usada será sqlite.
