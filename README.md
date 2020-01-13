# Aphla-zero 五子棋实现
## 参考 <https://zhuanlan.zhihu.com/p/32089487>
## 代码结构：
### game.py 构建游戏规则
### mcts.py 定义蒙罗卡罗树搜索部分
### network.py 构建神经网络部分，并建立进行自我对战收集数据和处理数据部分

## 提示：运行时，蒙罗卡罗树搜索400步，一局自我对战需要大约5分钟，训练开销很大，需要上千局才能有成果