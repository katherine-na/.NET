# .Net

## Fundamentos .Net

### ¿Qué es .Net?
Es una plataforma de desarrollo creada por Microsoft con la finalidad de crear facilmente aplicaciones utilizando un único SDK.

- Fue creada en 2016
- De código abierto y gratuito
- Multiplataforma 
- Programado en C# y C++
- Orientado a un gran rendimiento en la nube

### .Net Framework vs .Net Core

.Net Framework fue la primer versión en 2001 y fue compatible unicamente con Windows. 

.Net Core es la versión moderna multiplataforma y es = .Net

### Ventajas y usos .Net
.Net nos permite:
- Crear aplicaciones de consola y librerías 
- Aplicaciones web, web API's usando ASP.Net 
- Aplicaciones móviles usando Xamarin y NET MAUI
- Aplicaciones web usando web assembly con Blazor 

### Ventajas
- Multiplataforma
- compatible con múltiples lenguajes de programación
- Herramientas y librerías gratuitas
- Evolución y mejoras
- Apoyo de la comunidad y documentación 
- Soporte continuo 
- Integración con servicios Microsoft 
- Retrocompatibilidad

### Línea de tiempo .NET


| Año  | .NET Framework/Core/5+              | Versión de C#        |
|------|-------------------------------------|----------------------|
| 2000 | .NET Framework 1.0                 | C# 1.0              |
| 2002 | .NET Framework 1.1                 | C# 1.1              |
| 2003 | .NET Framework 1.2                 | C# 2.0              |
| 2005 | .NET Framework 2.0                 | C# 3.0              |
| 2007 | .NET Framework 3.0                 | C# 3.5              |
| 2008 | .NET Framework 3.5 SP1             | C# 3.5 SP1          |
| 2010 | .NET Framework 4.0                 | C# 4.0              |
| 2012 | .NET Framework 4.5                 | C# 5.0              |
| 2013 | .NET Framework 4.5.1               | C# 5.0.1            |
| 2014 | .NET Framework 4.6                 | C# 6.0              |
| 2015 | .NET Framework 4.6.1               | C# 6.0.1            |
| 2016 | .NET Core 1.0                      | C# 7.0              |
| 2017 | .NET Core 1.1 / .NET Framework 4.7 | C# 7.1              |
| 2018 | .NET Core 2.0 / .NET Framework 4.7.1 | C# 7.2            |
| 2019 | .NET Core 3.0 / .NET Framework 4.8 | C# 8.0              |
| 2020 | .NET 5.0                           | C# 9.0              |
| 2021 | .NET 6.0                           | C# 10.0             |
| 2022 | .NET 7.0                           | C# 11.0             |
| 2023 | .NET 8.0                           |                     |

> **Nota:** .NET Framework solo es compatible con Windows, mientras que .NET Core y sus versiones sucesoras (.NET 5+) son multiplataforma. Además, Visual Studio Code es un editor gratuito y de código abierto que puede utilizarse para desarrollar aplicaciones .NET.

#### CLR
Es la base con la que se ejecutan los programas en .NET ya sea en máquina local o servidores
##### Caracteristicas:

- Transforma CIL o MSIL a código nativo.
- Compilador en tiempo en ejecución 
- Agiliza la ejecución del código compilado

*Buscar más definición*

#### Compilador Roslyn
Roslyn es conocido como .Net Compiler plataforma. Soporta C# y Visual Basic y analiza el estilo y calidad de código usando niveles de severidad.  
Roslyn viene integrado por defecto en Visual Studio y al dotnet CLI.


#### Common Language specification
Permite compilar los lenguajes de alto nivel en el lenguaje común  
- Diseñado para lenguajes compilados
- Soporta C#, Visual Basic, F#
- Permite comunicación entre componentes de diferentes lenguajes

##### Common Type System
Define los tipos generales que se usan dentro del lenguaje, provee la librería base para los tipos primitivos (byte, char, int) y provee un modelo de tipos orientado a objetos

###### Categorias del CTS
- Clases
- Estructuras
- Enumeraciones
- Interfaces 
- Delegados

#### IDEs para trabajar con .NET

Visual Studio
- Integrado a .Net Framework y .NET Core
- Soporta todos los tipos de proyectos de .NET
- Soporta extensines para ampliar funciones
- Nueva versión cada 3 años
- Plataforma Windows
- Versión Community, Profesional, Enterprise

Rider
- Más ligero que Visual Studio
- Herramientas avanzadas de autocompletado
- Multiplataforma
- Contiene las herramientas de Resharper

VS Code
- Multiplataforma
- Ligero
- Extensiones para potencializar
- Gratuito y de código abierto
- Soporte la mayoria de lnguajes de programación

