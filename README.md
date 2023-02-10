# Java_Selenium_Tasks
Repository with tasks for practice writing tests in java selenium

## 1. Task_Bankier
1. Create database (locally or in cloud)
2. Create table in that database with following columns (id, price, currency, unit, creation_date, creation time)
![image](https://user-images.githubusercontent.com/46853980/217957104-56b30aee-cf4a-4604-8283-075ab64d2590.png)
3. Create new project. Using Page Object Model write test, which:
    - Opens up browser (Google Chrome)
    - Goes to website [Bankier](https://www.bankier.pl/)
    - Navigates to -> "Rynki" -> "Surowce" -> Selects one mineral tab (e.g. "ZŁOTO", "MIEDŹ", "ROPA") -> Clicks "więcej o surowcu"
    - Retrieves price, currency and unit from header above the chart
  ![image](https://user-images.githubusercontent.com/46853980/218053228-5674be7b-cc34-435d-84bb-186001652ef0.png)
    - Inserts retrieved data along with current date (in format yyyy-MM-dd) and time (in format HH:mm:ss) into previously created database
