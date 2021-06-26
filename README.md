# dotnethi2
hello world c# dotnet with docker project

## run

```sh
dotnet run
```

## build 

Referece see [doc](https://docs.microsoft.com/en-us/dotnet/core/deploying/#self-contained-deployments-scd)


```sh
dotnet publish -c Release

docker build -t dotnethi2:v1 .
```

## run

```sh
docker run -it --rm dotnethi2:v1
```