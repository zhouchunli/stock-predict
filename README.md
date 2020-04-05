# stock-predict
## 股票预测分析
1.加载数据，并将数据按年月日进行统计   
2.使用ARMA对价格进行训练，因不确定p、q的取值，于是进行区间搜索，寻找最优ARMA模型参数，即best_aic最小  
3.用最优模型进行predict  
4.使用plt进行画图  
