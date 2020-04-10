# [Test case 6] Images in Paragrath - Image Alt Text Duplicated
## 1. Against the rule
Here are some words. ![test alt text](./images/pig1.jpg) ![test alt text](./images/pig2.jpg)
Here are some words. ![test alt text](./images/pig3.jpg) <img src = "./images/pig4.jpg" alt = "test alt text" />

Here is another paragrath. ![test alt text](./images/pig5.jpg)

Here is another paragrath. <img src = "./images/pig6.jpg" alt = "test alt text" />

Here is another paragrath. <img src = "./images/pig7.jpg" 
alt = "test alt text" />

Here is another paragrath. <div>
<img src = "./images/pig8.jpg" alt = "test alt text" />
</div>

--------------------------------------------------
Result: 
    "test alt text": 6



