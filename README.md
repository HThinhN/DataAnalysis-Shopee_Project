# Analyzing Men's Fashion - Shopee Project
This project was implemented to analyze competitors in the men's fanshion on the Shopee e-commerce platform to be able to find out their tricks and trends in selling men's clothing.

## 0. Individual introduction:
| Full Name                  |   Student's ID   | Student's Email                    |      Individual Email              |
|:--------------------------:|:----------------:|:----------------------------------:|:----------------------------------:|
| Nguyễn Hoàng Thịnh         |  20120587        | 20120587@student.hcmus.edu.vn      | hoangthinhstkt@gmail.com               |

## 1. Data description
- ***Data Resource:*** https://shopee.vn/Th%E1%BB%9Di-Trang-Nam-cat.11035567

- ***Data Schema:*** 
(Only included mainly used data columns, having a lot of different columns when collecting)

|STT| Column name    | Description   | Data type |
|---|:--------------:|:-------------:|:---------:|
|1| itemid| Product Id | String|
|2| name| Product Name| string|
|3| shopid| Shop Id| string|
|4| stock| Number of products in stock| int |
|5| sold| Number of products sold| int|
|6| liked_count|Number of likes for product| int|
|7| cmt_count| Number of comments| int|
|8| price| Product price| float|
|9| item_rating| Product reviews (including average rating and number of stars)| dict|
|10| is_on_flash_sale| Is the product on sale or not?| bool|
|11| shop_name| Shop name| string|
|12| shop_rating| Rating for shop| float|
|13| flash_sale_stock| Number of products remaining in the flash sale | string|
|14| crawl_time| Data crawl time| datetime|


## 2. Used tools:
+ ***Programming:*** Python
+ ***Technique:***
    - **Crawl Data:** HTTP Request (Selenium: Fail)
    - **Store Data:** MongoDB
    - **Preprocessing & Analyzing Data:** Numpy, Pandas, Scikit-learn,...
    - **Visualizing Data:** PowerBI

## 3. Content:
Include 4 folder:
+ **Task1_CollectData**: File.py
+ **Task2_StoreData**: File.py, File.ipynb
+ **Task3_PreprocessingData**: File.ipynb
+ **Task4_VisualizingData**: File.ipynb, File.pbix