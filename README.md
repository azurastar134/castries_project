# castries_project

A project of microservices written in C# and NextJS mainly.

## Creating the database

dotnet ef migrations add "InitialCreate" -o Data/Migrations

The command above creates the migrations in Data folder.

## Updating the database with new information

dotnet ef migrations update

## How to launch docker

Use docker-compose to instatiate the container.
