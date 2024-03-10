# COVID19 Open Data on Domestic Infections
The table is compiled using the Open Data on New Coronavirus Infections ( https://www.mhlw.go.jp/stf/covid-19/open-data.html ) published by the Ministry of Health, Labour and Welfare of Japan.

- covid19_jp : Table containing daily trends in the number of new positive cases.
  - Date: Date
  - ALL: Number of positive cases nationwide
  - Hokkaido: Number of positive cases in Hokkaido
  - Okinawa: Number of positives in Okinawa
- covid19_jp_unpivotted
  This table is an unpivoted version of the above table. However, rows with 0 persons are deleted.
  - date
  - prefecture
  - new_cases: Number of positive cases
You can also use the following table
- japan_population: Population of Japan by prefecture (2020 census)
  - prefecture
  - population
## 1: List the three prefectures in order of the number of new infections on 3rd September
## 2: List the three prefectures in order of the number of new infections per population
## 3: Output by date how many prefectures had more than 100 new cases from April 1 to 30, 2021.
## 4: On October 2, 2021, find out how many new cases of infection Hokkaido had on that day.
The output should be one record.
## 5: For the entire period (January 2020 to January 2020), find out which province had the slowest date of the first infected person and the date of the first infection.
## 6: For each date in January 2020, find the province with the third highest number of infections on that day.
## 7: Add a column to the number of new infections in Tokyo for the month, indicating whether the number has increased since yesterday.
## 8: Using the results generated in the previous question, tabulate the maximum number of consecutive days (e.g., 3 consecutive days) of increase in the number of newly infected cases from the previous day during the period.
## 9: On February 14, 2021, list the top 10 (including ties) in order of least number of new infections
## 10: Find out which prefectures had more than 1 new case of infection every day (all 365 days) in 2021.
## 11: look at the seven days in Kyoto Prefecture in 2021 when the number of new cases was the highest and the seven days when the number of new cases was the lowest.

