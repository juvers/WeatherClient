This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

#### 1. (Launch project in VS) Visual Studio 2019 -> Create New Project ->  ASP.NET Core Web application
#### 2. (Name project in VS) Project name -> Create -> ASP.NET Core 3.0 -> Empty -> Create
#### 3. (Create react app in cli - identify root folder of project name in #2) npx create-react-app weatherclient --typescript 
#### 4. (Install Modules) Install ASP.NET Core SPA Services and ASP.NET Core SPA Services Extensions in Nuget Manager.
#### 5. (Import modules as needed)
i. using Microsoft.AspNetCore.SpaServices.ReactDevelopmentServer;
ii. spa.Options.SourcePath = System.IO.Path.Join(env.ContentRootPath, "weatherclient");