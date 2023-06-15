# base-ddd-mvc-ef-ioc-proj

Base ASP.NET MVC (Classic .Net Framework) Project using DDD, EF (Code First &amp; Migrations), IoC and AutoMapper

## Synopsis

This is a Sample Project with some technologies/patters such as:
- ASP.NET MVC
- Classic .Net Framework
- DDD
- SQL Server
- Entity Framework (Code First and Migrations)
- IoC (DI with Simple Injector)
- AutoMapper
- Log (with NLog)
- Cache
- Session/Cookies
- Generics
- Linq

## Motivation

This Project was Designed to be a bootstrap and/or reference for similar projects.

## Installation

To set up this project you will need to:

- Install Visual Studio (You may get it at : https://www.visualstudio.com/pt-br/thank-you-downloading-visual-studio/?sku=Community&rel=15);
- Install SQL Server (You may get it at : https://www.microsoft.com/pt-br/sql-server/sql-server-editions-express);
- Optionally Install SQL Server Management Studio (You may get it at : https://docs.microsoft.com/pt-br/sql/ssms/download-sql-server-management-studio-ssms);
- Clone/Download this project (You may get it at: https://github.com/felipeolimpos/base-ddd-mvc-ef-ioc-proj);
- Open Solution using Visual Studio;
- Edit POS > Presentation > POS.Web > Web.config file and set your own Connection String (Under Configuration > connectionStrings);
- Build Solution (Ctrl + Shift + B);
- Open Package Manager Console;
- Select "Presentation\POS.Infra.Data" as Default Project;
- Still on Console, run "Update-Database" command;
- Go ahead and HAPPY CODING !!!

