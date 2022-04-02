# SENAI-SP . UC12 - SA2  - Atividade online 3

# Projeto ClientLab

## ![contrato](https://user-images.githubusercontent.com/88597534/160513226-455b3b55-619f-4388-9ae1-c594860342bb.png) Descrição
Sistema desenvolvido para cadastro de Pessoas Físicas e Jurídicas. 

## ![funcional](https://user-images.githubusercontent.com/88597534/160514347-c5e58db7-4f55-41a6-afda-c75b7b1eba46.png) Funcionalidades
O sistema realizará a programação de um sistema de cadastro de clientes customizado (Pessoas Físicas e Jurídicas), atendendo às seguintes características:

- [x] O sistema de clientes deverá armazenar os cadastros das Pessoas Físicas e Jurídicas;

- [x] O cadastro das Pessoas Físicas é feito com os seguintes dados: nome, rendimento, CPF e data de nascimento;

- [x] O cadastro das Pessoas Jurídicas é feito com os seguintes dados: nome, rendimento, CNPJ e razão social;

- [x] Ambos devem possuir um endereço e indicar se o endereço é comercial ou residencial;

- [x] O sistema não irá permitir o cadastro de uma Pessoa com o CPF ou CNPJ já armazenados previamente.

- [x] O sistema deve armazenar os registros em arquivos de extensão ".txt" ou ".csv".

![clock](https://user-images.githubusercontent.com/88597534/161317745-9f938ddd-379e-42db-831c-5cfca06f7067.png) __Em tempo__: 

Foram criados 2(dois) projetos:  

- Na atividade online 2, os dados são armazenados em arquivos de extensão ".txt". 

- No encontro remoto 8,  os dados são armazenados em arquivos de extensão ".csv".

O projeto inicial , tinha como objetivo proposto o cadastro e a listagem de Pessoas(Físicas ou Jurídicas). Com o intuito de aprendizagem , antes mesmo da construção do sistema, foram pensadas em algumas melhorias ou soluções para que fossem aplicadas ao projeto inicial. Portanto, o sistema também irá permitir ao usuário realizar as seguintes funcionalidades:

- [x] A atualização de Pessoas Físicas ou Jurídicas;

- [x] A busca por uma Pessoa Física ou Jurídica;

- [x] A remoção de uma Pessoa Física ou Jurídica;

- [x] A remoção de todas as Pessoas ( Físicas ou Jurídicas );


## ![rocket](https://user-images.githubusercontent.com/88597534/160514865-439df82c-f169-4783-8554-3720d04f00ed.png) Tecnologias utilizadas

-   [Linguagem de desenvolvimento C#](https://docs.microsoft.com/pt-br/dotnet/csharp/)
-   [.NET 6.0](https://dotnet.microsoft.com/en-us/download)
-   [Visual Studio Code](https://code.visualstudio.com/download)   

## ![blueprint](https://user-images.githubusercontent.com/88597534/160515241-95aeaf07-31e8-47f1-a9fb-899ae702466a.png) Organização do projeto

Foi utilizado o paradigma padrão de _programação orientada a objetos_, onde as classes representam uma abstração do mundo real. Para tal foram usados também conceitos de herança. As classes utilizadas foram : Pessoa (classe-pai), Pessoa Física e Pessoa Jurídica(classes-filhas) e a classe Endereço a qual foi agregada à classe Pessoa. Também foram criadas as interfaces relacionadas.

## ![cd](https://user-images.githubusercontent.com/88597534/160516653-6a574855-3d05-4c3f-8dd9-240a340fa64c.png) Pré-requisitos da instalação

É necessária a instalação do DOTNET (.NET) runtime versão atual 6.0 ou superior para executar a aplicação pelo terminal do Windows. Acesse o site:
https://dotnet.microsoft.com/en-us/download

Caso ocorra alguma atualização no link de acesso do .NET acima, acessar o portal principal: 
https://dotnet.microsoft.com/en-us/ e clicar na aba downloads.

Instruções e detalhes para a instalação no Windows , podem ser acessadas em :
https://docs.microsoft.com/pt-br/dotnet/core/install/windows?tabs=net60

## ![tracking](https://user-images.githubusercontent.com/88597534/160517170-bd52fe21-a985-4fc8-b42c-144de734382e.png) Execução da aplicação

A aplicação foi desenvolvida utilizando o Sistema Operacional Windows 10. Para executar a aplicação :

1-Faça um clone do projeto na sua máquina :

```
git clone https://github.com/MarceloDev100/senai-uc12-sa2-atividade-online3.git
```
Ou se preferir, faça o download do conteúdo, clicando no botão Code > Download Zip. Logo depois, faça sua descompactação.

2-Acesse o diretório contendo um dos projetos pelo _terminal do prompt de comando do Windows_:

- _Projeto Atividade online 2:_
 
``` 
cd "caminho do diretório"/senai-uc12-sa2-atividade-online3/atividade-online2  
```

__OU__

- _Projeto Encontro remoto 8:_

```
cd "caminho do diretório"/senai-uc12-sa2-atividade-online3/encontro-remoto8
```  

3-Em seguida, execute a aplicação: 
```
dotnet run
```

Ou então, se preferir, basta fazer o download, por exemplo,  do instalador da aplicação ClientLab-txt para Windows e seguir os passos abaixo: 

![10](https://user-images.githubusercontent.com/88597534/161316811-c152eba9-3a64-4a57-8e2c-e8e4a831741a.jpg)

![11](https://user-images.githubusercontent.com/88597534/161316818-ebfd9e72-d8d1-447d-be38-3088b20a7fa2.jpg)

![12](https://user-images.githubusercontent.com/88597534/161316825-08138dd7-0b39-488f-a1f7-3673a6511775.jpg)

![13](https://user-images.githubusercontent.com/88597534/161316828-02bdc46b-ed26-4cc0-bd87-1aecdf93c2f2.jpg)


__Observação__: Caso opte por realizar a instalação da aplicação ClientLab-csv, os mesmos passos acima são requeridos.

Após a instalação , um ícone da aplicação ClientLab será criado, conforme figura abaixo, na área de trabalho do Windows : 

![14](https://user-images.githubusercontent.com/88597534/160504777-4f4fb175-9727-4c7c-905f-bbf14b63546b.jpg)

## ![warning](https://user-images.githubusercontent.com/88597534/160517997-40811145-6a1c-49d1-ac41-45d052694576.png)  Erros comuns

- A instalação da versão incorreta do .NET para execução da aplicação.

- Acesso ao diretório incorreto para execução da aplicação pelo terminal do Windows.

## ![group](https://user-images.githubusercontent.com/88597534/160518220-1ca484bb-53c9-452b-b2a4-f9bc2914aef4.png)  Contribuidores

Aluno SENAI-SP : Marcelo Marques.

-----------------------------------------

<h4>Curso de Qualificação Desenvolvedor FullStack - Módulo BackEnd SENAI-SP.</h4>
