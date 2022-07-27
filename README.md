# RazorPagesPizza
![Screenshot - RazorPagesPizza](https://user-images.githubusercontent.com/56870381/180647782-091ea6fa-6fe3-4910-a783-745e8310faaf.png)

See complete tutorial at [Microsoft Docs](https://docs.microsoft.com/en-us/learn/modules/create-razor-pages-aspnet-core/).

---
.NET 6 is required. If not already installed, download the SDK from - https://dotnet.microsoft.com/en-us/download 
```
>dotnet --list-sdks # check availables sdks
6.0.301 [C:\Program Files\dotnet\sdk]
6.0.302 [C:\Program Files\dotnet\sdk]
```

## To use the web app :
- Clone or download repository and `cd` into `RazorPagesPizza` directory.
```
>git clone https://github.com/Omkar76/RazorPagesPizza.git
```
- Run the app with `dotnet` cli.
```
>dotnet run 
Building...
info: Microsoft.Hosting.Lifetime[14]
      Now listening on: https://localhost:7065
info: Microsoft.Hosting.Lifetime[14]
      Now listening on: http://localhost:5089
info: Microsoft.Hosting.Lifetime[0]
      Application started. Press Ctrl+C to shut down.
info: Microsoft.Hosting.Lifetime[0]
      Hosting environment: Development
info: Microsoft.Hosting.Lifetime[0]
      Content root path: D:\CSharp\RazorPagesPizza\
```

- Visit localhost.

- Alternatively you can open the `RazorPagesPizza.sln` file in Visual Studio.

---
<sub>No database is used in this demo app. Data is stored in memory. Closing app (not tab) will destroy all entries.</sub>
