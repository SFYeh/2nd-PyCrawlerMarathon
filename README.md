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
| library       |command            |缺點|
| ------------- |:-------------:     | -----:|
| pandas        |pd.read_csv()       | |
| csv           |csv.reader()       |需要另外將資料儲存成變數並整合之後才能使用 |

see more ：[Reading and Writing CSV Files in Python](https://realpython.com/python-csv/)
#### Data IO：XML || DAY3
import xmltodict：transfer xml to dictionary

#### HTTP CLIENT & SERVER ||DAY4
* HTTP：Request & response 
* Structure
| Request       |Response        |   
| ------------- |:-------------:|    
| Header        |[Status](https://developer.mozilla.org/zh-TW/docs/Web/HTTP/Status)|      
| Content     |Header  |
|             |Content|

* Method 
Request：GET & POST
Response：API & HTML VIEW

### 2. STATIC WEBPAGE

### 3. DYNAMIC WEBPAGE

### 4. DIGGING DEEPER
