# [Test case 9] Images in included file - Image Alt Text Duplicated

[!include[included file](./includes/included_file.md)]
## 1. Against the rule
### 1.1 Same alt text in same page
![test alt text 1](./images/pig1.jpg)
![test alt text 1](./images/pig2.jpg)

### 1.2 [Now not support] Same alt text in included page
![included alt text 1](./images/pig3.jpg)

## 2. Follow the rule
### 2.1 [Now not support] Same alt text and same source in included page
![included alt text 2](./images/pig.jpg)