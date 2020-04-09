---
redirect_url: "test redirect"
---
# [Test case 10] Images in Redirected File - Image Alt Text Duplicated
## 1. Against the rule

## 2. Follow the rule

This file has been redirected to another. (Only work in yaml header. 
Do not consider the openpublishing.redirection.json case)

![redirected alt text 1](./images/pig.jpg)
![redirected alt text 1](./images/pig.jpg)


--------------------------------------------------
Result: 
    "redirected alt text 1": 0