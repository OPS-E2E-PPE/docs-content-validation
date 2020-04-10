# [Test case 12] Image with same source file - Image Alt Text Duplicated

## 1. Against the rule
### 1.1 Same alt text with some same source
![test alt text](./images/pig1.jpg)
![test alt text](./images/pig2.jpg)
![test alt text](./images/pig2.jpg)
<img alt = "test alt text" src = "./images/pig2.jpg" />
::: image source="./images/pig2.jpg" alt-text="test alt text":::

## 2. Follow the rule
### 2.1 All images with same alt text and src
![same image alt text 1](./images/pig11.jpg)
![same image alt text 1](./images/pig11.jpg)

<img alt = "same image alt text 1" src = "./images/pig11.jpg" />

## 3. Bug
### 3.1 TripleColonBlock image src same
::: image source="./images/pig12.jpg" alt-text="same image alt text 2":::
![same image alt text 2](./images/pig12.jpg)

--------------------------------------------------
Result: 
    "test alt text": 5
    "same image alt text 1": 0
    *"same image alt text 2": 2 -> 0