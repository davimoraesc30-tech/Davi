#SQL

SELECT [NationalIDNumber] as Identidade,
[JobTitle] as Cargo,
[BirthDate] as DataNascimento,
[Gender] as Genero,
[HireDate] as DataContratação

FROM HumanResources.Employee
WHERE [BirthDate]  between '01/01/1980' and '31/12/2000'
