# [Test case 3] Image use Triple Colon Block syntax - Image Alt Text Duplicated
## 1. Against the rule
::: image type="testimage" source="./images/pig1.jpg" alt-text="test alt text":::
::: image source="./images/pig2.jpg" alt-text="test alt text":::

## 2. Follow the rule
### 2.1 Unique alt text
::: image source="./images/pig11.jpg" alt-text="unique alt text":::

--------------------------------------------------
Result: 
    "test alt text": 2