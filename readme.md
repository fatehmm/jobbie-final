# Jobbie - is tapma platformu

## Dependencyler
 - ASP.NET Core MVC
 - PostgreSQL
 - node.js & npm 

## Baslayarken 

1. `appsettings.json` da  `ConnectionStrings` deyerini local masininiza uygun deyisin: 

`  "DefaultConnection": "Server=localhost;Port=5432;Database=CourseWorkJob1;Uid=postgres;Password=OnyxOrion01;"
`

2. Lazimi migration & database updateleri heyata kecirin.
3. `localhost/account/createroles` endpointine proyekt ilk defe acilarken `GET` request atin (ilk defe ucun lazim olacaq)
4. Jobbie-ni isletmeyhe baslayin.