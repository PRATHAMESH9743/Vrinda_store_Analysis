# Vrinda store Data Analysis Excel 2023
## Objective
Vrinda store wants to create an annual sales report for 2022. So that Vrinda can understand their customers and grow more sales in 2023

## PROBLEM STATEMENT
1. Compare the sales and orders using single chart
2. Which month got the highest sales and orders.
3. Who purchased more-men or women in 2022.
4. What are different order status in 2022.
5. List top 10 states contributing to the sales.
6. Relation between age and gender based on number
7. which channel is contributing to maximum sales
8. Highest selling category.

## Import Data into Excel 
![image](https://github.com/PRATHAMESH9743/Vrinda_store_Analysis/assets/154798147/9a4ef5f6-0253-475d-a588-9f812ac06ad2)

## Load the Data
![image](https://github.com/PRATHAMESH9743/Vrinda_store_Analysis/assets/154798147/45dbe21d-dc70-4878-9c9a-7c2193dc426b)

## DATA CLEANING
## Step 1
Put Filter to all the column and check for any irregularity.
In Gender column, The Men, M, Women, W is given. we have to replace 'M' with Men and 'w' with Women

![image](https://github.com/PRATHAMESH9743/Vrinda_store_Analysis/assets/154798147/5b838dc0-9f71-4db5-93c6-e92a57bc21c6)

select the entitr Gender column > press ctrl+H. 

Find and Replace tab will be opened
Now replace 'M' with Men and 'w' with Women. Follow the same steps for Women with 'W'. 
![image](https://github.com/PRATHAMESH9743/Vrinda_store_Analysis/assets/154798147/83f5ac41-00a3-4628-9de3-2a730817e2ab)

## Step2
In Quantity Column, Here Find and Replace one with 1 and Two with 2
![image](https://github.com/PRATHAMESH9743/Vrinda_store_Analysis/assets/154798147/2331b3b2-d9d5-4008-b979-e32205a22868)

Replace one with 1, and do the same thing for two with 2
![image](https://github.com/PRATHAMESH9743/Vrinda_store_Analysis/assets/154798147/4f2b28ed-c3b9-4037-8b4f-9bc3f4b29842)

## DATA PROCESSING
According to the 6th problem statement
we have to build relation between age and gender,
we will apply 'IF' condition
=IF(E2>=60,"Senior",IF(E2>=40,"Middle Aged Adults",IF(E2>=18,"Young Adults",)))
![image](https://github.com/PRATHAMESH9743/Vrinda_store_Analysis/assets/154798147/df14470b-cf42-4b87-bc94-bee954ab3830)


