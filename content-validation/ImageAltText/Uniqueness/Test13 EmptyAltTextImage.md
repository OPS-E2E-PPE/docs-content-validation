# [Test case 1]3 Image with empty alt text - Image Alt Text Duplicated

## 1. Against the rule

## 1.1 Markdown images empty alt text
![](./images/pig1.jpg)
![](./images/pig2.jpg)

## 1.2 HTML images empty alt text
<img src = "./images/pig3.jpg" alt = "" />
<img src = "./images/pig4.jpg" />

```
## 1.3 Triple Colon Block images empty alt text
::: image source="./images/pig5.jpg" alt-text="":::

## 1.4 Alt text cannot be null
::: image source="./images/pig6.jpg":::
```
--------------------------------------------------
Result: 
    Empty
