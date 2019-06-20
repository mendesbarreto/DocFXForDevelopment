[![Build Status](https://dev.azure.com/DouglasMendes0782/ProjectClient/_apis/build/status/mendesbarreto.DocFXForDevelopment?branchName=master)](https://dev.azure.com/DouglasMendes0782/ProjectClient/_build/latest?definitionId=1&branchName=master)

# Setup

To setup this project in your local host follow the steps:

## Step 1 - Install Chocolatey in your machine

1. If you have Choco installed in your machine jump for Step 2.

1. Open PowerShell as Admin
1. Run the follow command inside PowerShell

```shell
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```


## Step 2 - Install DocFx

DocFx will be responsable to generate the documentation from your markdonw.

1. With your powershell opened run the follow command

```
choco install docfx -y
```

## Step 3 - Runing DocFx

1. Download the project using git

````git
git clone https://github.com/mendesbarreto/DocFXForDevelopment.git
````

1. Enter on folder  DocFXForDevelopment:

```shell
cd DocFXForDevelopment
``` 

1. Run the command

```shell
 docfx docfx_project/docfx.json --serve
```

1. On the internet browser access the link ```http://localhost:8080```
