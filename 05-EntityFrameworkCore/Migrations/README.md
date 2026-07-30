# Lab 3: EF Core Migrations

Run these commands from the `RetailInventory` project folder:

```powershell
cd RetailInventory
dotnet ef migrations add InitialCreate
dotnet ef database update
```

This creates the `Migrations/` folder and applies schema to SQL Server LocalDB.

Verify in SSMS or Azure Data Studio that `Products` and `Categories` tables exist in `RetailInventoryDB`.
