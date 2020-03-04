# 2nd-PyCrawlerMarathon
## 【PROJECTS】

## 【LEARNING NOTE】
### 1. INTRODUCTION
#### Data Source & File IO || DAY1 
|Data Source     |       |
| ------------- |:-------------:     
|file       |csv, json, xml       |
|API          |[what is API](https://www.youtube.com/watch?v=zvKadd9Cflc)     |
|Crawler     |website    | 

|File I/O |   explain    |functions|
| ------------- |:-------------:|--------------|      
| urllib      |Download data by url|urlretrieve|
| os         |Manipulate file directory|os.path.join(), os.listdir(), os.makedirs()|
| (file handling)  |open--> 'r', 'w', 'a' -->close ||
| cardet     |Identify encoding type|chardet.detect(file.read())|



#### Data IO：CSV || DAY2
| library       |command            |Shortage|
| ------------- |:-------------:     | -----:|
| pandas        |pd.read_csv()       | |
| csv           |csv.reader()       |需要另外將資料儲存成變數並整合之後才能使用 |

see more ：[Reading and Writing CSV Files in Python](https://realpython.com/python-csv/)
#### Data IO：XML || DAY3
import xmltodict：transfer xml to dictionary

#### HTTP CLIENT & SERVER ||DAY4
* HTTP：Request & response   
* Structure   
 **Request**  |Header|Content  
 **Response** |[Status](https://developer.mozilla.org/zh-TW/docs/Web/HTTP/Status)|Header|Content
* Method   
Request：GET & POST  
Response：API & HTML VIEW  

### API||DAY5,6

**HW06 key：Header, timestamp & List sort**
1. 取出知乎問題發問時間  
   (1)Sometimes without header, data cannot be access properly  
   (2) Timestamp --> regular tome dormat
2. 取出第一筆與最後一筆回答的時間  
   * list sorting
   
### 2. STATIC WEBPAGE 靜態網頁
**HW07 Questions**
1. Shortage or HTTP (request&response) 
2. Difference between  JavaScipt & Python Interpreter  
**HW08：BeautifulSoup Library**
* request.encoding = 'utf-8'  
* class from 'str' to 'bs4.BeautifulSoup'  
* Solve '404 Bad Request'：headers  

### 3. DYNAMIC WEBPAGE

### 4. DIGGING DEEPER
