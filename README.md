# NYC_Subway_Exploratory_Data_Analysis

Foot traffic of NYC subway stations are examined to distribute invitations to an event to be held in New York City at the beginning of June 2022.


8 weeks of data are used (April 9th 2022-June 3rd 2022) from Metropolitan Transportation Authority.

There are 1496200 rows in the data and the columns can be seen in the below figure.
![1_tXOPvhcp7q8KxSMVXDgnCw](https://user-images.githubusercontent.com/108690977/196007086-ad5e6892-8ef2-4a38-948a-b1844729d8ca.png)

Diff function of the Pandas library is used to clean up cumulative data and get daily data. ENTRY datas and EXIT datas are summed up and combined into one column called TRAFFIC.

Indexes of TIME column which shows the hour information (Object) converted to integer and shown in a new column called HOURS.

C/A, UNIT, SCP are combined into one column called TURNSTILE.

Null datas are removed. Missingno library is used to check if there are any null datas left.

![1_NguaCR6Cy42VMHKEVYEf_w](https://user-images.githubusercontent.com/108690977/196007541-a5926f7c-86f8-445c-b1d0-cad53fcadf65.png)

extract_whiskers function is used to box the data between legitimate values.

Traffic density:

![1_PkVhrgES9R5gEEtZ5EVCcg](https://user-images.githubusercontent.com/108690977/196007683-28449f6b-8b12-4a3a-bd61-056d0166be92.png)

Top busiest subway stations:

![1_n7edhfzcMGXH5hZsUJ5nxQ](https://user-images.githubusercontent.com/108690977/196007694-c4bd4bac-42b8-4481-99ae-b97919496a29.png)

Foot traffic by days:

![1_hT9KmLMoSjRJZprVYKHUJA](https://user-images.githubusercontent.com/108690977/196007701-92717f71-bf9b-4e8e-b79f-f48ce7e2ac7a.png)

Heat map(Days, Stations, Traffic):

![1_WXRbaCgAyUKFJEblhH03_g](https://user-images.githubusercontent.com/108690977/196007723-93c82240-f614-4c55-8feb-1057ee9318e3.png)

Heat map(Hours, Days, Traffic):

![1_01NdrVYQkl_ulxlcX4ypxw](https://user-images.githubusercontent.com/108690977/196007743-79e14cdd-3e00-4b8b-86a5-1f5dbc99425c.png)

34th street Penn Station hourly traffic:

![1_Q-MTyaTer0c4GSIlZ3iKmQ](https://user-images.githubusercontent.com/108690977/196007775-c7fde50c-119b-4dc9-88d4-50d14ef7fb7e.png)

