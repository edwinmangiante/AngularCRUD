http://www.c-sharpcorner.com/article/angularjs-crud-operation-using-asp-net-mvc/

Base de datos en SQLServer.

CREATE DATABASE DEMO;

CREATE TABLE [dbo].[Employee](
	[Emp_Id] [int] IDENTITY(1,1) NOT NULL,
	[Emp_Name] [varchar](max) NULL,
	[Emp_City] [varchar](max) NULL,
	[Emp_Age] [int] NULL,
 CONSTRAINT [PK_Employee] PRIMARY KEY CLUSTERED 
(
	[Emp_Id] ASC
)WITH (PAD_INDEX  = OFF, STATISTICS_NORECOMPUTE  = OFF, IGNORE_DUP_KEY = OFF, ALLOW_ROW_LOCKS  = ON, ALLOW_PAGE_LOCKS  = ON) ON [PRIMARY]
) ON [PRIMARY] TEXTIMAGE_ON [PRIMARY]

GO