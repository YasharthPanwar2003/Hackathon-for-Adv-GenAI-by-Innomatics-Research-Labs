NO IW ANT SAME TEXT PLS THSI ---------->>>>>>>>>>>>>>>>>>> Hackathon-for-Adv-GenAI-by-Innomatics-Research-Labs



Hackathon jupyter notebook submission



Innomatics Research Labs | Advanced GenAI Internship Hackathon based Test







Dataset Overview and Problem Statement



1️⃣ Files Provided



You have three different data files, each in a different format, simulating real-world systems.







📂 File 1: orders.csv (Transactional Data) Click here







📂 File 2: users.json (User Master Data) Click here







📂 File 3: restaurants.sql (Restaurant Master Data) Click here







2️⃣ Step-by-Step: Combining the Datasets



Step 1: Load CSV Data



Step 2: Load JSON Data



Step 3: Load SQL Data



Step 4: Merge the Data



Perform joins using keys:



orders.user_id → users.user_id



orders.restaurant_id → restaurants.restaurant_id



Join Type: Left Join (to retain all orders)







Step 5: Create Final Dataset



The final dataset contains:



Order details



User information



Restaurant information



📁 Output File:



final_food_delivery_dataset.csv



3️⃣ Final Dataset – What Students Should Understand



Students must analyze:



Order trends over time



User behavior patterns



City-wise and cuisine-wise performance



Membership impact (Gold vs Regular)



Revenue distribution and seasonality



📌 This Final dataset is the only source of truth for all questions listed in this Hackathon



































IN this repo the datasets used are saved in Dataset folder







and the notebook code are present in Hackathon_solution.ipynb file

Hackathon-for-Adv-GenAI-by-Innomatics-Research-Labs
Hackathon Jupyter Notebook Submission
Innomatics Research Labs | Advanced GenAI Internship Hackathon Test

Dataset Overview and Problem Statement
The goal of this project is to manage three different data files, each in a different format, to simulate real-world data integration.

Files Provided:

File 1: orders.csv (Transactional Data)

File 2: users.json (User Master Data)

File 3: restaurants.sql (Restaurant Master Data)

Step-by-Step: Combining the Datasets
Load CSV Data: Ingest the transactional order records.

Load JSON Data: Ingest the user profile information.

Load SQL Data: Ingest the restaurant database records.

Merge the Data: Perform joins using the following keys:

orders.user_id → users.user_id

orders.restaurant_id → restaurants.restaurant_id

Join Type: Left Join (to retain all orders).

Create Final Dataset: The resulting dataset includes order details, user information, and restaurant information.

Output File: final_food_delivery_dataset.csv

Final Dataset – Key Analysis Areas
The merged dataset serves as the single source of truth for the following analysis:

Order trends over time.

User behavior patterns.

City-wise and cuisine-wise performance.

Membership impact (Gold vs Regular).

Revenue distribution and seasonality.

Repository Information
The datasets used are saved in the Dataset folder.

The solution code and analysis are present in the hackathon_code.ipynb file.
