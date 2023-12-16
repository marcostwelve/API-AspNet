![image](https://github.com/marcostwelve/API-AspNet/assets/94411600/adb00412-4a33-46c4-badf-65a6c6536bb0)


# Agenda de Contatos 

Agenda de contatos, é um projeto para criar e guardar contatos. Com os dados de ID, Nome, Telefone e Status.

## 🔥 Introdução

API foi criada com os métodos Http, com todos os endpoints do Http: Get, Post, Put, Delete

### ⚙️ Pré-requisitos
* Visual Studio
* Entity Framework
* .Net Core
* ASP.Net
* Sql Server (Ou outro banco de dados)


### 🔨 Guia de instalação

Para utilizar este projeto, necessário instalar o Entity Framework, e configurar o banco de dados no arquivo appsettings.Development.json, e instalar as migrations para conexão com o banco de dados

Etapas para instalar:

```bash
dotnet tool install --global dotnet-ef
```
Passo 2:
```bash
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
```
Passo 3:
```bash
Install-Package Microsoft.EntityFrameworkCore.Design
```
Passo 4:
```bash
dotnet-ef migrations add (Nome da migration do projeto)
```

Passo 5:
```bash
dotnet-ef database update
```


## 🛠️ Executando os testes (caso tenha testes)

Para executar o projeto, para testes. Digite o seguinte comando no terminal do Visual Studio

```bash
dotnet watch run
```

### Método Get

O Método Get, realiza a busca todos os contatos e mostra na página inicial do projeto

![image](https://github.com/marcostwelve/API-AspNet/assets/94411600/a1f02185-821e-4167-8c80-6c73cf21f666)


### Método Post
O método Post, realiza a criação de um novo contato, onde há um formulário para preencher os dados
![image](https://github.com/marcostwelve/API-AspNet/assets/94411600/e9625c3a-b04d-4350-ac46-4ccf0c512e8a)


Caso algum campo não seja preenchido, ele será salvo como nulo

### Método Put
O método Put, irá atualizar o contato, com preenchimento de todos os campos.
![image](https://github.com/marcostwelve/API-AspNet/assets/94411600/08daabda-06dd-4e3e-9466-906861297f0c)


### Método Delete
O método Delete, irá deletar o contato do banco de dados, sendo uma operação irreversível
![image](https://github.com/marcostwelve/API-AspNet/assets/94411600/b9f547e5-6d33-4d10-bff1-fe1b0f4d4e1c)


## 📦 Tecnologias usadas:

Coloque aqui as ferramentas que você usou para criar seu projeto, exemplo:

* [C#](https://learn.microsoft.com/pt-br/dotnet/csharp/tour-of-csharp/)
* [ASP.Net](https://dotnet.microsoft.com/pt-br/apps/aspnet)
* [Entity Framework](https://learn.microsoft.com/pt-br/ef/core/get-started/overview/install)
* [SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads)



## 👷 Autores

* **Maurício Marcelino** - *Back-End do projeto* - [Maurício Marcelino](https://github.com/marcostwelve)

## 📄 Licença

Esse projeto está sob a licença (MIT) - acesse os detalhes [LICENSE.md](https://opensource.org/license/mit/).

## 💡 Expressões de gratidão

* Agradeço todos por verificarem o meu projeto. Esotu aberto a sugestões de melhorias e evolução do projeto.
* [Meu linkedin](https://www.linkedin.com/in/mauricio-marcelino/)
