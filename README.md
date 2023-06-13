# yandex_afisha_marketing_report
Sprint 9: Business Analytics Practice for the company known as Practicum (as of 20230609)

## Project Description:
I have been told I've done beautifully in the Practicum course, and I've been, hypothetically and for the purpose of this project, offered an internship in the analytical department at Yandex.Afisha. My first task is to help optimize marketing expenses.

### I'm given:
- Server logs with data on Yandex.Afisha visits from June 2017 through May 2018.
- A dump file with all orders for the period.
- Marketing expenses statistics.

### I am going to study:
- How people use the product.
- When they start to buy.
- How much money each customer brings.
- When they pay off.

### Instructions for completing the project:

#### Step 1. Download the data and prepare it for analysis.
Store the data on visits, orders, and expenses in variables. Optimize the data for analysis. Make sure each column contains the correct data type.

**File paths:**
- [x] `/datasets/visits_log_us.csv`
- [x] `/datasets/orders_log_us.csv`
- [x] `/datasets/costs_us.csv`

#### Step 2. Make reports and calculate metrics:

**Product:**
- [x] How many people use it every day, week, and month?
- [x] How many sessions are there per day? (One user might have more than one session.)
- [x] What is the length of each session?
- [x] What's the user retention rate?

**Sales:**
- [x] When do people start buying?
    - In KPI analysis, we're usually interested in knowing the time that elapses between registration and conversion — when the user becomes a customer. For example, if registration and the first purchase occur on the same day, the user might fall into category Conversion 0d. If the first purchase happens the next day, it will be Conversion 1d. I can use any approach that lets me compare the conversions of different cohorts, so that I can determine which cohort, or marketing channel, is most effective.
- [x] How many orders do they make during a given period of time?
- [x] What is the average purchase size?
- [x] How much money do they bring? (LTV)

**Marketing:**
- [ ] How much money was spent? Overall, per source and over time.
- [ ] How much did customer acquisition from each of the sources cost?
- [ ] How worthwhile were the investments? (ROI)
- [ ] Plot graphs to display how these metrics differ for various devices and ad sources and how they change over time.

#### Step 3. Write a conclusion: advise marketing experts how much money to invest and where.
- [ ] What sources/platforms would I recommend?
    - I will back up my choice with the metrics I focused on. I will explain why I chose those metrics and share the conclusions I drew after finding the metric values.

**Format:**
I will complete the task in Jupyter Notebook. I will enter the code in code cells and text explanations in markdown cells. I will apply formatting and headings.

## To Do:
- [x] Step 1: Data Preprocessing
- [ ] Step 2: Do Math and Make Graphs
- [ ] Step 3: Advise