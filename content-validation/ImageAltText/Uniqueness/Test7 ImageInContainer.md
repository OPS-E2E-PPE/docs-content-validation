# [Test case 7] Images in Container Block - Image Alt Text Duplicated
## 1. Against the rule

### 1.1 Image in header
### ![test alt text](./images/pig1.jpg)

### 1.2 Html image in header
### <img src = "./images/pig2.jpg" alt = "test alt text" />

### 1.3 Image in list
- <img src = "./images/pig11.jpg" alt = "test alt text" />
- ![test alt text](./images/pig4.jpg)

### 1.4 Image in table
| o                                                       | o |
| --------------------------------------------------------| - |
| ![test alt text](./images/pig5.jpg)                    | x | 
| <img src = "./images/pig6.jpg" alt = "test alt text" />| x | 

## 2. Follow the rule

--------------------------------------------------
Result: 
    "test alt text": 6

