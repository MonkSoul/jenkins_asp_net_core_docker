FROM mcr.microsoft.com/dotnet/core/aspnet:2.2

WORKDIR /app

ADD ./publish /app

EXPOSE 80 443

ENTRYPOINT ["dotnet","aspnetcoredocker.dll"]