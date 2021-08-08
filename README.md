# ReactJsCSharpCoreApi
Full Stack React Js Front End connect C# Asp.Net Core Web Backend [MSSQL]

## Donation

If this project helped you reduce time to develop, please consider buying me a cup of coffee :)

<a href="https://www.buymeacoffee.com/ongyishen" 
target="_blank">
<img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" 
alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>



------



## Mssql Database

Create database with name **EmployeeDB** and run the **DbScripts.sql**

DB Screenshot

<img src="https://github.com/ongyishen/ReactJsCSharpCoreApi/blob/main/SampleDB.PNG?raw=true" />

------



## C# Asp.Net Core Web [BackEnd]

Change the database connection string at appsetting.json

```json
"ConnectionStrings": {
    "EmployeeAppCon": "Data Source=(local);Initial Catalog=EmployeeDB; Integrated Security=true"
  }
```

Backend Screenshot
<img src="https://github.com/ongyishen/ReactJsCSharpCoreApi/blob/main/SampleBackend.gif?raw=true" />

------



## React JS [Front End]

Change the Backapi API UTL at .env file

```javascript
REACT_APP_API=http://localhost:50306/api/
REACT_APP_PHOTOPATH=http://localhost:50306/Photos/
```

Run 

```bash
npm init
```

Start the front end

```bash
npm start
```

Frontend Screenshot

<img src="https://github.com/ongyishen/ReactJsCSharpCoreApi/blob/main/Sample.gif?raw=true" />

