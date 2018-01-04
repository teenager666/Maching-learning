# Other way of create array of numpy

## 1.initial array of numpy by Python list
    import numpy as np
    nparr = np.array([ i for i in range(10)] )

## 2.
    import numpy as np
    nparr = np.zeros(10)  #Create an array of ten zero elements.
    # the type of array is float64
    
    nparr = np.zeros( 10 , dtype = int )
    #Create an array of ten zero elements of int. value = 0
    
    nparr = np.zeros( shape = (3,5) , dtype = int )
    #Create a three-row five-column matrix. dataType = int value = 0
    
    nparr = np.ones( shape = (3,5) , dtype = float )
    #Create a three-row five column matrix .dataType = float-64 value = 1
    
    
## 3.
    nparr = full( shape = (3,5) , fill_value = 666 , dtype = float)
    #Create a three-row five-column matrix .dataType = float , value = 666
    

## 4.   arange
    L = [ i for i in range(0 , 20 ,2)]
    Create a list of range[0,20) , step = 2 (step must be int)
    
    L = np.arange(0 , 20 , 0.2) 
    Create a list of range [0,20) , step = 0.2 (step is float64)
    
    
## 5.   linspace 
    L = np.linspace( 0 , 20 , 10 )
    Create a list of arithmetic progression of ten points.
    range[0,20]
    
## 6. random number 
    num = np.random.randint( 0 , 10 )
    Create a random number range[0,10)
    
    L = np.random.randint( 0 , 10 , size = 10 )
    Create a list of ten random number . random[0,10)
    
    L = np.random.randint( 0 , 10 , size = (3,5) )
    
    #We can define seed of random number 
    np.random.seed(666)  #such as 666
  
    np.random.random()    random number of float64  , range[0,1]
    
    np.random.normal()   #E(X) = 0 , D(X) = 1 , size = None
    #normal(loc=0.0, scale=1.0, size=None)
    
    
    
    
    
    
