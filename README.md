# 数据集下载链接
https://pan.baidu.com/s/1nB0i_qzRMzUTz0I8HCqQ2Q?pwd=8the

### node.jsonl文件
每一行通过字典存储了全部数据，各字段的含义如下
* ‘Source’: 原始频繁API使用序列
* ‘Insert’: 插入算子的标签，形式为[[位置， API], ...]
* ‘Change’: 替换算子的标签，形式为[[位置， API], ...]
* ‘Change’: 删除算子的标签，形式为[位置, ...]

### dataset.json文件
通过词典记录了node.jsonl中每条数据属于训练集/验证集/测试集中的哪一个，各字段的含义如下
* ‘train’: 训练集的id列表
* ‘valid’: 验证集的id列表
* ‘test’: 测试集的id列表
