# DataCastle_Competition
 数据城堡实战模型



# 数据来源
数据主要包括银行用户信息的脱敏信息。 

数据分为训练数据和测试数据，分别保存在train.csv和test_noLabel.csv两个文件中。 

字段说明如下： 

（1）uid：编号 

（2）x0-x19：银行用户的具体信息，已脱敏处理 

（3）y：银行用户的信用好坏，1表示信用好，0表示信用差。 

如遇数据下载打开乱码问题： 不要用excel打开,用notepad++或者vs code。
文件格式是通用的编码方式utf-8。


网络地址：https://www.dcjingsai.com/v2/cmptDetail.html?id=355


简单的逻辑回归，得分为:0.745