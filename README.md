# WarrantyAPI
Servizio REST per la gestione di veicoli e pratiche di garanzia. Lo sto scrivendo per studiare ASP.NET Core Web API e SQL Server oltre il livello base.

Stack: .NET 10, ASP.NET Core Web API con controller, Entity Framework Core su SQL Server, NUnit per i test.

##Struttura
- WarrantyApi: il servizio
- WarrantyApi.Tests: i test

##Per farlo girare
Serve un'istanza di SQL Server con un database vuoto WarrantyDb. La stringa di connessione è in WarrantyApi/appsettings.Development.json, da adattare al proprio server.
