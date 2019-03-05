## week_1 : 228 practicing 


### Topic 

#### 主要目的為讓現階段科技化的時代，許多學生很懶得每日看新聞，但是我認為新聞是學生必須所了解的為此製作出此程式，學生可以藉此視覺化的圖形列表，直接德觀察出那些政治人物、政治事件、以及各政治人物對於政治事件的相關程度，進而可以達到關心社會時事的功能

以下是執行的流程圖

![alt text](https://github.com/jeff20628m/Fintech_Class/blob/master/Week1/img/news_crawler_Diagram.png)


### Install

``` python 
git clone https://github.com/MiccWan/Political-News-Analysis.git
```

Since plotly is used in our project, you need to set your credentials to use the package:

``` python 
import plotly 
plotly.tools.set_credentials_file(username='<YOUR_ACCOUNT>', api_key='<YOUR_API_KEY>')
```

### Environment

[Python3.6](https://www.anaconda.com/) with [jupyter](https://jupyter.org/) notebook.

### Folder

* crawler : 爬取中國時報、自由時報以及新頭客新聞
* data : 存放爬取新聞、政治人物出現列表、政治事件出現列表、政治人物和事件關係出現列表
* final_demo : 最終實際操作
* jieba_data : jieba_library 所需的資料庫
* politician : 政治人物圖片以及文字雲圖片

### Resourse

[Most information you need here 'MiccWan/GitHub'](https://github.com/MiccWan/Political-News-Analysis)
