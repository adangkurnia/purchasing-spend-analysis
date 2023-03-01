# Defining the question
Purchasing is the process a business or organization uses to acquire goods or services to accomplish its goals. This part becomes very important in organizations since it gives businesses a structured way to address their needs. Generally, purchasing covers more than 50 percent of expenses of all the revenues the firm receives as income from sales. Based on that situation, the effective purchasing process can help prevent theft, fraud, or irregular spending since it requires documenting all business transactions.  Here are some objectives to be done in this historic procurement spend analysis report:
- To see the high-level view of purchasing spend
- Make wise decisions to predict and budget for the future.
- See lifetime total spending
- See total vendor
- See the different percentages of spending for specific periods
- See total spend by department
- Check what is most spent for every department
- Total spend by vendor
- Total purchasing spending trend
- Total purchasing transactions trend

# Collecting the data
The dataset is containing with more than 2000 rows of data in Microsoft Excel format with a period of data from 8 January 2020 until 6 January 2023.
Here is a list of columns of the dataset:
1. PO Date	
2. PO Number	
3. Project Code	
4. Vendor	
5. Department	
6. Usage Type	
7. Total Value (USD)	
8. PO Status
# Cleaning the data

- Checking any duplicates row
- Removing rows that don’t have total values
- Filling column in project code that blank with analysis code
- Standardizing column department and usage type
# Tools
1. Spreadsheet
2. Google Data Studio (Looker Studio)

# Analyzing the data
- Lifetime total spending for the whole company
The total spending on purchasing from January 2020 until January 2023 is $17.8M.
- Lifetime total PO has been made for the whole company
The total PO transactions made on purchasing from January 2020 until January 2023 is 2346.
- Total vendor
The total number of partnership vendors is 223.
- Total spending for a specific timeframe
The total spending in 2022 is about $5.7 M which is increasing 14.7% from 2021 with total spending of $4.9 M. Meanwhile, the total spending in 2021 is decreasing 31% from 2020 with total spending of $7.2 M.
- Total PO for a specific timeframe
The total PO transactions in 2022 reached 789 transactions which are decreasing a little bit to 0.3% from the previous year which reached the number 791 transactions but this is not giving a big impact since the total spending is increasing. Meanwhile, the total PO transactions made in 2020 were 748 transactions.
- See total spend by department
Department H is the department that spent the most on purchasing with $4.7 M or 26.47% of the total spending.  The second department that spent the most is Department E with $3.5 M or 19.82% of the total spending. The rest total spend of every department can be seen in the following pictures:
![Screenshot_2](https://user-images.githubusercontent.com/65482851/222129920-a0aaefa0-2b9e-4ceb-9612-7811c4ec9012.jpg)
![Screenshot_4](https://user-images.githubusercontent.com/65482851/222129959-16e83d06-ac3a-4681-ad88-b44b52030587.jpg)

- Highest PO spent 
The highest spent is from the Department H department with PO number 20432 on September 21, 2020, with a total spent is $1,264,910. This is used for Jetty Facility AHT Limin Handler Loading & Backloading.

- Total spend by vendor
The highest total spent by the vendor is Pthain with a total spend of $6 M and the total PO made with this vendor is 861 transactions. The highest PO made with this vendor was PO number 22276 which was requested by Department D for Bauer Synthetic Oil. The total spend by the vendor can be seen in this picture:
![Screenshot_5](https://user-images.githubusercontent.com/65482851/222130093-cbfa94e4-67d4-414a-bfe3-a71c328497dd.jpg)

- Purchase order spending trend
![Screenshot_6](https://user-images.githubusercontent.com/65482851/222130191-9f661102-48e9-4ce7-baee-ca653a9a4d62.jpg)
The scatter plot table shows a positive correlation between PO transactions made with total spending.  The table shows that the higher the PO transactions made, the higher the total spending of PO. The yearly trend of PO spending is decreasing from 2020 to 2021. Meanwhile, from 2021 to 2022 the trend is increasing but not reaching as high as in 2020. 
![Screenshot_7](https://user-images.githubusercontent.com/65482851/222130266-dd5bef68-182e-4d13-ac65-8af7bce411c8.jpg)
The monthly spending trend of PO from 2020 until 2022 is showing a variation but mostly it shows up and down pattern with the average monthly spending is $494.3 K. The highest monthly spending happened in September 2020 with total PO transactions is 122 and a total value is $1.8 M. the lowest monthly spending happened in January 2021 with a total of 36 PO transactions and a value of $55 K.
- Purchase order transactions trend
![Screenshot_8](https://user-images.githubusercontent.com/65482851/222130354-806f2a94-3234-43f1-b176-da794608f49b.jpg)
Since the correlation between PO spending and transactions is positive, the PO transactions trend also shows the same pattern with an average of 63 monthly PO transactions made. The highest monthly PO transactions happened in June 2022 with 144 total PO. Meanwhile, the lowest monthly PO transactions happened in May 2020 with 15 total PO. 

# Data Visualization
Full dashboard can be seen on this [link](https://datastudio.google.com/reporting/f5057bcc-008a-400b-a98c-a6fd99451c68)

#Summary
From the analysis, there are several important things that need to be considered in order to increase the good performance of Purchasing spend. Here are the points:
- The total spending in 2022 increased quite significantly compared to the previous year, so it is important to provide a better strategy in 2023 to reduce and avoid unnecessary costs.
- The number of partnership vendors is very quiet, so the main thing to do is to keep or even improve a good relationship with them. To reach that, something that can be done is to identify which suppliers are not only available during your urgent times, but also classify them based on a number of other criteria such as special discounts, reaction time, and other compliance parameters of the contract.
- Since there are various spent by each department, it is very important to set up the future budget for purchasing and make sure that every department will spend their needs wisely.
