# Vrinda Store Data Analysis Excel 2023
## Objective
Vrinda store wants to create an annual sales report for 2022. So that Vrinda can understand their customers and grow more sales in 2023

## PROBLEM STATEMENT
1. Compare the sales and orders using single chart
. Which month got the highest sales and orders.
2. Who purchased more men or women in 2022.
3. What are different order status in 2022.
4. List top 5 states contributing to the sales.
5. Relation between age and gender based on number
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

## DATA PROCESSING
CREATING PIVOT TABLE
PROBLEM STATEMENT
1. Compare the sales and orders using single chart
![image](https://github.com/PRATHAMESH9743/Vrinda_store_Analysis/assets/154798147/15aa7214-521e-4ea4-904b-d82f0a31e63c)

2. Who purchased more men or women in 2022.
![image](https://github.com/PRATHAMESH9743/Vrinda_store_Analysis/assets/154798147/e5ab5fd6-5243-4171-951d-99e817b83fca)

3. What are different order status in 2022.
![image](https://github.com/PRATHAMESH9743/Vrinda_store_Analysis/assets/154798147/2a8eb126-cd21-47ad-9265-8c35844b4a35)

4. List top 5 states contributing to the sales.
![image](https://github.com/PRATHAMESH9743/Vrinda_store_Analysis/assets/154798147/e30e596c-78f7-4112-be4c-458046edbe8e)

5. Relation between age and gender based on number
![image](https://github.com/PRATHAMESH9743/Vrinda_store_Analysis/assets/154798147/3bc9177c-9781-464e-8fb9-a5310f2a1573)

6. which channel is contributing to maximum sales
![image](https://github.com/PRATHAMESH9743/Vrinda_store_Analysis/assets/154798147/e5d87be2-49b1-4ac1-a844-85946060e864)
