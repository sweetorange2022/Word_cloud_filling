# Word_cloud_filling
用python进行文本分词并生成词云 , <b>FROM [wordCloud](https://github.com/fuqiuai/wordCloud) </b>  。

## 需要安装的包  
* `sudo pip3 install jieba`  
* `sudo pip3 install wordcloud`  
* wordcloud包依赖于Pillow，numpy，matplotlib   

## 使用方法  
+ 将图片放在　images　下，这个图片建议从照片中抠图，抠一个自己喜欢的轮廓下来，替换alice.png   
+ 自定义　doc/alice.txt　的词汇(也可以不修改)  
+ 执行　python demo.py  

## 其他
* 分词采用结巴分词，并支持自定义字典
* 分词结果进行词频统计分析，并导出
* 词云图可自己设定背景图（英文词云图不需先进行分词）
