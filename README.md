🍕 Food Delivery Data Integration & Analysis
Hi there! This project is all about taking data from different places—like a CSV file, a JSON file, and a SQL database—and bringing them together to find out how a food delivery business is actually doing.

I built this to answer real-world questions like: Which cities spend the most?, Do "Gold" members actually order more?, and Which cuisines are the most popular?

📂 What's in this Repo?
I’ve included the raw data files so the code has something to work with:

orders.csv: This is the "heart" of the data, containing every single order, the date it happened, and the total bill.

users.json: This contains info about our customers, like their names, which city they live in, and if they are a "Gold" or "Regular" member.

restaurants.sql: This is a master list of all restaurants, their cuisine types (Italian, Indian, etc.), and their star ratings.

Food_Delivery_Analysis.ipynb: This is the main notebook where all the magic happens! It cleans the data, merges it, and calculates all the answers.

🚀 How to Set It Up
You don't need to install a bunch of complicated software. The easiest way to run this is using Google Colab.

Download the files: Download the three data files (orders.csv, users.json, restaurants.sql) and the .ipynb notebook from this repo.

Open Google Colab: Go to colab.research.google.com.

Upload the Notebook: Click on File > Upload notebook and select the Food_Delivery_Analysis.ipynb file you just downloaded.

Upload the Data:

On the left sidebar in Colab, click the Folder icon.

Click the Upload icon (the paper with an arrow).

Select orders.csv, users.json, and restaurants.sql from your computer.

Run it!: Just click Runtime > Run all in the top menu.

📈 What did I find?
After merging the data, I discovered some pretty cool things:

Gold Members are Key: They make up 50% of all orders.

Top City: Chennai is the champion city for revenue, especially among Gold members.

The "Pricey" Choice: Mexican food has the highest average order value.

Quality Matters: People love highly-rated spots; 3,374 orders went to restaurants with a rating of 4.5 or higher.

Best Time to Sell: The 3rd Quarter (July–September) is the busiest time of the year.
