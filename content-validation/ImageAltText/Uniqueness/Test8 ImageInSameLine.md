# [Test case 8] Images in Same Line - Image Alt Text Duplicated
## 1. Against the rule
### 1.1 Same alt text in same line
![test alt text 1](./images/pig1.jpg) ![test alt text 1](./images/pig2.jpg) 
### 1.2 Different duplicated alt text in same line
![test alt text 2](./images/pig3.jpg) ![test alt text 3](./images/pig4.jpg) 
![test alt text 3](./images/pig5.jpg) 
![test alt text 2](./images/pig6.jpg) 
### 1.3 

## 2. Follow the rule
### 2.1 Same alt text and same source
![test alt text](./images/pig.jpg) ![test alt text](./images/pig.jpg) 

--------------------------------------------------
Result: 
    "test alt text 1": 1
    "test alt text 2": 2
    "test alt text 3": 2