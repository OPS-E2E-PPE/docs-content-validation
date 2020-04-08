# [Test case 5] Images in Link - Image Alt Text Duplicated
## 1. Against the rule
### 1.1 Image in link
[![test alt text](./images/pig.jpg)](http://www.microsoft.com)
[![test **alt** text](./images/pig.jpg)](http://www.microsoft.com)
[abc ![test alt text](./images/pig.jpg)](http://www.microsoft.com)
### 1.2 Html image in link
[<img src="./images/pig.jpg" alt="test alt text" />](http://www.microsoft.com)
[abc <img src="./images/pig.jpg" alt="test alt text" />](http://www.microsoft.com)

--------------------------------------------------
Result: 
    "test alt text": 5



