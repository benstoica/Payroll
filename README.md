### This is a complete console application that generates salary slips for a mock small company.

The application consists of six classes:
- Staff
- Manager : Staff
- Admin : Staff
- FileReader
- PaySlip
- Program

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


![staff](https://user-images.githubusercontent.com/13625714/89697276-77604980-d8e9-11ea-984a-36eaf7719a0f.png)
![image](https://user-images.githubusercontent.com/13625714/89697311-a1197080-d8e9-11ea-85ce-525ef76e39f5.png)
![image](https://user-images.githubusercontent.com/13625714/89697321-ad053280-d8e9-11ea-873c-5e22be66006d.png)
![image](https://user-images.githubusercontent.com/13625714/89697333-b68e9a80-d8e9-11ea-8ff1-47a0b1dfe92f.png)
![image](https://user-images.githubusercontent.com/13625714/89697490-4e8c8400-d8ea-11ea-8b5a-2510e2b5ee15.png)
![image](https://user-images.githubusercontent.com/13625714/89697438-15ecaa80-d8ea-11ea-8efa-26234e4ede4a.png)
![image](https://user-images.githubusercontent.com/13625714/89697450-21d86c80-d8ea-11ea-855a-12fe05ea5df7.png)
![image](https://user-images.githubusercontent.com/13625714/89697461-2a30a780-d8ea-11ea-978c-5f25463040f6.png)
![image](https://user-images.githubusercontent.com/13625714/89697518-724fca00-d8ea-11ea-9890-e881f874b78b.png)
![image](https://user-images.githubusercontent.com/13625714/89697529-7c71c880-d8ea-11ea-9609-f6ca1320d37c.png)

