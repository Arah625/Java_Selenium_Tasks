# Java_Selenium_Tasks
Repository with tasks for practice writing tests in java selenium

# Task_Bankier
1. Create database (locally or in cloud)
2. Create table in that database with following columns (id, price, currency, unit, creation_date, creation time)
![image](https://user-images.githubusercontent.com/46853980/217957104-56b30aee-cf4a-4604-8283-075ab64d2590.png)
3. Create new project. Using Page Object Model write test, which:
  3.1. Opens up browser (Google Chrome)
  3.2. Goes to website https://www.bankier.pl/
  3.3. Navigates to -> "Rynki" -> "Surowce" -> Selects one mineral tab (e.g. "ZŁOTO") -> Clicks "więcej o surowcu"
  3.4. Retrieves price, currency and unit
  <image>
  3.5. Inserts retrieved data along with current date (in format yyyy-MM-dd) and time (in format HH:mm:ss) into previously created database
