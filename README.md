# visionox-Lot
### @wanglei_visionox

##### 19/4/9 OIC目前不处理canceltrackin，MCS只能处理上报两次complete，也就是transjobid 是 3的情况，后面遇到新的问题再解决，注意搬送次数要加上STK15->AUU的那一次。

##### 19/4/12 新增功能：判断是否有多个ship，如果有多个ship，只保留第一个(也就是时间维度上最后一个)

##### 19/4/22 新增cell，省去了修改代码的步骤，为了处理没有到AUU记录的lot，少读一个文件，开始时间要重新定义