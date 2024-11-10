# life_urban_data

## Problem statement and tasks
A major pain-point for customers is non-arrival of professionals for their service without prior intimation, (called No-Show) and leads to a bad experience. In case Accelerated prediction of No-Show enables the platform (Urban Company) to deploy additional strategies to re-assign the booking to another professional. You need to build a predictive model to predict No-Show probability of a request

- Perform a comprehensive EDA
- Share additional relevant insights and visualizations
- The associated sql query for computing the same in a JUPYTER Notebook
- Build a predictive model to predict no-Show given the features described
- Find the ideal threshold for prediction if , the benefit of a correct no-show prediction is 400, benefit of correctly predicting a no-show NOT happening is 0, cost of incorrectly predicting a booking as no-show is -200, cost of incorrectly predicting a booking as NOT no-show is -150

## Data description
- ns_count_1day : No shows done by the partner/provider in the last 1 day and last 1 month
- is_exclusive_lead : Is the shown lead exclusively shown to partner/provider or not
- responded_lead_1day : Number of leads responded to by the partner/provider in the last 1 day and month
- paf_count_1day : Number of cancellations where the partner/provider was at fault
- delivered_lead : Number of leads successfully delivered by the partner/provider
- service_delivery : ratio of deliveries to lead responded by the partner/provider
- acceptance rate : ratio of responded leads to number of shown leads to the partner/provider
- pro_rating : Average Provider rating given by customers
- Total Income : Money earned by provider net of commission and expenses
- days_no_block : Days not blocked by the platform and available to work
- days_block : Days blocked by the platform
- number_times_blocked : Number of time blocked in the last n days
