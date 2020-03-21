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
| csv           |csv.reader()       |Need to save data in variables independently & intergrate them before using|

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

#### API ||DAY5,6
**HW05：Access API data & View the data**
1. Acess data from "Dcard API"：import requests (library)   
2. View data：import json  
  (1) data length of the API  
  (2) Columns names in the API   
  (3) Title, post time & Likes in each post in the API  
3. Information in API ：popular=true/false  
   * popular post：<div style="display: inline"> https://www.dcard.tw/_api/forums/pet/posts?popular=true </div>   
   * Less populor post：<div style="display: inline">"https://www.dcard.tw/_api/forums/pet/posts?popular=false" </div>      

**HW06 key：Header, timestamp & List sort**
1. Retrive data from "知乎"  
   (1)Sometimes without header, data cannot be access properly  
   (2) Timestamp --> regular tome dormat
2. Retrieve the earliest & latest post time of the data  
   * list sorting
   
### 2. STATIC WEBPAGE 靜態網頁
**HW07 Questions：**
1. Shortage or HTTP (request&response) 
2. Difference between  JavaScript & Python Interpreter  

**HW08：BeautifulSoup Library**
* request.encoding = 'utf-8'  
* class from 'str' to 'bs4.BeautifulSoup'  
* Solve '404 Bad Request' by headers  

**HW09：Picture Download**  
* from PIL import Image：Check if "image format" is the correct one   
* Cookies：Skip 'age' restriction in PTT
  [Python 網路爬蟲 Web Crawler 教學 - Cookie 操作實務 By 彭彭](https://www.youtube.com/watch?v=BEA7F9ExiPY&feature=youtu.be)  

**HW10：grab/PyQuery Library**  
* similar usage with 'requests' & 'BeautifulSoup'

**Day 11:Regular Expression**  
* SAMPLE
  *  Escape character「\」    
  * 「\w」word，「\d」digit，「\s」space  
  * '[]' for the "specific" first character & '[]+' for the "specific" first and "any" rest        
  *  or「|」  
  * Match chinese： UNICODE 0x4E00 - 0x9FA5    
* HW
  * filter IP Adress：Matching Numeric Ranges
  * filter URL "<a>    
                href=https://...    
               </a>"    

### 3. DYNAMIC WEBPAGE

### 4. DIGGING DEEPER
