# API .NET core com MongoDB

Possui suporte para os verbos GET, POST, PATCH e DELETE.
Precisa configurar a ConnectionString no arquivo appsettings.json.

- Exemplos de uso:

GET:

https://localhost:5001/infectado/

POST:

https://localhost:5001/infectado/

{
	"dataNascimento": "1990-03-01",
	"sexo": "F",
	"latitude": -25.5630994,
	"longitude": -49.6565712
}

PATCH:

https://localhost:5001/infectado/

{
	"dataNascimento": "1990-03-01",
	"latitude": -30.4578996,
	"longitude": 15.7894562
}

DELETE:

https://localhost:5001/infectado/1990-03-01



  



