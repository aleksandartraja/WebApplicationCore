FROM microsoft/dotnet:1.0.0-preview2-windowsservercore-sdk
ENTRYPOINT ["dotnet", "WebApplicationCore.dll"]
ARG source=.
WORKDIR /app
ENV ASPNETCORE_URLS http://+:82
EXPOSE 82
COPY $source .
