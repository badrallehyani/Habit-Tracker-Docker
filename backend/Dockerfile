FROM mcr.microsoft.com/dotnet/aspnet:8.0 AS runtime
WORKDIR /app
COPY publish ./

CMD [ "dotnet", "backend.dll" ]