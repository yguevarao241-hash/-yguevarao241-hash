# Northwind WPF

Sistema de gestion de datos para la base de datos Northwind

---

## Que hace este proyecto

Dos ventanas principales para gestionar la base de datos Northwind:

- Buscar Clientes - Filtra clientes por pais
- Gestionar Productos - Visualiza y edita productos

---

## Tecnologias

- C# con .NET
- WPF (Windows Presentation Foundation)
- SQL Server
- XAML

---

## Estructura del proyecto

```
Northwind/
├── frmBuscarClientes.xaml
├── frmBuscarClientes.xaml.cs
├── Productos.xaml
├── Productos.xaml.cs
├── MainWindow.xaml
├── MainWindow.xaml.cs
└── Cliente.cs
```

---

## Base de Datos

Usa la base de datos Northwind de Microsoft.

Configuracion de conexion:

```csharp
Server=.\\SQLEXPRESS;Database=Northwind;Integrated Security=True;TrustServerCertificate=True;
```

---

## Como ejecutar

1. Abre el proyecto en Visual Studio
2. Configura SQL Server con la base de datos Northwind
3. Ejecuta (F5)

---

## Sobre mi

Yesica Yanira - Estudiante de Ingenieria de Sistemas

Peru

---

## Licencia

MIT
