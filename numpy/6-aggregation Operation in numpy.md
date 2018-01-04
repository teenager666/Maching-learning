# Aggregation Operation in numpy
        import numpy as np
        L = np.random.random(10000000)
        
        %%time sum(L) = 2.58s
        %%time np.sum(L) = 24.1ms
        
        np.max(L)
        np.min(L)
        
        x = np.range(16).reshape(4,4)
        
        np.sum(x , axis = 0)   sum of every column of x 
        np.sum(x , axis = 1)   sum of every row of x 
        
        
        np.prod(x)   multiply every elements of x and return it 
        
        
        np.mean(x)   mean value   // 均值
        np.median(x)   median value  //中位数
        
        np.percentile(x , q = 50)    50% elements of x < it
        
        np.var(x)  D(X)   // 方差
        np.std(x)  D(X)^(1/2)   // 标准差
        
        
        
