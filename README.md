**Food Delivery Dataset Integration & Analysis**

**Dataset Overview and Problem Statement**

**The goal of this project is to manage three different data files, each in a different format, to simulate real-world data integration.**
**
Files Provided**

    File 1: orders.csv (Transactional Data)
    
    File 2: users.json (User Master Data)
    
    File 3: restaurants.sql (Restaurant Master Data)

    
**Step-by-Step: Combining the Datasets**

    1. Load CSV Data: Ingest the transactional order records.
    
    2. Load JSON Data: Ingest the user profile information.
    
    3. Load SQL Data: Ingest the restaurant database records.
    
    4. Merge the Data: Perform joins using the following keys:

        orders.user_id → users.user_id
        orders.restaurant_id → restaurants.restaurant_id
        
        Join Type: Left Join (to retain all orders).
    
    5. Create Final Dataset: The resulting dataset includes order details, user information, and restaurant information.

    Output File: final_food_delivery_dataset.csv

**Final Dataset – Key Analysis Areas**
The merged dataset serves as the single source of truth for the following analysis:

Order trends over time.

User behavior patterns.

City-wise and cuisine-wise performance.

Membership impact (Gold vs Regular).

Revenue distribution and seasonality.


**Repository Information**

The datasets used are saved in the **Dataset** folder.
The solution code and analysis are present in the **hackathon_code.ipynb** file.
