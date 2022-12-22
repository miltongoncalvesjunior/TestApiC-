dotnet new webapi -o TodoApi
cd TodoApi
dotnet add package Microsoft.EntityFrameworkCore.InMemory
code -r ../TodoApi

Estes comandos:

Crie um novo projeto de API Web e abra-o no Visual Studio Code.
Adicione um pacote NuGet necessário para a próxima seção.


Confie no certificado de desenvolvimento HTTPS executando o seguinte comando:


dotnet dev-certs https --trust