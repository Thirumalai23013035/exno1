# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output
            import pandas as pd
            df=pd.read_csv("SAMPLEIDS.csv")
            df
            ![Screenshot 2024-08-17 140037](https://github.com/user-attachments/assets/1c97e622-fa5f-4fd6-9ada-9919f632d492)

           df.tail()
           ![Screenshot 2024-08-17 140715](https://github.com/user-attachments/assets/2d335de9-0801-4c5c-8359-69331784b584)

           df.head()
           ![Screenshot 2024-08-17 140736](https://github.com/user-attachments/assets/8a38385b-88ac-48eb-bcd6-edd1729d1c96)

           df.isnull()
           ![Screenshot 2024-08-17 140751](https://github.com/user-attachments/assets/bcb4ca12-b4df-466c-a416-ba68a340de74)

           df.not null
           ![Screenshot 2024-08-17 140802](https://github.com/user-attachments/assets/9c6e7257-670c-406b-87c9-aecc8f4326f9)

           df.dropna(axis=0)
           ![Screenshot 2024-08-17 140818](https://github.com/user-attachments/assets/868c8914-2d99-437c-a955-7a5ab4998e2e)

           df.dropna(axis=1)
           ![Screenshot 2024-08-17 140832](https://github.com/user-attachments/assets/94e63d0c-e1a3-49e3-9105-eaa4c1a0689e)

           df.fillna(0)
           ![Screenshot 2024-08-17 140853](https://github.com/user-attachments/assets/34d7990a-3210-49c6-86ad-996158789029)

           
           printf(df.shape)
           ![Screenshot 2024-08-17 140916](https://github.com/user-attachments/assets/d7b1730f-3bc0-40fd-9093-399211e72cbb)

           df.describe()
           ![Screenshot 2024-08-17 140927](https://github.com/user-attachments/assets/6fbbbec5-59e7-4f44-9a73-d9ca7194afef)

# Result
          <<include your Result here>>
