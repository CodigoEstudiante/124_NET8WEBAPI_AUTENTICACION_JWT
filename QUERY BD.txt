create database DBPrueba
go
use DBPrueba

go

create table Usuario(
IdUsuario int primary key identity,
Nombre varchar(50),
Correo varchar(50),
Clave varchar(100)
)

go

create table Producto(
IdProducto int primary key identity,
Nombre varchar(50),
Marca varchar(50),
Precio decimal(10,2)
)

go


select * from Usuario

insert into Producto
(Nombre,
Marca,
Precio)
values
(
'Laptop gamer 1001',
'HP',
3500
),
(
'Monitor curvo HD',
'Samsung',
2000
)

select * from Producto

SELECT NEWID()
SELECT LEN('B016924A-DE13-4CA2-A828-B0ED7F9D9EB8')