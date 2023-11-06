# Cadastro_de_-Empresas--CRUD-

# Sistema de Cadastro de Clientes

<div align="center">
  <img src="https://github.com/LaiFrance/Cadastro-de-Clientes/assets/91226847/acb28c13-f9a3-4fbe-b07f-61aa04519744" width="200" height="200">
</div>

## Instruções de como executar o projeto na sua máquina local 
Clone o repositório:
Abra um terminal e navegue para o diretório onde você deseja clonar o repositório. Em seguida, execute o seguinte comando para clonar o repositório:

```
git clone git@github.com:LaiFrance/Energizou-Cadastro-Crud.git
```

Acesse o diretório do projeto:
Use o comando cd para entrar no diretório do projeto recém-clonado:
 ```
cd Energizou-Cadastro-Crud
```

### Tabela Mysql do Projeto 

![image](https://github.com/LaiFrance/Energizou-Cadastro-Crud/assets/91226847/66c0b458-4530-4f1a-85a9-974920f40e3f)


 ## Instruções Gerais

O projeto é dividido em duas partes: back-end e front-end
## 🚀 Começando

Siga as etapas abaixo para configurar e executar o projeto em seu ambiente local.

### 📋 Pré-requisitos

- Node.js: [Instalação do Node.js](https://nodejs.org/)
- MySQL: [Instalação do MySQL](https://dev.mysql.com/doc/mysql-installation-excerpt/en/)

| Tecnologia | Descrição |
| --- | --- |
| Node.js | Ambiente de execução do servidor |
| MySQL | Sistema de gerenciamento de banco de dados |
| React | Biblioteca JavaScript para construção da interface do usuário |


### 🔧 Instalação

1. Clone este repositório em sua máquina local:

### Yarn



## Back-End (Node.js)

O back-end é um servidor Node.js que fornece uma API RESTful para gerenciar empresas e funcionários (CRUD).

### Endpoints
- `POST /`: Cria uma usuario.
- `GET /`: Lista todos os usuários
- `GET /:id`: Consulta um usuario especifico.
- `PUT /:id`: Atualiza o usuario.
- `DELETE /:id`: Exclui o usuario.

- `POST /empresa`: Cria uma nova empresa.
- `GET /empresas`: Lista todas as empresas cadastradas.
- `GET /empresa/:id`: Consulta uma empresa específica por CNPJ.
- `PUT /empresa/:id`: Atualiza os dados de uma empresa.
- `DELETE /empresa/:id`: Exclui uma empresa.

## Front-End (React)

O front-end é um aplicativo React que permite ao usuário:

- Criar uma nova empresa.
- Listar todas as empresas cadastradas.
- Consultar uma empresa específica por CNPJ.
- Editar os dados de uma empresa.
- Excluir uma empresa.

O aplicativo React se conecta ao back-end por meio de requisições HTTP.

## Executando o Projeto

1. Inicie o servidor MySQL.
2. Navegue até o diretório do back-end e execute `yarn start` para iniciar o servidor Node.js.
3. Em outro terminal, navegue até o diretório do front-end e execute `npm start` para iniciar o aplicativo React.

## Contribuindo

Pull requests são bem-vindos. Para mudanças importantes, abra um problema primeiro para discutir o que você gostaria de mudar.

## Licença

MIT


