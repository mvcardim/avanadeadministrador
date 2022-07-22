# API dotnet com ajustes para 6.0

## Ao baixar o projeto instrua o seguinte comando com
`dotnet run`

## Para rodar a migration:
```
  dotnet tool install --global dotnet-ef
  dotnet ef migrations add AdmAdd
  dotnet ef database update
```