# Personal Blog
Angular 8 CRUD blog app with .NET Core 2.2 and Entity Framework back-end

## Prerequisites

* [.NET Core 2.2 SDK](https://dotnet.microsoft.com/download)

* [Visual Studio 2019](https://visualstudio.microsoft.com/vs/)

For the Angular front-end, we'll also use:

* [VS Code](https://code.visualstudio.com/)

* [Node.js](https://nodejs.org/en/)

* [Angular CLI](https://cli.angular.io/)

If you clone the repo, make sure you set up the database and Entity Framework migrations!
Here's how:

In Visual Studio 2019:

1. Remove the contents of the folder Migrations.
2. Then open the Package Manager Console (Tools->Nuget Package Manager->Package Manager Console).
3. Run the following commands:

```bash
Add-Migration Initial
Update-Database
```

4. Now press F5 and run the application. You will have an empty blog list to start with.

## Debugging
If you get an error message running the app, first make sure you installed node modules using the `npm install` command.
In VS Code or in the Node.js command prompt, run `npm install` in the ClientApp folder.

Make sure you've installed the following as well:
1. Angular CLI using the `npm install -g @angular/cli` command.
2. @angular-devkit/build-angular module using the `npm install --save-dev @angular-devkit/build-angular` command.

---

**About Me:**
This tutorial was brought to you by alae-eddine sahbou. You can find more of my projects and contributions on [GitHub](https://github.com/alaesahbou).