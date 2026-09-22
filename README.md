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

Controllers

* Cliente
* Veículo
* Agendamento

Entidades e relacionamentos

* Cliente → Veículo: um cliente pode ter vários veículos.
* Cliente → Agendamento: um cliente pode ter vários agendamentos.
* Veículo → Agendamento: um veículo pode ter vários agendamentos.

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

Agendamentos

* GET /agendamentos
* POST /agendamentos
* PUT /agendamentos/:id
* DELETE /agendamentos/:id
