# Controle de Medicamentos

## Projeto

O Controle de Medicamentos é um sistema web desenvolvido para auxiliar no gerenciamento de medicamentos e dos recursos de uma unidade de saúde. O sistema centraliza informações sobre fornecedores, medicamentos, pacientes e funcionários, além de permitir o controle das movimentações de estoque.

A aplicação possui módulos para gerenciamento de fornecedores, medicamentos, pacientes e funcionários, permitindo cadastrar, visualizar, editar e excluir registros. Também conta com um módulo de estoque responsável pelo controle das entradas e saídas de medicamentos, mantendo a quantidade disponível atualizada.

O projeto possui regras de negócio para garantir a integridade das informações, como a validação de identificadores únicos, o controle da disponibilidade dos medicamentos e a verificação do estoque antes das requisições de saída, facilitando o acompanhamento e a organização dos medicamentos.

## Funcionalidades

### Fornecedores

- Cadastro, visualização, edição e exclusão
- Validação de CNPJ único

### Medicamentos

- Cadastro e gerenciamento de medicamentos
- Controle da quantidade em estoque
- Associação com fornecedores
- Identificação de medicamentos com menos de 20 unidades
- Atualização da quantidade quando o medicamento já está cadastrado

### Pacientes

- Cadastro, visualização, edição e exclusão
- Validação de CPF e Cartão do SUS
- Validação de Cartão do SUS único

### Funcionários

- Cadastro, visualização, edição e exclusão
- Validação de CPF único

### Controle de Estoque

- Registro e visualização de requisições de entrada
- Atualização automática do estoque nas entradas
- Registro e visualização de requisições de saída
- Associação das saídas aos pacientes e medicamentos
- Verificação da quantidade disponível antes da saída
- Atualização automática do estoque após as saídas

### Tecnologias utilizadas
C#
ASP.NET Core MVC
Razor / CSHTML
Bootstrap
SQL Server
Entity Framework Core

Desenvolvido durante o curso Backend da [Academia do Programador](https://www.academiadoprogramador.net) 2026
