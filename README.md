# CHIP2021-baseline

第七届中国健康信息处理会议(CHIP2021) 

## 评测一: 医学对话临床发现阴阳性判别任务)

Task1: Classifying Positive and Negative Clinical Findings in Medical Dialog Task 



#### 简介

将mention与它所在句子+前后的各一个句子拼接做相似度匹配任务。

【text_a】 ——  【mention】

【text_b】 ——  【text_forward】 + 【text】  + 【text_backward】

【label】 ——  【attr】

线下验证集F1约0.680，线上测试集约0.678，预训练模型是ernie

测试环境：torch 1.7.1 + transformers 4.5.1 +  ark-nlp 0.02



## 安装

ark-nlp可依此安装：

    pip install ark-nlp

详情可见：https://github.com/xiangking/ark-nlp


