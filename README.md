# Description

Create a Class "DCommon" with the following 
properties : id (Long), createdDate (Date), updatedDate (Date), createdBy String, 
       updatedBy String, state Long, version Long

Create a Class “Person” extending class "Dcommon" with the following 
properties: birthDate (Date), lastName (String), firstName (String)

Create a Class “Employee” with the following 
properties: salary (Double), years (years spent in the company) and lastName, birthDate, firstName. 

Create Interface “View” with method getDataView() return as String.
Implements the interface View with the Employee class to display all the data of an employee.

Create a class “Developer” extends employee with properties: comment.
 Add a constructor so we can create a Developer from an Employee Object.
Implement the Interface View to display:  fullName + comment  + salary

Create a class “TeamLeader” with properties : projectNum.
Implements the interface View to display:  fullName: UPPERCASE_NAME + number of projects
(use StringBuffer to manipulate string, the fullName should be in UPPERCASE)

Create an employee, a developer and a teamleader object. Put them in an arrayList of Employee.
Loop on the array and display the information using the getDataView Method.

Display the information by accessing directly to the object. 
for example: 	Developer dev = new Developer();
dev.getDataView(); 
========
