This is a complete console application that generates salary slips for a mock small company.

The application consists of six classes:
Staff
Manager : Staff
Admin : Staff
FileReader
PaySlip
Program

The Staff class contains information about each staff in the company. It also contains a virtual method called CalculatePay() that calculates the pay of each staff.

The Manager and Admin classes inherit the Staff class and override the CalculatePay() method.

The FileReader class contains a simple method that reads from a .txt file and creates a list of Staff objects based on the contents in the .txt file. The file is stored in the
same folder where the .exe is located.
You must add contents to the "staff.txt" file in the format of staff name, position. For example: 
Ben, Manager
Peter, Admin
John, Admin
Carol, Manager

The PaySlip class generates the pay slip of each employee in the company. In addition it also generates a summary of the details of staaff who worked less than 10 hours in
a month. The summary file is stored in the same folder where the .exe is located.

Finally the Program class contains the Main() method which is the main entry point of the application.
