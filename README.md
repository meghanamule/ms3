# ms3
The contents of this repo include the coding challenge. 

To complete this challange I have used the following. 

1. Anypoint Studio (6.6.1). 
2. Mule Runtime Version 3.9.3
3. MySql Workbench
4. Postman

Step1: Create a database schema ms3

Step 2: CREATE TABLE `address` (
  `type` varchar(50) DEFAULT NULL,
  `number` varchar(45) DEFAULT NULL,
  `street` varchar(45) DEFAULT NULL,
  `Unit` varchar(45) DEFAULT NULL,
  `City` varchar(45) DEFAULT NULL,
  `State` varchar(45) DEFAULT NULL,
  `zipcode` varchar(45) DEFAULT NULL,
  `id` varchar(45) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;

Step 3: CREATE TABLE `communication` (
  `type` varchar(50) DEFAULT NULL,
  `value` varchar(45) DEFAULT NULL,
  `preferred` varchar(45) DEFAULT NULL,
  `id` varchar(45) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;

Step 4: CREATE TABLE `identification` (
  `FirstName` varchar(50) NOT NULL,
  `LastName` varchar(50) NOT NULL,
  `DOB` varchar(50) NOT NULL,
  `Gender` varchar(50) NOT NULL,
  `Title` varchar(50) NOT NULL,
  `id` varchar(45) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;

Step 5: Clone this repo

Step 6: Import the project into studio 

Step 7: Use the postman collection to run the project.
