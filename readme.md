Persiapan sebelum menjalankan Program :
lakukan dotnet new webapi -o api pada terminal
dotnet add package Microsoft.EntityFrameworkCore.SqlServer pada terminal
dotnet ef migration add init pada terminal
dotnet tool install --global dotnet-ef --version 8.\* pada terminal
install extension nuget gallery, Microsoft.EntityFrameworkCore.SqlServer, newtonsoftjson, Microsoft.AspNetCore.Mvc.NewtonsoftJson

install package
dotnet ef migrations add init pada terminal memigrasi ke db
donet ef database update pada terminal
dotnet watch run pada terminal untuk menjalankan api
