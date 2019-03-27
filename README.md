# TodoApi

https://docs.microsoft.com/ja-jp/aspnet/core/tutorials/first-web-api?view=aspnetcore-2.2&tabs=visual-studio-code

## Setup

```
docker run --rm -it -v ${PWD}:/app --workdir /app mcr.microsoft.com/dotnet/core/sdk:2.2 dotnet new webapi -o api -n TodoApi
```

## MySQL

```
docker run --rm -it -v ${PWD}:/app --workdir /app mcr.microsoft.com/dotnet/core/sdk:2.2 dotnet add package MySql.Data.EntityFrameworkCore
docker run --rm -it -v ${PWD}:/app --workdir /app mcr.microsoft.com/dotnet/core/sdk:2.2 dotnet add package Microsoft.EntityFrameworkCore.Tools
```

```
docker run --rm -it -v ${PWD}:/app --workdir /app mcr.microsoft.com/dotnet/core/sdk:2.2 dotnet ef --version
```

## 参考

- https://github.com/github/gitignore
