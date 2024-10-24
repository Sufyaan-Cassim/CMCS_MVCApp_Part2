Claim Management System
The Claim Management System allows lecturers to submit claims, while a Programme Manager (PM) can review those claims. The application is designed to streamline the process of claim submission and approval.

Prerequisites
Before you begin, ensure you have met the following requirements:

A compatible version of Visual Studio installed on your computer.
.NET Framework installed.
Access to a SQL Server database for data storage.
Installation Instructions
Clone the Repository
Open your command line interface (CLI) and run the following command to clone the repository to your local drive:

bash
Copy code
git clone https://github.com/Sufyaan-Cassim/CMCS_MVCApp_Part2.git
Navigate to the Project Directory
After cloning the repository, navigate to the project directory:

bash
Copy code
cd demo_part2
Open the Project in Visual Studio

Open Visual Studio.
Select "Open a project or solution."
Navigate to the cloned repository and open the .sln (solution) file.
Configure the Database

Ensure that your SQL Server is running.
Update the connection string in the appsettings.json file to match your local database configuration.
Running the Application
Build the Project

In Visual Studio, go to the "Build" menu and select "Build Solution."
Ensure there are no build errors.
Run the Application

Press F5 or click on the "Start" button in Visual Studio to run the application.
The application will launch, and you can interact with the user interface.
Usage
For Lecturers:

Register a new account or log in if you already have an account.
Submit claims for review by filling out the claim submission form.
View the status of your submitted claims.
For Programme Managers (PM):

Log in with your PM account.
Review submitted claims and approve or reject them as necessary.
View documents submitted with the claims.
License
This project is licensed under the MIT License. See the LICENSE file for details.
