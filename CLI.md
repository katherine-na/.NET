## CLI - Command Line Interface

Comando para validar instalación de .NET

```
dotnet
```

Comando para saber la versión
```
dotnet --version
```
 
Comando que nos brinda información de como funciona el CLI y lista de comandos

```
dotnet --help
```

Comando para ver las funciones que tenemos para crear un nuevo proyecto .Net

```
dotnet new
```

```
dotnet new console
```

Comando para correr nuestro proyecto
```
dotnet run
```

Comando para copilar nuestro proyecto en tiempo real
```
dotnet watch run
```

## Caracteristicas del archivo .csproj 
- El archivo consoleapp.csproj no contiene nada de lógica, es un archivo de configuración.
- Tiene un formato XML
- En la parte superior se especifica un SDK, este varía de acuerdo al tipo de proyecto con el que estamos trabajando.
- El OutputType es el resultado que tendríamos de la publicación del proyecto
- El TargetFramework es la versión del Framework con la cual se está ejecutando el proyecto
- El ImplicitUsing nos ayuda a que no tengamos que especificar las librerías que vayamos a necesitar dentro de nuestros archivos de código.

```c#
<Project Sdk="Microsoft.NET.Sdk">

  <PropertyGroup>
    <OutputType>Exe</OutputType>
    <TargetFramework>net6.0</TargetFramework>
    <ImplicitUsings>enable</ImplicitUsings>
  </PropertyGroup>

</Project>

```

> **Nota:** El archivo .csproj y Program.cs son los archivos base de cualquier proyecto en .Net

En la carpeta “bin” se encuentran los archivos compilados.
Comando para Eliminar archivos compilados

> dotnet clean
2 modos de compilación en .NET
Modo Debug

Modo Release

< dotnet build --configuration realease
Se crea la carpeta “Debug” y “Release”

