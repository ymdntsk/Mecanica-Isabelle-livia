Mecanica-Isabelle-livia

## Descritivo do que a aplicação precisa fazer

* Cadastrar clientes.
* Cadastrar veículos.
* Associar veículos aos clientes.
* Cadastrar agendamentos.
* Mostrar os agendamentos por dia.
* Permitir buscar clientes.
* Permitir editar e excluir informações.

## Front

Telas

* Tela de Clientes
* Tela de Veículos
* Tela de Agendamentos
* Tela Principal

## Comportamentos

* Cadastrar
* Buscar
* Editar
* Excluir
* Visualizar

## Backend e Banco

Entidades e relacionamentos

* Cliente → pode ter vários veículos.
* Veículo → pertence a um cliente.
* Mecânico → realiza os serviços.
* Serviço → é realizado por um mecânico.
* Agendamento → relaciona o cliente, o veículo, o serviço e o mecânico.

Controllers

* Cliente
* Veículo
* Agendamento
* Serviço
* Mecânico

Rotas

Clientes

* GET /clientes
* POST /clientes
* PUT /clientes/:id
* DELETE /clientes/:id

Veículos

* GET /veiculos
* POST /veiculos
* PUT /veiculos/:id
* DELETE /veiculos/:id

Serviços

* GET /servicos
* POST /servicos
* PUT /servicos/:id
* DELETE /servicos/:id

Mecânicos

* GET /mecanicos
* POST /mecanicos
* PUT /mecanicos/:id
* DELETE /mecanicos/:id

Agendamentos

* GET /agendamentos
* POST /agendamentos
* PUT /agendamentos/:id
* DELETE /agendamentos/:id
