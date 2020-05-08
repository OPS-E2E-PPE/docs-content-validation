# [Test case 9] Images in included file - Image Alt Text Duplicated

abc [!include[included file](./includes/included_file.md)]
# h1-before [!include[included file](./includes/included_title.md)] h1-back

abc [!include[included file](./includes/included_title.md)]
## 1. Against the rule
### 1.1 Same alt text in same page
![test alt text 1](./images/pig1.jpg)
![test alt text 1](./images/pig2.jpg)

## 2. Follow the rule

## 3. Bug
### 3.1 [Now not support] Same alt text in included page
![included alt text 1](./images/pig3.jpg)

### 3.2 [Now not support] Same alt text and same source in included page
![included alt text 2](./images/pig.jpg)

--------------------------------------------------
Result: 
    "test alt text 1": 2
    *"included alt text 1": 1 -> 0