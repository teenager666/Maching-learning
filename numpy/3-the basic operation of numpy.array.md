# The basic operation of number.array


    import numpy as np
    x = np.array(15)
    X = np.array(15).reshape(3,5)
    
## 1.The basic features of np.array

### * dimension of np.array
    x.ndim   
    #out:1
    X.ndim 
    #out:2
    
### * shape of np.array
    
    x.shape
    #out:(15,)
    X.shape
    #out:(3,5)
    
### * size of np.array
    x.size 
    #out:15
    X.size
    #out:15
    
##  2.cut into slices
    X[begin:end:step,begin:end:step] #dimension = 2
    #range[begin,end)
    
### * difference with python list
    
    xx = X[:2,:3] # this is a reference of X
    xx = X[:2,:3].copy() # this is a copy of X
## 3.Reshape , change dimension
    
    x.reshape(2,5) #get a dimension
    x = x.reshape(2,5) #let x change with '='
    
    x.reshape(10,-1)  #-1 let computer compute
    x.reshape(-1,10)
    
    
    
    
