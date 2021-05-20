FROM mcr.microsoft.com/dotnet/sdk:5.0
WORKDIR /app
COPY ./bin/Debug/net5.0/publish/*.* /app/
EXPOSE 8085

ENTRYPOINT ["dotnet", "dotnet.dll"]
