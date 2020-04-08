# [Test case 4] Image in code block - Image Alt Text Duplicated
## 2. Follow the rule

![ignore alt text](./images/pig.jpg)

### 2.1 Code block 1
```
::: image type="testimage" source="./images/pig1.jpg" alt-text="ignore alt text":::
<img src = "./images/pig2.jpg" alt = "ignore alt text" />
![ignore alt text](./images/pig3.jpg)
```

### 2.2 Code block 2
~~~
::: image type="testimage" source="./images/pig4.jpg" alt-text="ignore alt text":::
<img src = "./images/pig5.jpg" alt = "ignore alt text" />
![ignore alt text](./images/pig6.jpg)
~~~

--------------------------------------------------
Result: 
    "test alt text": 0



