# Create project

## To list available templates

```zsh
dotnet new list
```

## To create necessary project files

- create gitignore file

```zsh
dotnet new gitignore
```

- create solution file

```zsh
dotnet new sln
```

- create web API

```zsh
dotnet new webapi -n API
```

## Using cli to add or put API projects in the solution file

- check available options

```zsh
dotnet sln -h
```

- add API project in solution using cli

```zsh
dotnet sln add API
```

- list available projects in the solution

```zsh
dotnet sln list
```
