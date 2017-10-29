FROM microsoft/aspnetcore:1.1
COPY . /app
WORKDIR /app
EXPOSE 5000/tcp
ENV ASPNETCORE_URLS http://*:5000/
ENTRYPOINT ["dotnet", "EnvironmentVariable.dll"]