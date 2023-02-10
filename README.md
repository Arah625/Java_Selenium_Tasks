# 1. Task_Bankier
1. Create database [^1]
2. Create table in that database with following columns: price, currency, unit, creation_date, creation time

|  | price | currency | unit | creation_date | creation_time |
|:---:|:---:|:---:|:---:|:---:|:---:|
|   |   |   |   |   |   |

3. Create new project. Using **Page Object Model** write test, which:
    - Opens up browser [^2].
    - Goes to website [Bankier](https://www.bankier.pl/)
    - Navigates to -> **Rynki** -> **Surowce** -> Selects one mineral tab (e.g. **ZŁOTO**, **MIEDŹ**, **ROPA**) -> Clicks **więcej o surowcu**
    - Retrieves price, currency and unit from header above the chart
  ![image](https://user-images.githubusercontent.com/46853980/218053228-5674be7b-cc34-435d-84bb-186001652ef0.png)
    - Inserts retrieved data along with current date (in format yyyy-MM-dd) and time (in format HH:mm:ss) into previously created database

|   | price | currency | unit | creation_date | creation_time |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | 1874.15 | USD | uncja | 2023-02-10 | 10:25:57 |

> __Note__
Preferably please use Google Chrome as browser.

> __Warning__
>Remember to close connection to database after every use of the method that connects to it.

[^1]: Setup database locally on your machine or cloud. The type of database does not matter you can choose **Postgres**, **Oracle**, **MySql** and so on.
[^2]: Do not add webdrivers to \src file. Instead, create folder on your hard drive where you will keep drivers for all browsers and could reference in various projects.
