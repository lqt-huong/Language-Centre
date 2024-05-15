# Language-Centre

Language Centre is a simple C# application used for Language center management. The system is used by the center's staff, including 3 main functions: course management, human resource management, and application access management to help the management of the English center operate effectively.
## How to run?
1. Install the database in the following path: Language-Centre/Database/English_Centre.bacpac to your Sql Server Management System
2. Change connection string in DataServices.cs file in this line 
``` c#
const string CONNECTION_STRING = @"Data Source=JOSIE;Initial Catalog=English_Centre;Integrated Security=True"; //connection string của TH

```
3. Start Program.cs file to run this project.
