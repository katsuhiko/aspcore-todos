# TodoApi

https://docs.microsoft.com/ja-jp/aspnet/core/tutorials/first-web-api?view=aspnetcore-2.2&tabs=visual-studio-code


## Setup

```
cd aspcore-todos
docker-compose up -d
docker exec -it app /bin/bash
```

```
dotnet ef database update
```


## Develop

### Create Migration file

```
dotnet ef migrations add CreateTodoItem
```


## Memo

### Create project

```
docker run --rm -it -v ${PWD}:/app --workdir /app mcr.microsoft.com/dotnet/core/sdk:2.2 dotnet new webapi -o api -n TodoApi
```

### Install MySql.Data.EntityFrameworkCore

```
docker exec -it app /bin/bash
```

```
dotnet add package Pomelo.EntityFrameworkCore.MySql
dotnet add package Microsoft.EntityFrameworkCore.Tools
```

```
dotnet ef --version
```

## 参考

- https://github.com/github/gitignore
